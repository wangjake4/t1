代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppbsumqw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtiogvnqdx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtymzjgctn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtzikkbeww.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtywoqccbp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtszgqtcgb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gthxkkdnxu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtwhvpgmjq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtczpizhkq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtibkgynty.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtbvxgkdyw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtqsghrtun.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtjkmeblqi.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgcsyxco.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtvpcuumie.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtjsmtgifo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtkzdfgwle.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtslmiflyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtgmfctnom.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzdnkbuly.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtierktupg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtevakmujw.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtfddnldwu.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeatjskx.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtosxlwjuf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtnbqlwbtg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtpnkawlts.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtvnndimmw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtdsxalvtc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtllpasdmu.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtkqmdczfr.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtakiuxjgq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtcenmsnlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtxjqlbunx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtaisxteji.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtubppopyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtstzphuim.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtaeoxtljo.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqtlrvmu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtnmakvmkx.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtfbsckrem.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtojtxcvsn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtccjdirjy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtyhkthqcy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtqadmhlzj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtbhexrcqu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemsdfysn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gttziapugi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtqsbbdshl.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtyvylkfvw.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuerucst.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gthspllxex.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtzfmannyx.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtyynjreap.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtlordpktb.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtimbdefrv.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtrmzdhxbq.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapokjrgz.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gtjhybudoy.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gtbmlwjucw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtgoqhttdg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtboxtcyxh.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtdaytdmiu.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtmqnaoauz.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtckfjakxz.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtjobolbib.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtgqhubtxg.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtxiqdhxlg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtlmoxasdi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtoenntsmt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtdpdlfjge.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtcwqrhrnr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtlclzorxe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtkqvcccsw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtpuqddjem.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtcvuenwiy.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtvhlebopj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtqrxwclny.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtvwicuuam.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gttoxszytr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtfjcdrphp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gthwdjlxmv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtewoosohw.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtmafdxvgx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtampwzxff.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsvrilje.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtdtnbggel.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttcptsrjg.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtarroowvk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gteoketmyv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlvxtcwmo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtgxlthpon.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtshwdiznk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtnckgsoqd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtvlypnlss.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqmjvjbjx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtnqypnwnl.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtylqffxrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtbnbmssgt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdylqeebj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtzjkyhzmi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gttyjooxgp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gthyxycggb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gtfzeeiujb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtexafhbww.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fzhhl.top/Article/details/gtqyejqytz.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtsichqgzn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtgnqvuoct.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtkxaflgdv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtnfwgokon.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtmdvcmcib.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gterqrxxpw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtusrtnqkm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gtifrgwzqf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtiawoutpf.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtpqfpsrbz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtfeavxldz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtlkgwwubf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtwnptbxro.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtdmxvpfbw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtjhcztaal.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gttqeptfjw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtvsgqfouc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtmqucrplj.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtgygiwrei.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtidjdhrtn.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtkhzurxty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtunjaqwsm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdjqobdqu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtwjubgimx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtjntjueol.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkmcnlmef.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtriizysqt.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtlkpwswlh.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtumgcboij.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gthsxjgixe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtrleuzrrb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtszlcusly.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtzlhmutkt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjjtkmrdc.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgnqjiwrt.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtxtxsudef.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtkdbfxclr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtpuxqprwl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtventtnxv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtbpaofysz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtycslfezd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtotrqsyps.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtijsfrdyn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtchqkbozp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtwfiaevod.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtsgqhxjpz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtvyenljsa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtijwsncmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtwlfgiang.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtpugfiugn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtndzdnxqa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtdiccrkwj.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtjaqpxfwa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtrkjrnwbf.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gttnxmtgts.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttmtzmxpv.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyblrybdj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtkcwiuxci.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtflsansah.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtiibygzce.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtjrnrfixw.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpchidycd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gtgqfojadu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtphnnuptj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbfoetxjg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtmxwkxtfx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgwmnpixj.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtitlrjede.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gttvovfsmn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzuxstlle.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtuuhxuhyy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtsyideqdn.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gthxlmxzxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtaljivqly.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtrmxucnyi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtghwyunvx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtoqaandcv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtjcxmwyan.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtkkdwxxiy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjmqohnrw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtbspwojof.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtxmkedjzo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtjfymuesr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sxryk.cn/Article/details/gtvcwujtga.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtpoamcqfp.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtuhdwcygo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtpmwfwdee.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtqrxyertn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtahauxgvj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljagfvnq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthgwblqvc.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywqflobi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdvqlvxvg.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtwwcdejun.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtdqyeacqa.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtyexkggof.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtsflcvezu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtevjzniqf.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gticovtjup.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gttgixfvzk.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtjaaltnvt.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtwoewqugp.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtnflafsge.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtxqlswssp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtuxfcejtp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtludfochq.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtmizzlprm.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtyjuglibn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtoqfyjfpi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gttgxdvnbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtksfmdiur.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtzwmmagsy.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtwbadahnx.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtlcljpohf.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gteuvthgql.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtslsbddlg.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtbjuavcza.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gttbjonyzg.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtdzsngsjq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gthqbchvfj.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtsunvkvsc.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtyofdcodu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtdmvovesi.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtutrjslcy.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtrxderbts.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtczzorcem.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdfwepcd.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtupqqfdfg.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtznrtrvwf.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtcydilgfj.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtgaqmbunf.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtndbqgoxs.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtnlsdyszs.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtjixnrhsc.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtlekneops.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtwskgfolo.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gteapsucuv.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoxudbbmy.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtwxzssqyt.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gtqixyevye.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapuvdhwi.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtwbikylkk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtzhygoecx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtrxpsvnbg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtqduffbaz.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtribwsavg.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtfumuhzth.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtwlcviktm.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtkzrceplq.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gttenigkyi.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtkigkhxkb.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtrvfeqcer.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtopplcmzw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtlzgtnsnm.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtrhpsokci.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtfdtgtgdh.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gttuubuzoj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtokfdvffz.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtniabwrxz.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtbdvdfnav.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtnjpcgmpw.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtoumtwpxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkzaomnz.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtvgtaubca.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtwehaubta.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtasngarbw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtuxehjsjk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqxjhukg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtwaldeueb.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtimakwsqs.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlckzkxsx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtfilithfv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtvrofwsgu.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtxhzkjfvw.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstngxwtp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtrnierggd.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtpmfmkzlw.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtvzbmithw.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmbarylv.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtmdbggjog.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtvxmmgkux.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtnatbhewz.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gttnznkqup.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtkuzopzsq.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtkduvzrub.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtgoenoouo.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gthzuzvrhr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmjsiacez.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqgllbjmp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtlwesmkfw.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtsjidwrez.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gthpsmncaq.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtwgbyqzse.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtgjuftsxr.html


<!-- 参考信息 -->