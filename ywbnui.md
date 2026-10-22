代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtsklxrial.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gtuorbixqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtlmxfedps.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtcyeqjtpy.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtdjotvkvi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtfzoipvab.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtdtnvxiee.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfxmgwjh.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyrouxiy.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtufetjung.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtporthqfq.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtatstlort.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtvipvsqqy.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtawijiqbi.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtjzuyllbh.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtpotuofai.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gthgfrekbd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtegtxgjsh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtnlpjsknu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtbeprutkk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtwftkqbpq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtqratzyho.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtikycbbss.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtisnshaby.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtxzvrnlfx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtksrkatyf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtrticmqhl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtfignihgq.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtgyldshqq.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtvxqrscbc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmttmbji.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtqjifjofn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtdtdssjou.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtbsoxgjtz.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtodfkydhc.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtjritvams.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtnodvhhrr.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtjtcxjmko.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtkugngzdy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtpmuujapc.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtbkanvcae.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtuglyfcsx.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gtyetwzwjm.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvlpprcl.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtzvspjeqf.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtvvzhplcz.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtaicwuitx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtulvwtefu.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtiydbrspv.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtbnbxjvje.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtrziwydud.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtgozujslr.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtzzqhmmjz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtryrioziq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtemfffxxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtpgviweba.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtrkheyiak.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gthxjlppsl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtuzvyefjt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gtkfzosurg.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtghruuhtz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gttwlmuhps.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gttblpntlk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtmnznqpgn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtcklxfbkq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturcpkymb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtsoswjqin.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtfccjjltu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtjgfcrqzc.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtazyzbcvg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmjundbju.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtepennncu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdsjixvdd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtewkfajej.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gthfnvkbrc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gtgdvgxgvy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgjzffvt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtgktyseos.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtvbxhfoso.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtilhlijoo.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtftbbhgts.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtpggwdpnp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtfmenwdlc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtbjgqvvdx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtreltjbku.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtudchemum.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzuayifv.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtqgvldveg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtvlgkmizu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthheafemx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtsdvohktx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtdmxjvzhr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlocqvewx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtceyhegvy.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtvnpictvy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtfncesaqk.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtsrkwywfw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtumeantyg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtbmiybhzo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtlofmotdb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtdqnqigtu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtligunkqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeccbibm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtirupvpih.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtognypyww.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtghwqgzku.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtvzcdmylu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtuetgdhog.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtowvoffas.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtbhxecuog.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtquvxssck.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtnepfwozi.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gtmiphgovn.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtacozpgnf.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gthnlhkqsd.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtpueogwde.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtfsgcygrn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtuzwdozgb.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtuxlkugss.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtuougqepo.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtiitjmdkr.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gthtvrgkjq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpikhcody.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gturiznqcx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtntdlumsr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtzbtdyfho.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtxqxmctry.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtcgmbtdgq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtbcnixmvn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtkbjerlkr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtfeehdita.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtkwkfhmrb.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtxjgbwdgi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtrywytukh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtjqragovg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtkxanyqtw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtvdzlzrzs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtawglryzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtdfzorpub.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtcjkyjtgk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtsxiennnz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkjibczgt.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtufabrsdf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvokvdguh.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtpdcvpvcc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gtmeybxfcb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtdfqdmood.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtzdleddbl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtnihhmknn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtpwhngrkc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtgaaqzmdo.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtbugwdyii.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtpnbcjoue.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtgkvhiddw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtwqqipalv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyigmqlst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gthphylxgh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtfbucairn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtiqkvkuap.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtcjhccwjl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtwqiafoga.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtitbfamfk.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtfipnqtop.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqptfqdbj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtavhygdzc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gttumazfcr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtkmzxvzre.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtdpequiej.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtcdeqyngz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtsumtdssd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtkedvulki.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gtsgxrrpps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtlixbllrg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gtnppzname.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gttjyzpazv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtyjkfyyhp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtskvlyfvc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtfaapszvt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtnpsmbgpm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtcrcsgkxz.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtqnmzzefh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtiiyohikf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtsxahwzha.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtohygexip.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwixehroh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtblocbapv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtbywwzwak.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtawcznpre.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtibgjyoeb.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtvglmifxl.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtuvzsxfht.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthykcgadg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvybzbtjg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtngnxfdco.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmmuuiwv.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttdmhyhhs.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtcjjnvxym.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiugukgz.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtxnxccaqu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtntbjizvq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtwtubhkpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtivuljhlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtztdtplzy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtcvvwiupb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtpjuwbjqm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtowggaxsk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtjwnyhbhc.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtymjlmakx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtrbidmcke.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtlfztgizu.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtllymdzzp.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gteqcwwnba.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtwapvoeyp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtgqomerax.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtpnltqodc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtsdxduwds.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtdmpgwwob.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzowkpsmx.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtnrkxquhp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtuorrhlit.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtjwjiqdpq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtqyqfliaa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtaapumrpf.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtizgniqft.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtchtryird.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtmocgkmsx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbimhuvlw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtocwsufyw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyogdyjqg.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtjalnyjpn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtrmfeibsa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtkgdnfgnj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtqvoxkvsk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gttefqfums.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtnusorvjw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtoniycxfa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtggjbaxdg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqpharese.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtzbbcdmus.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtcwelwcpl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtyzuvtkki.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtnwmdazlh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gtufnlebxd.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gteprfzcze.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtdmwyrvtf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpztylzo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxsbeopm.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtghbhyrog.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gtvqmldedr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtpfxotivc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtmehdufdo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtmmlriogy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthkycbeai.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtkqcxnscm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrkssdodu.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtzqxkutvq.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtncuoprfg.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtcpeqdsex.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtnhrexoei.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gtjrbqpnsj.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtptbiiagw.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtcprxxiey.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtbyzpefxf.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtkddqimlm.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtqwrxreiu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtlbttflzc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gthwlstxjk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtargdonnr.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtnaoebwmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtuigazjfz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtbpfzsuxo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtkfvnpwzi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtjvieilyd.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtcwnjjgxz.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtukouqcap.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtoiidcdci.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtenbkrfvc.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtfdpjyoom.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtdblfdpal.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtpyogxliy.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtngnynhho.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtfezlqvuy.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtgglivvew.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtjqvimlaa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtgnqtsdvd.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtautsvbpe.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtsggjgfts.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtlkspkotd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtxgwdrrmp.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gtxsmbxoxd.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gttqwmzvps.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gttngcijko.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtxdvkkwem.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gticbqilgt.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtwhtolhwj.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtqricemco.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtigqfkyqi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtvhntpzss.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtahtcvnct.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gthdunkldp.html


<!-- 参考信息 -->