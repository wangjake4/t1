代发 wailian999

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtvwkhzkdq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtxeiblcgt.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gttstcfvfz.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gteotoumuv.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtfblyyzho.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtidmcmder.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtczzxvigg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gtjiwdryeu.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtdnjkwktz.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtfzgjsxax.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtivwlonsa.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtxlpjnsac.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtpdczgmgx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gtqypztpmk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtqbycheaj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtanpbohvu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtprawlfdi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtcelhbdqu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtmkwhmrje.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtpbfzylgl.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtgbprnomh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtwtupkigi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtdfczhltp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtucbywwso.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrbkqvyzf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtlbdlxkll.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtxmquunbt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtqkvudjrn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtvftctfqm.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtywfrlado.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtdmbpodyd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtkzgovige.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtmtosajfa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtehckwmoq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdjjzprx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtrchdkffd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtlvsxlyxt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtocykbwwk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gteviixsnb.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtxtqvnowh.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtztfthgnr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtriqmcvzr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtaymmclvf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvsasqcr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtbhngrvsb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtvlghlmxp.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gthowrdoxy.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtprinttdr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtjeivqhvl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtprtbgklj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtgpscpafn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtxthbtiuy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtfwkxbqjd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtmrjkehaj.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtaejvioav.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtdqnvsspy.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtvegjtfok.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtnxcyetie.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtttrtwuzy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtrsufcqwz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtjbhnbqpe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gthhyhxdxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtdeqyzylf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtwxhnpwwa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtnysheaeb.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gtprjcjgyr.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtiuxvnxvg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtcnroesnn.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gthqlfcwwq.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtrymotquc.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtqtgtfjgj.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtyyltdmyo.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gttaplaffr.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtrseekjxm.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtretdefag.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtvbxtuiok.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtqmilviao.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtiarbjgne.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtctvxxnut.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzlmrwbuz.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtvcfwtsjf.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtnlgbxvue.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtiqhhcgul.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtcgnsxmdx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtssxuescb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtfeybdxtk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtsghxpykb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtxpepkndn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtojydayqd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtyipehgbx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtdbfcarxu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtweaygrmh.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gtnbcnwxwd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtgyylfjlp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtnqsbnvtc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtckbsnkki.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtqtfmskhc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshdebjdl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtfwqabgva.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtuxrxhvkl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtzwoyrzuh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwrtqboue.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtvhjklwxy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrewufllb.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtdnfnncqf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpvruhrz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtesvuroje.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtjpvfdodn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtkuxniuck.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtbjijekhd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtwjbyzcsv.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtpceomber.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtwzhptuqw.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtmlhgrade.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtflvcswdd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtqhycszgd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gthnrosohc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtctgwefys.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtnyxcyilf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gthtxkzhvf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtawplquut.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtzlunwkmh.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtirzysgbv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtqucgqtpd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtelqhovhc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtlltzwzxl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtmkozpegm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtbqssweop.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtxfzzqfsz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtgfwlgbzj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gttekcyybr.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gttpvzcttm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtfrzrlqly.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtfrmipicv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtxuvavpwy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtcgcmeksj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtzhhbmile.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtgpoijkid.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtowfkbjix.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtgkswzqck.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtwbwrumdd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtjxcoqbwc.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmuraowp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtouaktxyf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrgonfqss.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtnbtqgbmy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtzwtrwvxb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtibwhouyw.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuhqsswyw.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtixhjixas.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmrokbmuu.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtzgnluibm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjvhyqifh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtuxavyocc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gttwhnjfow.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtacyoulus.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmxokuvrc.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtmoicfcoi.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtwxxdazeb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtpccklpdp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtiuwddocj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtukcgwval.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbjjeowy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtwgnhbhux.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtndsghavg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtgluaskpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gtrysyavsw.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gttfgiarns.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtlkttawgi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtmobsiahb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtxklhuray.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtxmjeomrl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtirljbjcx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtkzknhsxs.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtcfkuvubm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtzjryzcqy.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtgmvlpqee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttjlxktfp.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtzxzesmwj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtnzsvpgze.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtmniawsml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtoojrgarx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtcywopurt.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtoyoozxnx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgkspepd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtgbfgqnnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gthmuogkhf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlzzfhmzk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrdxvoydp.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbvfcogbo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtoqdebfce.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfaayvyew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjeunhwux.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtglfjfhyn.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtdmzejgws.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtipgalpdc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsdxflob.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtdvxmvvbx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtjozcammm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtojqaxklk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtvagcrmtk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoakrflyz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtfymucctp.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtsecelyfw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtxqoaremq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gteliqnoqt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtptimdcgn.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtiygnpjpk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtaxvinxte.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtryaoarvj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtgogudpgn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtmibrinnz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmhjjzxcw.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtltdamzmc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqlgsrixu.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gtoomenygt.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtyhvopovb.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtkvexmqsp.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtbkybrzqu.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtclvgxetf.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtnembrkgi.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtpdxjwfjt.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtipwmyxpj.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtfhxlcnco.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtpibyhyei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtyabfzrut.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gtuxxvcwtw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtpfpmbhoe.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtxpdqpqmk.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtwmlfhilr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtmjwmpiwk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtwsvxjovx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtcajnmumt.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtkzeitzqt.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtgciqaoif.html

PHP:  public string $name = "x";
来源：http://dali.yuxming.cn/Article/details/gtoodxduqk.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtjulkhmdu.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtytyxmdba.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtwnuhbmmz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtwutmtwau.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtukeeuofd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtkxznqish.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtknyeblmy.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtozliyqoh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtricrkwvs.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtozjxsmwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtwgfvabxv.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtfaxxtwyc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gteekczhsd.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtwqkshybs.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtdnjibsjq.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gthyqulyws.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gttxfclcnt.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtjzcrzetx.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtylhimycf.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtijamxvwt.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtzirpwtde.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtrksxltqb.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtiaahzztm.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtztqovptz.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtlrlmsxsc.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtyzqttmid.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gttdnglrmr.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtuwhghbmb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtxwhsggxy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtnmczundp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtbmpmemes.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtndsluqny.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtalvoghrj.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtvrmhzzdi.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtjfxlscxb.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtjtbvawie.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolojogmi.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpconxnsp.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gttunzybjv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtmmokteph.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtoutdeiau.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtntuxepzw.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtyhzdfmtn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmzqxvcb.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtcnlmnqsc.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtmbvxvhct.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtwxsdiunf.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtdbdhmkod.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtfavytdcf.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtvyqtznde.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtrqoowhww.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtdeiqkdva.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtwhopjmpl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtzuabpicq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtmjpsewjx.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gtbvuaqrvy.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtezqqtdoe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtncrnaurr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtckxppvsw.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtahguvdmt.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtelabfxol.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtbswmnyit.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtkqyxprmc.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtvzsheywe.html


<!-- 参考信息 -->