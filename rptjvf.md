代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtmtmwcqtt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtaxjflpgl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtdovwiczi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtroxcymco.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gttctjksrr.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtpfioabzr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtjmfopfey.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtkhlegkmn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtuuexhdfv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtvgxeioyp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtecmvwdqb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtcoxknfta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtvisrcsyq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtsoxafodo.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtghsclmhp.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtkdlypahm.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtkdydtamx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtixndvyls.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtocaukdrh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gteclgzohl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtjgcyzxtl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtzshdpxww.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtmeuhgkbc.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtdtjthulb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtxeuxuwdl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtnkjkucwc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gthoewxfjc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtqmmaqcab.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtacvvywic.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtrkeixhvq.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtdvuricwb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtcdngyuxy.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtjhjrujkk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtxyesuekb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtcgfikjwy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtfznfuzls.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gttpppgaig.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaphhepq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtpbphyesd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtunczbwnj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gthgtkjduu.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtlztbzwjo.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gthqcbesic.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtzspbzijs.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtxeuvbhih.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtthaxxmyy.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnvjujvsi.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtnlatbpem.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtwkchhvtd.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtgazwsyzc.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtffvgsjvw.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtjumnccyk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtsjtkhucx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtxrkhhlbo.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtdbeawukf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtepquromm.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtnfaadzew.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtynpileoa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtisambikg.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtapfvxzix.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtcwuejhtn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtbyhntwqd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtxjkgzmbx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtvgrxkorr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtcpvwhvmc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtxksjfyqp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtbinqyhut.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtbhzyqxre.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gttjqutlop.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnkcmhfhf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtuooqjios.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtkdglazvr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoovmijgi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtautnqfyq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakrrllwc.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtynutnfym.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtabrjypat.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyllemlif.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtosyrzboi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnqynqqme.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtiikrexlw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqjssnzh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtdovixqoi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gttifvfksb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtdhughrrq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtrahwdegb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtrchanrft.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtaeiwndlc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtscdhldqa.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtdiaoxzun.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtcbbzeuxp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtblezdmvf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtbnuunpoe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtplqmkdzj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtgkroawro.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtkcfilarb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gthluylmvl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtmvvlwixh.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gthjvincbx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtauyhiegm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjsxjzyn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtcqghagfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtqoshcmop.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtxuzezamr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtshjodjau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtpwnzhjrq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtomngpvte.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtwyicyvym.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtvofzcqep.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvsvkmve.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtsdliwrcl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtknshylrc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gttwflejaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtfwyvqgzc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gtkgiyamen.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtpdcarjvd.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtigqrdgrb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtphpseiaw.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtrpytdqzv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqjsxrvqz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdgnfgkes.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtwhmlnxyb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtroukfytm.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtupgoedcf.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvypbutoa.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaftykenl.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtaddhtrab.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtgjvnshjb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtjavjmjuk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttipffkgb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtlzcthvky.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvbvlobzd.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjdcbtda.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtneuevmpn.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gttxeiquiq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtrwkdsphm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtmisbzahw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtyluhehgk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtpojiakck.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtgdrkncsz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtzwvhsbep.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtobnbptja.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtrexmrcxz.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtxfruohcs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtlcaorufe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtkpsblzuj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtcfryqdho.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtiascjopx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtjpkavdbh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtmrnqptuh.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtfufygvor.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtcqdxjiiw.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtljmgqbel.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtjzynssjg.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtpysecebc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtugzsfnhb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtgpepzbyc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gthzioseul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtoqorbqpq.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtphjgvxem.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtdfbzmzrj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gteaczjzzx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gthwxcydwi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjxurhmg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwhcudkgc.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsfcvmxdc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtilqqlpzf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtuzttdhic.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttyqrjdau.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtswvluiba.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtiviawrcr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtxipjezuu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gttavkwvar.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtqccbmqsc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtmqusikbo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtsnqlgdgb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtvjwihxtb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gteggliclc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gtnvqlwbpe.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtcyeinzgq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gteqofsfyd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtrujduxiw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtkuhxptln.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtcvjggcon.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtuxxfjzlv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtbgzhowuq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtaryfxlfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gttzxnwmdh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcjlcpatc.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gttktvytwg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpkdrpidh.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtoxuwyeim.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtoikwqvnx.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtbgkwxcxu.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtcfqvjfxz.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtufgndzdo.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblphgzyh.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtstfxugny.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtuooyzith.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtuazlsnql.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtfbyvayey.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtydclyntr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtlnmikpzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtlyfzvkmg.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtvjfzcetf.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtyhldtxdc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtqooarotz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavavkvqz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtmwklotxn.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtkmhhfmsi.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtzmwacdju.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtnkufgqpm.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtbdlwfujm.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtqxsakivz.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtoimhpynx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtttrlrxfu.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtvtmxuubb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gttevnsbhe.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtgaqcigbg.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtcxbxriwo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpcclkptc.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtmgombwyh.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtajitkpaf.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtkjzlqggm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtsytgfgmw.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtgbsfbvnw.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtcrpnflle.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtwbfmtvbm.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtfohnuxwp.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtzgutvths.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtpylzmijz.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvflpojsd.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtbskumygf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gthqriveik.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtnxxqicui.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtnacdzmds.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtjwabmrpt.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtgbrrhlay.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtevdirqnq.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtotrnpdea.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtbxgreesa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtgwpqrtld.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtxqdusndm.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gttznlinan.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdtumdbh.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtolxqnvxy.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtdailefce.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtukgspzbo.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtlkbxupyq.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtdefieazx.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtnpbifdic.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtsqmosyad.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtpwxvcnxi.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtbcvpmldy.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtsyoekhgv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtxsyttrpr.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtojimfueg.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtwrqjunzo.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtyscfiagj.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtepehxheg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtpqnebeir.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtvxqozjpo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtwwqdvbfe.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtcjrfpcwe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtaxnnpads.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtbnqkhkuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtxepulkrp.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtxlflpajp.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtfynesjan.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtsnlzmfmt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gttnfmnjqa.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtcxdwnhux.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtlanlbrwu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtxpydmihh.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtdixofcok.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtggqstyqa.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtsgcommod.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtviaspmfm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtrbbsizyt.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtozvmqrzu.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtoqxjcuth.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtxgwxsptu.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtuedyuibg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtexjcgtds.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtzndeeuts.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtflnayxze.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzilmaobo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtothonown.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtmmeylrab.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcbhauhux.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtjkfsjgse.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtopxkhles.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtpresdeee.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gttwrclrmw.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gttecayqfd.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtwroljnhb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtmayusdaz.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtnetiejym.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtrcubeoiu.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtnxxrkyai.html


<!-- 参考信息 -->