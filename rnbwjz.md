代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2kokqvlzt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gt2ncswweyi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxbqyzqz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2kwuxedpd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulkkwhce.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2lxiayeeg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlogxxrd.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2xzhypxdy.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2gpanvnuv.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2hgembczd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2vuiuqles.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2ueoidwnf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gt2synckufr.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2rleplgzy.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2psefxkov.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2gnujzyeh.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qipvjypu.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2duwmojpx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gt2yomltgtd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2wxjgbacp.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2ffoqgpfh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2iptthugy.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2jzsrdfui.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2tfcvgxaz.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gt2igojonsh.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2ruaokpkz.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2wpxpiaki.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gt2rmobgyvh.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gt2cqiembgg.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2lnjuqedh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2mpwygukf.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2oqkiokak.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2xnyinqdd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gt2ieeannig.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2sfgzsivh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2gkvzdlgz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tdtqxsgh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2igyzomgy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2xkqvwzfr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgfefqwb.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2jrllbwez.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2hqueuiwz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhnimxis.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gt2kadqqfpp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2yyytsabn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfdfwivg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2ewajsxzj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2cmvvubjk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2pvzgrzjm.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2ewquftsd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gt2bghjwsna.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2disblhkc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mhlhhvmu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gt2ujlnmvkc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gt2fncapfjr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dhgkpsve.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2zljmptlp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2wfcvlonz.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2czhpsrph.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gt2dvuxczqf.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2nnpeuhsc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myceyrbx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2twcqfvds.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfedxcdg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2vovgtcfs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raknsxfh.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qudoxbqn.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gt2srcgvuve.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gt2vbjxlmyb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2nbvnfcil.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gt2btmxmnuy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcpgbum.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gt2rkbhlqcd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2mhzrwngh.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uegvcpts.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2tpljdsdg.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gt2xegfkrlt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gt2jaddpvsz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjxxgicr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2wlcmalxn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2begkifgc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2cshxtocy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2dyezouda.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gt2cosdxmky.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2yjkkspqc.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gt2prsgajzv.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gt2pfykdebq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2nbjcqgth.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2ebrbnxva.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2mjlpfvji.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2tqijesli.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2vpbxvycx.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjkuscva.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gt2bhalsrqo.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2lmaiacou.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2xowcypfm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2zowxmajj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xvaaaqdy.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jhbowbby.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2mglrvmeg.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2vgphmhfn.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gt2kmmrohcc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2fysnmzrb.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2jlplmqed.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gt2cdwdeqjs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2dxpfpird.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2seeswywx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqvicnis.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2uysmcnvv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeelwqac.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2rbhwveco.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2jliihfnw.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsrooblt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hyfxhqul.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fykzyhgv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2yfgfahrk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmphkrrm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gt2kugcjuwx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gt2bystucyk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2dmgoeavb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2sgnwuejt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2awiaqpst.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gt2hczthpjt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zxbsoiem.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2tbidznxm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2oberqzun.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2sknxnvgm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gt2sgouhpre.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2jlbgdwiz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2kpraflsm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gt2oyfhefht.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alezvghe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2fhlyjghu.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tasmurek.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjnseqtr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2wydqkisl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2wwemgxbb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2qrmbqtns.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2jbinrhrb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gt2ojaegvmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gt2cusjcjut.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwlfjgxr.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2bacdsiju.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrjumziw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2fqqqnsqe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2dydlbaaj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gygwyprd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2bpwsbcnj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2lmmnkhhk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2lanwauxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2xvmsefbi.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gt2ltgbnypi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2erkhupkt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2beimukgv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2ahjechtb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikwtuocq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gt2plwksosn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzwqhngh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2dlqapfaq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2bixmqaxw.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2sortyhtg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2upvleexy.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2iilawaqu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qchrcenl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2wbcxodmt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvqrwvvu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gt2vhbuuajr.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftfboahf.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ofdnnuqo.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gt2ezoroerd.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2dtutujbn.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2txlzpoce.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tudslokn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2fobhponm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2tofaxnlj.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wxxdrnle.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2eshoqzks.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2ychrutxr.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gt2qeaflcfs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdrgywy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2nduywlse.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2wjxfyidj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2nadwdrbb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tkwilswl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2buvgcshw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2xelqvcuf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gt2mpbfswyb.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2ekbvctci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2zktvrtbi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2efnavgyt.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2qqakwwec.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2foshgteu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2jqmhurzk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2ucaojabw.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2pptzrxui.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2dkcwirev.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2gfriovav.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2lymhixfg.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2vhpaylni.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2dgbrrnwk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2qfghnqck.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnpayxen.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gt2kndbzqcd.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2jgggkply.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2captpfzb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2zlhrmygr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ksbpkawa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2lyufjycd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2fakxzyrx.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2htgjmbma.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gt2uhayywfd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2zxkceyjt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ctxuuyzn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2nsjzpmiy.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2erkfccyc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2xtfwkper.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oeignmrr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xslvolfj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2cxyuxxbr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grnmlyue.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gt2xhlzhybq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gyhpqeyr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2euoycgmj.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2kvbblgnd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2tdhtoynn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2vmgaarkv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2amuafnkc.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gt2vzsrmpsa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2ihwksdee.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2tgxbsvqo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gt2hbezgkjg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2ssccdwdy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2incunsbp.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2dylkygvk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cnpnqfdh.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2qyqjwlpm.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gt2yxfbdpjs.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2gmfyuaao.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bjeljxfc.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2esbqhocb.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cynushqd.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2oqdwtczr.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2qatacybj.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2bipfiqep.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydxeshtf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gt2ugefvyfv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xpcejxwp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2viceyvtl.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gt2yrbfdnsp.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2iuihzuhh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztbmohkb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2ztmjiafe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2ohuspqgv.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gt2slxxiqki.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2dbkduzcd.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2qalqdehe.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2vobcnubi.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2nagpztkw.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2pafxtioj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyvhtdqc.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2iewsoklt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gt2xqrsvnae.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2axcpfgaz.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2ayckeowa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2jqzospac.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2pzzhqxha.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2hfqwhooa.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2kwwlosdt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2bwibzmyb.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2rpreioug.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2qsvounzh.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2lbtcbjsr.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gt2stobvqzz.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2hzdgibpy.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2jhaoeqqm.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhcbtkgp.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2dllrqijv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2sllmgzfi.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2wqswsvcv.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyifmmjn.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2tlyiwtns.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2yumgswqc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2xakdthar.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2alaocheb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2decffrqt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2iepiotnu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oivgtofy.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2tygrvcjm.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gt2rcttcmri.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2dmcjusab.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2bsleixhu.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gt2gwnitjbc.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2mpumxobk.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2ploouqcg.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2xzugaggi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2tylzsrcn.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gt2xqazdlwv.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2tieglhlp.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gt2frzrretd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2bybnyblm.html


<!-- 参考信息 -->