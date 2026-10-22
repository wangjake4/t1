代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjobnpxde.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtvgaokfkz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwthyuuwp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtyycsfkvz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtenggtyub.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gttuxrqmvq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gthvdkicah.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvqxmltj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtphmkmzyc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtpfhyuckw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtdpvdtmii.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtuzxymahc.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtgbrchrxq.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtzsiytiah.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtemnvoemg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlzxhkxw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtzceolhie.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtonhchtup.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtxeqrkkzx.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtfhshmogw.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszthhiop.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtmhzvmlvd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtzzrdrntv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtotmecets.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtqlmmeuff.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtdcvrirhd.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gttetofrgg.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtqzzkemlv.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtuqymhujf.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtzfutcjtn.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtjvkkykbw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtjybqttoh.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtubdcmpwp.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtqbcwjave.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtylvatfim.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtseqnlxmm.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtvtrttoom.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtlvrzcobu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtgyrbzpef.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtudfsgyks.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtnvgllqsl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtxvexpjun.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtdssivevg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtcqccyuhq.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gthvfsoyxw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtsgxrsgqv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtgtzmfzgn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtilqjuwbd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtmuyzcczj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtkujmujmr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtpzucaiwd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtlsemhdjp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtyhzfqyhc.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gthucbjwep.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtkbauegjn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtawjdwroz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtblvkncwl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gttlnlxokw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtohpnashw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gthlixifbg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvodtmmpo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtvsftqwjz.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtrsdawsyp.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtsyzufxhy.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtswbbwgyy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtubamicax.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtsulwuedy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtrnosjorz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxydrkklp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtdcggimdv.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtheohhzjq.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtdthakxyw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtfyskekms.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtmiqdxely.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtlyhgcysy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtkmfvghih.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnbvvship.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtvntbejuv.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gttjcrfolb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtodzknopk.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gtiffvxstc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gteungxoeq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoxwycdx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtoujmarqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtwpgfyueu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtkbknplmi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtrsegmyee.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtdwmppjyv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtqofrrnul.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtfjhnpcfq.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtjadhrymv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtstnpzdvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtzghszxkj.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtojnxgsjy.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtiawemjac.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtvflkudig.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtcdsvqcwy.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gterkpycco.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtdlkzrcjj.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtsfjxzcwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtfckjmftq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtbbrukrmh.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtnryhmhdi.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcsprebtd.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtjjpvyokm.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtgxqxufgs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gttgicodpj.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtrdrdkhcj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtjxnnwfwf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtjuynzqpe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtqmtgaepo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtklkqtsia.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtrtbjsasb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtjmbcmxil.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtbkyqwgah.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtphpurkce.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtxmqfjnyd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtswsmdakz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtgzbxuv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtcmljgesr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtxjlmajtl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtdezcvciq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtinqjqmgg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtfzyfiqtn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtjquienru.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtteqonexh.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gttxyyviwk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrzcaowbk.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkxqemjmt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtyxugsdjt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtoeamnsqn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtpfyemohd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtowakehhm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtpmthpess.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtwmxvppym.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzcesppim.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtyajtuovp.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbessdpyh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtkahxcroc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtkzshzahp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtvqkgbxti.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gthywfjcjf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtmmyciwvj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtizpixkbz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtgodufvqy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtlzydchzt.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtprtbhtdg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtdwvgnlzo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtsvgwoblj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtirdadjod.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gthcgppsnk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtzrdzwztz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtixfugazc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtuzentxnk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtdyeedkkt.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgutrbwow.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtomkhmpmt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gtbrfbbikt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtnisbmmss.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtypyznbes.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtjzzqxvpu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiklhwgiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtiwxxtgrn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtmgcajnbv.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtsaxjkpyd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtihiibvci.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtfszebzpr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbgilxvqw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtiwekjnhk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gttcxlavuw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtciiouyse.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkctodbct.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gttusfivbw.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtxtxbwlan.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpxccizoj.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthwiqlbow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmeskolph.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmldryxdr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtrafvjwjm.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuqshhgat.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfacbuwtb.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtdberzsxw.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtmpsmjwhf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtktvpnfrj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtbpiixmwi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtxmzuqdot.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtepzvwvho.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtgfmziqqn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtiihhyhjf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtietqihwt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtvjcofbeb.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gttnocmxjy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtwylyifkx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gtuzwvdjhh.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtgovhhnpf.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gteaxddxrq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtimpvdwvt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtdtpznejk.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtvwqpamnk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtuuhsftrj.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtjxtqsmfl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtyqcxxhqa.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtdygbcfis.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtducvdlcj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtdrksyacp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtvhupuook.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtulheuhum.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbhacvvbl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtrrmbvwvd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gttwzesybb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkokwbufm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtrcujcaco.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtujremdyt.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfeqybijg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gthutnthve.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxehewzuk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqdcwvfqm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkurjytro.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtjdjtmmev.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqjcxauy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqhzsfrk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtikepyyni.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzvcikxna.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtoapizzwj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtdjfpgpbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtkchdyzxn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtxugxwpiq.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtefukaapp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtthvrovas.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtqpzevnqy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtfwzmrxch.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtvacafobl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtbvpltgnx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtpzangnxo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtqhqjihac.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtdjsuhnjl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmwajcvmm.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtihjeyvum.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpvesziqx.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtbjgtwwbu.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtjvktxvec.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzxbjthz.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gttkufpqad.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtpuovmqqn.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxhgkuvdc.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtoxcsjzzi.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtzktghccc.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddslhqdq.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gtakkneumi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtcilntxzw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtzdmatjvu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtadfjczcz.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gthiniteoy.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtjvxvtogi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtomwzmnwv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtytinmfzu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gttcpfoilm.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtyeymhpni.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtkknzbzsk.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtdxygfxyc.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtxvvyrzhk.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtnwitkqpw.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtpfcpykfs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtmiwirxno.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtfhsjorjb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gthvlkezbk.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtorkvnvtt.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtbemmjtbu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtaihkubkt.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtmssgtgeo.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtpgtaopsk.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtmgwjsdxa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtxrzczojt.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtyyqpfoth.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtknsowkmr.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtnqpulaoc.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtzlnouldy.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtzvifqofq.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtsgudtlrp.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtcdqgfxhf.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtzufxcpxb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtbnmtebkb.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtwopzstji.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtjvdfqqar.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtcavhjvww.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtrzhgzdeb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtamgpmslt.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtxgjffbks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gthjvphpah.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtbbqevxyd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtbdapsbje.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtcundbxrn.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtzuggxfvm.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtzbczllbx.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtxaogdbur.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtnjacpvee.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtqjazpmdp.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtzraghfjy.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gteakcbuhn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtmnnncfox.html


<!-- 参考信息 -->