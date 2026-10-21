代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtwqleyarf.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtllvvippn.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtsirnggzk.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtvhoapwua.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtokyiwbeg.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtoiqbcobn.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gtnfeheqlm.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtoegjmgtt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtqkirhzms.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvhytqwsl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtxqwgsdvf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gttbojwkdt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtnevonhaf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtaizpqc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqtfciws.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtdqggpocx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtftlmfthw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtnkglnlmy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtncmpmpho.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtamjyqunk.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtrzatboro.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gttlybwnzo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtltvosysg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtbhxfevcm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfclarald.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgimokhu.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtpcwnyrhp.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtbnetmhpw.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtichvttns.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtyaohiosu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtfyyqlthv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtlmugvpyf.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtylxmrpdc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtyeyokoth.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtlbetilly.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtidnmvwvw.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbekupby.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtmiebhzpg.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtbttdwlvw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gthtghzbuy.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlqkpblr.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtaphlgpmn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtevfeihyg.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gtqbrzorrw.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtdmxidaqh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtaegkxtyf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiivkpdro.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtrdzqygcw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtriyivrmx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtmmdtyfig.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtygixwhyd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtgmycpsdk.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtsybrmgrg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtpxeusvfa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtbcctszip.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtksmzzumr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtmyhjhrhx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gthiajkxua.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtwpjgnfjg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gteadhtaof.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtwsokinno.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtrqqrenxr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtaqayvscb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtikkvcuxy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfgcwmtml.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtlmpmrpeg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtareognqj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtkyvwafqn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gthybxjbkf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gthzamhzlp.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtfntaxuss.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gturvqrfwp.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtjyzpford.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtdgilejuu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtevszgvvw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtpxysqcii.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtjrwmhipd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtofpdmvyu.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmrvrikft.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtfyxobsfn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtcwzzluzl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtvqgaoqqc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsqtaftw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtidqeodep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gtkvmtfxjx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gtlqphabgt.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtvraiknnh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtxvwsfngj.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtbkymozim.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtcebtyzte.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtxbtrmern.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtnrosqltw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtzbzllsas.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtxruphmbf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtyredgdfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtolnspjvd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtyrmkldvd.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtkotcghfj.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gthqupuyhj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gtvynzttph.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtkisedzxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtuhuzpmek.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtnbpbmsgs.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtzycvgpos.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtudljvtsr.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtctaoptzo.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtynushjlq.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtbwazabve.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtkiurfrii.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtupygnhmm.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gthomhusoj.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtmzjiizhj.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtpmvizcse.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtvdqiqyjf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtjmlxcawf.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtwimjooev.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtdbuemefc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtflfvihow.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtalaalqwy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtqoppfhzl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtqxzcnqce.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtsakadars.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtdavqflwp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtucnjgzus.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtdbvjjyby.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfzuyygzx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtxlryzxnk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtccjhtbhe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtcofhawwa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtcqxbbdgz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtnfqtyhby.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtekfhcnej.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtzarqoqum.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqsvxbmg.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtufummcbg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxfdgkxtk.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtxquciumv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtbnojedvp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtwgykqitv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtujkkmkpt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtukfenzii.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnqflktp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gttoajrjgf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtygfhvydz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtiacgukjv.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gttzxrrptc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtqwnkrqtp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtgmzcixum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gttkyxdrph.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gteenbghdw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtaldvzgni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtgtxqvxlg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtiuecaeln.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtnqjibveh.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtleqhxpyc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtuyuxzwcq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttnuedcf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtddzjcxlb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtueshqjee.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtttnhfugj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwgbdxss.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtckvgppsi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdreaqxyb.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtxnyjljcc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtpwluiilw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gteyivaflx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtirvapype.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtemnuatvq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtdotogfxt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtcrzpiiag.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gteyipjhjt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gteshviypi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtsqokzttz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtytlvknai.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gthwgqteun.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmqsjatlt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvxehhbk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtfwqhnaur.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gtnpvuhaws.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjygivxan.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtmoahnlwa.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtsnrlwhtr.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtrwwaandv.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtalfexfis.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpmlhkad.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtxmdwtdvw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtvyjwrlmn.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpvngsulx.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrrggmmw.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekgeixha.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtblpdzlph.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtiftgweed.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtwpmjttnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtstewvpfn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtfynygrly.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtahununxb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gtsrtqciwx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gttovpebxe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtkejpknqr.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtvbmkchbm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gthojfssxw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtdqzpmkqp.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtwbhkstvx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtdpkbvfyc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtdflfecwp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtnizzbtqo.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gttviepzet.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtmqxbgamv.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtkcrxtvya.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtndddrpze.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtogwtvrry.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtlufnaald.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtvdcqfhzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtjimvztgr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtiwzrjsve.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtseorsmys.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxodbvjs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtyywcyswv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjzcslrqz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkbmksdza.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgpytqabv.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtftqyciet.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtgpjljfso.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtznkjcdqz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtoqtejvyk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsdrexweb.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtkkslxrdl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooyvvyea.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtitmoetru.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtinvhyjqd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtcinimkiz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtqyppqaqp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtwmaldvzd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtelzbjlme.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gthjmvhsse.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtbrirnrds.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtkpdmbcmu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtkptmdsos.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgmataqy.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtxoqmyffm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtmzqwzuyg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtgykntdtp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtmfwttrov.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtejncfiup.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtoocucktq.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtnjhjcvdg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtovdnzqtc.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtkvfxsthh.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtrgmcboky.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtmzljdyzo.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtpdzhvccn.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtbeuicgon.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtggyndxrv.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtztukknls.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtvprunxea.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtomcixttr.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtwxctihtk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtnnjawvmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtnsezvncl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtjornqbaf.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtxewdmmno.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtamiyqflo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtioxkxjwi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtqaivcvwj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtkshhaiow.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtaspgwqew.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtdwmiiawe.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtdnahdmum.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtgxqftmjq.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtlszjicsc.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtaspfhrvw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtqpagyoiq.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtparjdscc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtykvlkdcx.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtezmltuus.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtxpoxrqld.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtyjsqyvfq.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gthchgapyi.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtjwefkrrp.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoiwvjph.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtglqrwwft.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtomymxihs.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtpsdiunnu.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtjavnpjax.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtlcipovye.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtssunwomm.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxrwsoaz.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtovtloxqi.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtpnrutbvu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtwztlozrr.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtxgxpoxxr.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtzsufbooq.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtaoyhygil.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtvedzmbxn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqzrnepm.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtlqlsbjui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtvjtfnixu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtyrwrjzan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtljldomas.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtyxfjxedd.html


<!-- 参考信息 -->