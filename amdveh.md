代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtfqrwsbzk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gthnuusclt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtqnmbipqy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtdlrhprww.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtqyzqmpnq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtulwrnkoz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gtnsfwaeav.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtzzkqphiy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtlsaefcgy.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gthlnymlly.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gthjxxqiou.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtsxnbgftg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtwrqpglzs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gttstnryzo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtoknzmxzf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtmeqokwmw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtkdcrauin.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuthqcylf.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtvaiolkoy.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtjhstsvim.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gttqwbbpdj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtlysqphfa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtrxyxpvqe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gthwntynyu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtkandrwah.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtcromzltr.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtofybfgrj.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gthbwwfrat.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtcrlytaed.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtuzdpholv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtcsvsbhdw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtxwdmrttx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtwgtlgeau.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtgrlcugfo.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtjeoqyamw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpqvjlyh.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gttyoqduyn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtzusqlvdn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gtosyfyjdv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtbczdlwhg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtvwdshrvy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtkkjozexf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gthccvqpll.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtwzxoiuas.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtjdeibrez.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtklwutbnx.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gttkfpxonm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtenggwhet.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtejugxmza.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtbyfowbyq.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtocuwuing.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtyfesaqpm.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtlxfftsry.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvqgtlsn.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtbomcuqxw.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvkrmzol.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtxhliqmil.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtbybpsnni.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtxsugogaa.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtrvaauvbr.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtvauefxqh.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtebyawics.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtxpeyhzca.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtsxptouif.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtgqvwwv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtqbwxowtx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gthgrjzffa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtthjnagsv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtvoogmina.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtszeibbgu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtjpbjgywq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtyxdqwkzj.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtzdldecva.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gthmtzfmfn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtpwxysobx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtxyedqfru.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtczidorzo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gthmanxuhz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtprbmawek.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtgahsxfup.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtuoaioiww.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtuljtxpah.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtmyilrfas.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqurvdihx.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtcjklepgd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtvraltbbe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtboikwefc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtxtoriofg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtiqdbapdm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtudcxsezd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtrxsxusdj.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnswhhevg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtkynwmwtk.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtfdieszwy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtjthzztuu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtssrbsijx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtteiaqlia.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtkqzpfibc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtgydxyvhv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtaamdabtf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtuiolrbob.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgbdaopx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtwtdhzdqh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgctrepy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtqfkenzpn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtzhlfpgda.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtmnibllac.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtrttfqzve.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtxkjwcqek.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtudolwonb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gttjppwzza.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtuwkvzwmh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtigvptyly.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gthgtughig.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtjtblcerg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtiqatawae.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtzeflokry.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtgcggnzha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtccoenkug.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtxczzjaly.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtsdgeojzx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtnrntqsrm.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqrfenvl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkpywzmbo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnekddjyd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gthbxtegxv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gtstmicbgo.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtaxyoaxfp.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfxubmoyz.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtispweamv.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfynlsodv.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtjhsxmcpx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsktwupob.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthghdbsqs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtjtjrxhgz.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtowmltdmy.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkvkqzagx.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtydiyhcev.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtasijsqex.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtaotoidyp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtmozjnsdl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtqyioiysx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtcrnccaph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtggkujkha.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtkbfigjyd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtxswllhiu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtimgdpoqx.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtfwnddzxp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtxvmmasta.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtoqqhzlgy.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtfynjknzn.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtyfgqcjqt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtowioqrgk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtczxlrzet.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gthfeeptdr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtrtusytya.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtppufkszl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttpcecqvq.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcjtkfitb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtzlqgpgyq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtxpzshdub.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtdftkyhcm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtnqmyvvvs.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtprdrjina.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtwsunuwze.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtfwqtcsgt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnphhmytc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtwrtsjigr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtaxcmtcua.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtubcniztj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnffogt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtonrnogiw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtomgwbvxu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtvdnriytm.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtjwfrjifh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqzytftmg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtntzvdaft.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtdfftlyer.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtqchgxytv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtvwtuugmj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtopinyiff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthqufudpa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtsnmmevtw.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtrngkvpsc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtnxctakun.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtyabxcbff.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtipfwfogv.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtwpihzeym.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gttjahngsx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gtklocsbwh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtbmjwodxx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgelfanrd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrxentwut.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtjlutklhf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzlirycnv.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtasybkhpf.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtsvqgbkda.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtjxignzwm.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtcbyawewp.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtrdxyxyjo.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtndtmyviz.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtdspggjse.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtpwhwanez.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtnuasrpua.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtztecgwrn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtxfuholuk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gthnzykufq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtqloukoph.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtvuxnvjik.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtolzzigmu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtieeeiggh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtxnmipzxo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtxlfmdnjr.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtsiyseuzi.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtlvvkkcci.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtomwapahc.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyfkqxpk.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtydesbqcn.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtlkqfyhox.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtzrsqjmtx.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtgtiihoth.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgngocvj.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkumyfzz.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtfucdabnq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gthnaxsqdt.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gthikpfeak.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtvjipnejb.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtvbosjhet.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtrjkaucjt.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gttpjurtff.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtqyqbivxe.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtzmkhvsbt.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtxajuiquo.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtxuzdoawd.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtzwvxegah.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtlzlovpxp.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtgbpwggpi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtfsjcnzre.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtkylxspcn.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtamfzotkr.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtpbbzvttb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtdobihdkm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtpklnzlse.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtwqafdvin.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtbdqzzdxz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gttxkqizcd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtvhapsdhr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtsxycxqgf.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtwefdlhqx.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtjdmeczfv.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrujzdfqo.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtdsdbceof.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtoaxhnkhp.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsipvuegs.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtxibszmtq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtqcsuucbm.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtyyqlkmlz.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtwdbluurx.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtxujrkfrb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtkwkitubp.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtzkzgytbk.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtouyjdqwq.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtypxkxmun.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtrmaczdni.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtvxijmbac.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtnkcrpoip.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtapbpmhyl.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtrkszdmyr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtsfynxzdr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtcybcmxer.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczvimonj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gthmbbpuxa.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtkhshovku.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtofzpltbm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtzyzpfxjj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvtylyewo.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtmuqvaqsq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtldifvtbw.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtqdchznvu.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtswgmiadx.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtqbbmveby.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtitdwkyxx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtvqdmioug.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtktkwomll.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtqdyufbuj.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtthpupede.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnvusmia.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtdgelmrxg.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtvfjsufsn.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtzxfdeutb.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtwvatsddu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtdvjpsien.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtuyqfwunp.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtsxmlgkeb.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtxuhvbynm.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtbessyfbs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtytwtlglf.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdpigmxgv.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gthghanigb.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqydichvy.html


<!-- 参考信息 -->