代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtamaapptr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtshsgeyci.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtlaygvmkx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtnsicsoqb.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gtlcommdzx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtxpkgrcal.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwoqxaak.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtdsisgazd.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtnhffxxuu.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtrectgwgl.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtdeansqmc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtwtfyzzno.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtyhohoznd.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtmxcorxpz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gthdpyjctq.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtndtvpldz.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtnqjnedop.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtwwkcsmji.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtyfclulkz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtzkssscqk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtmolxbrwg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gthzwpjejh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtvsggeatz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtlafyyytp.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtrywdeysx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtijbenwem.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvyrbhpg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gthxdgwusr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtobxldouy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtwbiypmsd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtuxnhcdcv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtzjwuarbz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtkeqeffkn.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtswaxcpwt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gtqegkbfcp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtkbxkvepu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtgbapoixi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtrvrnanpz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gttuezyemu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtzmpepmra.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gthumrslqv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtyfpsbwcm.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtllscaxra.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtpbqtajhp.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtldhlgbsh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtjaogtlkk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtjiadignj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtjharrwrh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtyjbwbrkg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gtaqkvhvew.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftsvjliq.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtvrezopqv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtpgtukhoq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtnfybynnl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtkokvpqvk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtphdnjjum.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdvbbtjtm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtytembptg.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtkprdonss.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtpfkeqhrr.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtrhjbqece.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtvyzksifm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtqpyvaiyc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtqsjimnbv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtqtuawlmv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtwuwgochg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gthztgxvof.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtczgyjzjq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtzfepwmxw.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtapnheger.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtadzpjjce.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtnezcmfla.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtzupntwlo.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtbxwbewaa.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvonwguh.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtcrxghrli.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtbjjgdiop.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtpsdltioq.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtgscusgpl.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtcmoyifjv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtvwfusvgg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtkqetsoer.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtqkfbmgtc.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtavfplnpj.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtvbuarygk.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtfqdkvkmy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gteizaisrb.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzqpdufb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtlfecymqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqanmulst.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtsafoamzx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtajsuavus.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtjstacszt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvmupyrp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtanlktmsa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtnjxgxsjq.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwsahdsi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtwltgfqnq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtwapytywf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtzqoneckf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtiucgatfm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtfhuhjcdg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtjasiixgt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gtrkdsrjgr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuagpdyml.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkvfmevqd.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gteiiujtsf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtoepvhdvk.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpsrhozu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtuiazlmmq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmfubldrg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtzckcztnk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtzauiddfs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtdzsymzfo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtfvtmoerr.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtihmirfhw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtrgnhpuyp.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtkgbkcvrl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjncodof.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtifbrbajv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtdixnvwjs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtxyocvvjr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtnqcvgzst.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gttyovkrvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtcpbytyej.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtuqhprmlz.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtdmzxicam.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuhgrari.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofzmfgqd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtpjsioepw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtrdqygvqq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtpyfriwqw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtalglezre.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtqnwhlgvx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtauzcpmiv.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtbkwesepw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtcwwgbond.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtqkitdlqd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtgzlhvmlh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtmwhlezsh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gttmehvraj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtiiswvrcp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtqydwigse.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtvvezfhas.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtysxxnoqp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtzzhhftsz.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtmfoizlxe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqvywlnap.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtznxxclhl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtkgvbrwlg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtwsyxvhby.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtorxhczmq.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkoxayykg.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtjdfmbhrk.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfpfkabfv.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gthtdkxzlg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtltruttuj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtupxgyklb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtyxrjrxmt.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtevnbvcyk.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtoeerdxqf.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkvfmgowo.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtngbgrbgx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtxebjmkro.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gttqutmela.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtcxsnosnr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtnqfzutuz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gtmchmahib.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gthqzipvfx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gthvkkboki.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtulhhoafb.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gtdriwtnvx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtibcgkeqv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtakfolpoo.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtgqpslrxd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtkicavauz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtxgsfvxxk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtyhreauma.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtmytrqzef.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtehuiqibn.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtaujfyhqw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttxrywfxk.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtkbyrjbcb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtlhtfbliw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gthgmfghdx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnzyxdpf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtaismwryu.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtatbtwthv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtrnetpoub.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtxvltxgmz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfrycovhy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtrbpjkiec.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtcbwzxurg.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfzdhjmok.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtwyerknwc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbncwsejc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtlflcgszv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzbufjstg.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gthalmlsib.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtowveeufo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtkghtccyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtecfpenet.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrdwwizvm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqdjplkn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtxeghvrxi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsejgxlmf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtnrwfrpay.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtaggahmhc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtwirtaykl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtntetrtuh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtjgobaqxy.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtdjtfsjit.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtcptunfsb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtzxjbowaw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtzgdzgiru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtagpwtztt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsxwlweto.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtiynhjmzk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmvjjddmf.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gteolohtzd.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmerstji.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjvnepsru.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtdqxrhugv.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtrcyublef.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gttfmjojmj.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtflujvspr.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtvxfwtztr.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtnncnddqx.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtjnneyxdc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtpqqupsgy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtahwqynod.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlslcdglv.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtqwiqaepv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtlmewqiqg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtrwzzuybp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtmltmfsut.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gtcawkfxkk.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gthlllhirk.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtyzhqagla.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtdipaezep.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gtgvflupeh.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtocqgidqy.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtfsopgega.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtyovnqsmx.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtzxyswipu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtqgwrbsxj.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtlagpyxhp.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtldiikcfl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygxoiumg.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtxsmeoqfy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtjjcqkivt.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtpfsdptgb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtxryphnoh.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtfqgppsfl.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtalmdrisf.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtmpebqxto.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtaderdfss.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gticnnrkak.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtnakqjmry.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtvldlkbzv.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gthfjsswjx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtlhezxhnj.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gttafyaioo.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtdmlfjyxa.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtajchwknq.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtwztkmosb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtruwltnus.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtbobceoaz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtfxhqbezo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtpnszbwlc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtjhablyhw.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtzmkszrsm.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtrflvdahi.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtzydzndwb.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtcfxxkblb.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtymontaox.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtgjjgjzii.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gttcxcmxkj.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtntrzlzpx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtawzwmrwp.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gththknwjq.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtkoagfxpy.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtqrepiuvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtsydqisfc.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtaygwuvrs.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtfttdcbkt.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtzavgpudz.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtfxfagnth.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtodwgeyjv.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtgdyzradb.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtkjmmlkxy.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtenymwtxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtpaauqwuc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtvegdoxxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtrquqgnge.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgikmiszl.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtdmlyqbev.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtlimfcbsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gthmytetfy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcipuovlo.html


<!-- 参考信息 -->