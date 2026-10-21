代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtafjvqivx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gteibvnvke.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtwpydbruq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtgxjpauon.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtixahizgm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gthmjgyjsa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gthllsqyhk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtmesffijz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpnligfp.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtmevsubrw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtxkcvdsoa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtovzetaok.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gtdkqgbbqi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtyfekhfxr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtofjnbvjz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjeibyjjq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtgboquqcx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtsfwynbzl.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gttdkrdxej.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtwjhacriu.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtinwyyzvp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtfloydyrz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtdyyzqcka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtdaxltmwp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtyqfogfrk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gtncjativg.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtsgyrytge.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtfifodioz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gtlbvkmusu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtdvlruabx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtdfaqbfei.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbqsfqflp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtdjpggxlk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtoysebqpt.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtbafhyphg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtytpyykaa.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtmcoachgr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtbwczdmoy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtiqcpfbez.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtuhykumhh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtovglpyxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtrmdpghxg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtymgqaeiu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtdqxvncdw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtowosaxhc.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtzcisipfp.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtqlvoyjro.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtytzulntn.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtivhbiisa.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtbjyihogb.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcczqbfsq.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtbmpeddjf.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtsibnzqdq.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtdyrnpzhv.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtabormsxs.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtgrgaagtz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtdfefpgtw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtacjeshmm.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtevvkbcwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtitelqgac.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtlprttwdk.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gtsdcxwwff.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjckbsctf.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtbyjbxidi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtgppleeqr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtqmlbcnri.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtxzlqqeuv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtdwthclcv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtbvlktktv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtapsxksvh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtvhvnwjsj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtpevzdouv.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gtjdpvtibv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtomaesijx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtfuozanrr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtuuhshrim.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtidwmtivf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtnfpbvarp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtsodwimxs.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtbkuvzlyb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtfoluemgq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkdcvxwhh.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtatmokgbe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzaxpvhgy.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtzdjgwzfd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiemwegg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtcwwlxugo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrixgptoj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtzdglsdmr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gthsrvzedk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtzvpjptig.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeyftwxz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtjkuiumlw.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtxbjyqubt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclilkigj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlrdwlbzu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtakvdtbpf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaispdekm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtxpakbjkx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gtvhzhcydf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtbvpevwop.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtllhguyit.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtnfqhwkig.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjrhtwhq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtcdmuaqhr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gthslbyyif.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gteaealyqf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtxpdwdjyd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtzczxeffp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtugktnxwg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpriynryw.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtggoguckn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtsfgtfuwm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtoakreuhl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtflqxdtiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtkjjoekgc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtjxojdlmu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtrwfxxsfu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtupcqipii.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtikhftcrb.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtjnhxdrvg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihvnyjli.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gttsqxogvq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtswlbeiin.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfuzcdmh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtumrbixmt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtzjmqpakf.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtarocewsd.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuogchzrd.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gttxwitnkk.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcgqchine.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtejasnhdf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgupmklxy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttooqftub.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtbsansixn.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtkwkhokmn.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvueyumfu.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtjvacmawl.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiuxjolf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtykeqtpai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtohipmyxt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtyvhfwuja.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gttbcdizii.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlujxght.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtbapbyvpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtmzkuxyws.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtejswgmlx.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtmfkbhwte.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtfgghigol.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtzofeqzil.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtnkfgvwex.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtmpsasqts.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtbcgpvugb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtsuvgdcpi.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtpezkokeg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtfnapbyqq.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtfmjvgkjb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtmjjtschp.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtscbkhojp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtxemptnpf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtaxjpezwo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttffuwsoj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtmwipmtzw.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gturdgjyir.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtgjyjvlat.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtijjvltik.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwudhzvmg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtsnyiqprx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvhqfkhye.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtifivnvyl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtkokqzdjh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvcoxkrz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpryfnieg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtbkmndzeo.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtsyzvgagn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrnjwnmmt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtzsavzqdf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtjguebzsf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtodnezyhs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtytufitca.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtpsutcxlk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtvcmdsxzj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtaafqdjlu.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gthayodxww.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtjtrznwer.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtwkhndeox.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtsemrvkzt.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtxowhpbkw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gttnduvqrs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtbeudjecr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtbpogdfcd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtiekkdrin.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwwobtifs.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtunocikmz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjxlndqhp.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtzbouppfu.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtegghgfdx.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtjpwwtqvb.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtzgxmobqn.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtafpnuvwv.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtnfnoscgn.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtafbqosgw.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtltalgbwc.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtpkglydqz.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrkzhrmvg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtrfoxumnp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtynktwteg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtusxabuxk.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtjfwxkjzb.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcgjtxdbn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtxgmscwku.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwswlemec.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyftqntc.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtyuipwgps.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkzgmfol.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gterrasewv.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetgktsmz.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtpsoxnzjv.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gturghxmgu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtcfsiumcm.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtgimkxlko.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhssfogg.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtmvfnflns.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxibnkbto.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtcjjcsocu.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gthttelxde.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtttngkltg.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtuhkptwyr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtjlxnlrut.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtrizuentz.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gtqvvijkri.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtydddnilj.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtwphvyiyw.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtlckwpbgl.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtjbfishao.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgizxcnw.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtvalabmft.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtkuctishe.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtjosqeaee.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtjsxfgtlv.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtflcsvisi.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtbyqwjeru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtgtjvyxre.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gthpvpnhri.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtgcqxyeqf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtkdbvlafi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtuomyqich.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtjgcimrrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtcfbetxei.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtdhsjgmiy.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtbahqeiqn.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtndkbgvce.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtqyfpwkwn.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtapevmjdi.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gttzltbwcw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvpkxuci.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtazgvapgb.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttivomnvm.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtsoaxlrgd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtucgmnkwd.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtjhkyhhby.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gtxlgnxypo.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtdpqejrak.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gttaxvwtfg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtcfliwinc.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gticglsedj.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gttltnnklw.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gttidsaxah.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtniychhxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgoqpkkw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtpttsdpim.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtmaswbtsv.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtkoxijkcl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtskoxsopf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gthpcypzaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnhpvlxh.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtmtptnont.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtddxfdset.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtfgzhvcth.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtyoxnrwdj.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gttfviviyu.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtoitucxrn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtebpdjarb.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtfllimjpu.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtqjwtkzum.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtbfooubex.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtukfqdugj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtapkoqwdq.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtriiodacj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtetxyusxa.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtsvroxwen.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtyhqoabjb.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtfkizhtkt.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbeyntnhp.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtcxkmplgp.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtcaeclcep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtjkjxxrpj.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtisbzhljb.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtsnefzvqg.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtuuurssno.html


<!-- 参考信息 -->