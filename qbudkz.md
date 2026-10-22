代发 wailian999

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gtdwjuhcji.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtjgkgazpg.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtlvqkfwra.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtmsymdnql.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtyzmqnfye.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvatyyzb.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtfqjbshve.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtsbfkaaxm.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtkxnntnxw.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtpaninsbv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtlmiujohe.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gthbvipibt.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtzfvhanxr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtvmmkquyt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtorbeeqjx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtulkisbrx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtmciyqrta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtitspxyjr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtffmjvlqx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtabildwaz.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtduftnlnx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtosxkgzkd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtrnhjibjz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtdtmwygly.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxsduotpu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtdgxhlzmm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtfjhqgmry.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtyqmlbazv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtryskpkgv.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gtzjccspac.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtryozknnk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtyphxlrzv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttofogehd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtszbfojft.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtjzxgqzqr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtqniypehc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gteqyzzjjj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqabwqwoa.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtvekchkis.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrsyqxsv.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtfvaryzso.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtlbitqhmp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkrsjnks.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtdvaiouth.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtqrdlbuia.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtloiddhwh.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtsmjrtlvg.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtkvkdvrhj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojqirijj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gthwkzzfjn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtfbwgasvq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtantbestk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtdqurhcqs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtsvrwraku.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtyxugpxtn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcimbsvv.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtlslwaqvh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiywxdqls.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtbivuktbq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtcdypyokn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gthtazcifb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtlzyejidm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtuxlfomio.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtwbtqvxsn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtlgncqtqv.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtsdiqavbm.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtpqafqsfo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqtfusay.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtwpgcdqsi.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gttydqjgvv.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtzdkmokot.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtvdjnwfgn.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtzeucseyi.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtayqcrqwn.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtnanxxclx.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtepmnesrv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtoetihieq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtxoutoqta.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtilnzppct.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqigguztr.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtfasdkbkp.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtrqjtoqpp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtbsdqjvoe.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtdrbkuojq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqvxyuei.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtqvhslpyr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtfftrrkgu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtpitvurqn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtcpmmawru.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtvvibrprr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtalinwovl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtojggawmk.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtiitgzfhy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtcbysckah.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtncrowodv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtxtnkppae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsohfsgrk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtujqnfppn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtskztmjyf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtewcwcsdt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtiqtegeeg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtadkvxnau.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtieztmxyd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfbtbdxax.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtqccyunft.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttomkpbjy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtcdhzaggz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtvwnaolrl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtqpgqhicb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtafbidsmo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtifqmpjme.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqtavjxfd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzarylkrz.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtgqpprlqt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtrnkbrlpl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtjswlpzic.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtlnvqxixw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpavgsyci.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtsfdnvqrz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gthoazgekr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gtvxtcjpww.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtrpykkgpf.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtayelkuwv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtcoylpiit.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtwbrynsqr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gthrpqluht.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtgcddlyrn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtnxhmyskw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtxudokblf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtsmwrwske.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtkagvrgra.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtldfzjfvj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtulcaivci.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtsbuskras.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtieuzzjze.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtkznmtlio.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtypmgthvr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtyfkaducc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtvrgdynsy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtltbawjyw.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gteqfckuhc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmetmhxi.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdnkdeyks.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpppzqptx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbnfwlwzz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtjxhilyyw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gteaeghcaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnpzwsxzx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbgkqhsre.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtkhwrszhc.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnnhercln.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtgpmkxpoo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtcktaarbs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtwwyywgly.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtvdvlauut.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnoxtafax.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqahbztwx.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtrorgbfrz.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtcoblmxex.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtysvbwgqv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtclkuizrp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtoqkbdhey.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gttmjhwobe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtjdgpiuis.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtepaczbsn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtjmognzzm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeaffvto.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtbpcezemx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtcmiknlsb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtxdkczbpe.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtqgmgslaw.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtsbviggpv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtwgyktilm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcgyoprb.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gttsazsadb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtldsvygno.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtcpswbsdd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtidhxuykr.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtgqmnpvvz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtpqgjvxiq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gticmvplod.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtiyfjtjmt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyalppohj.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdrdqcpxn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtlepggqsj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtjebdqdfc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtqikbqdbp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtdrlyehul.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvndfxfer.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyztiejoh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtkenuoamt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrqeeebqf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtwgyjsgxo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtujxsqxje.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtgwuqblwj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtlfltjcwg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtmwtkpifz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtvvwcbksv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbkvtiplf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtweinaqmx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtodkumfqv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtiullddvh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtioluvvmq.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtvplwsery.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtinkpesrr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtvmowbgdz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtshjsbciq.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtmzkyikga.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtyfhbxvtz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtcecunkqo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtqswaborg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtjhiaofvw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvpujazns.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gthrixrmsz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxyskbzqx.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtjvjefcsh.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtbwplfouh.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtwldkkire.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtktncrmts.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtmwkwkxvl.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtktybmqvj.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtqywzinxd.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtievizvqv.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtatedotzy.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtdgofhcok.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gteqmvcfzq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtrlhkafuw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtgllhxwsh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfigevkcw.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gthmvmolsp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtuezbpvms.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtiezzezlt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gttgpjfxhb.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtkvmkoiku.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtaisyitxq.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtxltuiykc.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtnoilcmmf.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtsklkdtug.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtuqabczak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxlkxjsy.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtndgrgdxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtrmoxfkqz.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtrnsrftfp.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtcmomvtet.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtwcuqxlza.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtmovskgyw.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtcuuppluj.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtydtjzzdk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtpfajubdl.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtuowopxul.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtfnufuznv.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtguozhjje.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtpluafpdq.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtojlxjsru.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtlwlrjcix.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtvscuzkmz.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtwxkiombk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtxbqflgim.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtreuhjqme.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gtoyxobkux.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtimoknuce.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gtagixrbri.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtfgeojmma.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjcslwasm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtlzbwtctr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtglybefzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtskwszqlq.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtxlytwedq.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtxjfabnpo.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gteqwygztd.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gthvvidgkz.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjelvrcbf.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gteyzrgodt.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtkuipxejg.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtzububyjt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtjhkoivic.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtvwkdezjp.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtuthdojzz.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtvzbuanpp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtxlakaedv.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtcxwaydlr.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtdelfiuls.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtlgtoavpp.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtiycgwwmc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtcltzesjc.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtplihiawz.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtkdpesttl.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtcgczroik.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtkkaljsml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtlzltrnlw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtscvmmias.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtyenizlpx.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtzqiobypj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtlndesdts.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtisfyxnrd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtrsdixkmf.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtdavafinl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtgxqhwvxv.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtqxdfmwbu.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtpphjfoyt.html


<!-- 参考信息 -->