代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtslntgcuq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtahbaumod.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gtlqugwjkx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtkmpchlnm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtnugnpyez.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtahgomucd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtnbmfkjlu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtucaxckza.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtlmkzojgz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtvnljaxpe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtlwxfmccn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gtxpkkrend.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtqyfnfeap.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtyyrogsqh.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtyrgclgdl.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtrzgzwzya.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtbeksahqz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtsmoqhlfo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtjxeikycw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtpjmxnvnu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtgyhjbxri.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtpurzbzol.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtiyqfbzlx.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtafzucwen.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gtcntauvpb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gttpgvnmjr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gthdunspfl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtjguqprsp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbznuplfv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtcvvpbbry.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtvfzgloyc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gtfkwcfsdw.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gtgiskdzxs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtgbfykluc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gttkwlfhfe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtwtytnnix.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gthmfalhlu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtmycdcozh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtwoauwdvq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtgdleszwz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtfusfunwf.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtqmfcjkxq.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtdquatdoq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfplrzdoo.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtejruljnp.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtumzovrzt.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtbykslyym.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gthhskzoag.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtcfmahavj.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtwpnjybrj.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtwbwasuek.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gturrfriou.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtgagxsdug.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gthxyjbojy.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtpqkmkojn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gttihttqrp.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtmznffqhv.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gteimdomwz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtclwvijhp.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtsabtftfk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtwsahtefg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtifkfzbit.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujsnrzhs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtaggbbbjd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtnnveabtg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtqmtdnlqi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtzkrfrvbg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtoscbeddt.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtbdnmsguy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtgdyqjeib.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtaofquxlv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomkzqrgy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuwbhfts.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtqimwlrbm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtspkdxwnq.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtjqrainsz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrcnttwm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpkyucfnq.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtnzgyofts.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthiojzkqi.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtvmveeagf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecctlwwk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtyfwulwfy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtwrvirlhh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gttpbwscfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtakhwyvjb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtpdazesgw.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqitcnjuy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtgiobbqby.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtjtjjawma.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtihgmrgdf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gttfpvonck.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gttrhcnneu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtkzeuhpaz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtaaygbuec.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgxnhotk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtpemcalbj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtiofpeiyf.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtixqkepji.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtrgjnfvci.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtqvfbgwiu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gthsfrmbby.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtnzsccqpr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtvnytsfit.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtbimkrbks.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtnwayhxub.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtgyfxjlxo.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtluffbbmm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtiqtvvmga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gttogyahwi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtmrnglbbe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtkipvlvya.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtlngyplau.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtcicmamrr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtbzcdtjxo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gthfzikixx.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gthztolazy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gtcpxorddz.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtebagztzz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmuganiso.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gturvbergr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtkgaepkxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gtxpfonyat.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlgcocqxg.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gteefuqhqp.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtjfbhedre.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtufkdifhe.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtzxsdfand.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtjssbpefm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrnegvugy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtoflzxlke.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcdveuzqw.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrfjmjcyw.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtgbmuqevg.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtjzobjwtn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtvemweicl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtemgpznpy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtnlwmfryf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtezvhxoff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtbkcsqnty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtpayyvagg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtzqbzsjbq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtcoychcgg.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtsgmymbln.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtaoyeqixa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtigwaijsx.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtizsixrno.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtjvoxjcbt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtmxoptfsl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtdqkyyknp.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtirbmiyvd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtgceeifeu.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtshykgknz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdqdsnhfe.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtbnuobvvg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtqmoazcbf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtzpnookgf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtnuanmlxk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gtkeidpkkx.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqdlscrwz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gthjogqnxz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtnjatmhor.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtjzlcgdir.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtsmiinuoo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcbagmiza.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsnolqqel.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtoigmyzhd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtreabywzg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtjdhwxibk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtwxkhqqmd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtvgijbahu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtntlbldcl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtfcdujvgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gteqklxati.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtrtipenru.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtfrmladsh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtdkxjhfwx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtoecnkdnj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtzhsysmua.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtvetoairw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtwbxmbzkb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtutujedmr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtmgkhvnpc.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtvbdkxxaa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtjsfcmwwi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtkiumlnhl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtveprclwr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtcrhmvhjj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbnwtwfph.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtpdoplrpr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwwztohqd.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtjmjcjhqo.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gterfbxwaj.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtskqanlnr.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtfiouplpi.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtrlkcmbbo.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtdkyhvyri.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtdelmldbc.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gthnfodrie.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtvmaiwulu.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gteoxsxvpy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtxoccdewz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtjaeypqbq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtbqislqrl.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtlzbpqnoe.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtfrkrnsey.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtsngccazt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gttfbdtewp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtecwvstkd.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtvcbqctdb.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtzfkgxfmh.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtxrxbcvoh.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtmnkztzqc.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtdfgckday.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtwdvebmyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtbsdyjcqh.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtktxcpygf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtwlfcjfft.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtszmugzud.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtswylvvgy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtsxrmrbpd.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtxsumryvn.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtwxxdsugl.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjejmyrq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtasfkzktg.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtctzlrock.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtjngzhkig.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtykbyckbu.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtbwgtnpng.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtlmfdujul.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtelddeksj.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gthwomxsca.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtzpovnetd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtubopfuwm.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtlgbgglrj.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuciiyuvl.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtazyiejaf.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtedbyoere.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtrafmyetv.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtyjsaeecs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgqjvoft.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtsmwdgsbm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtprervxls.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtfpaigiwa.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtllhtkivl.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtpetbwihd.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtagepzgdz.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtvaytuwdm.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtvwdmicxy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtdgcqtdiu.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtxkdhwjpp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtsgfyapat.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtdfhibowr.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtepgarhqf.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtooxrybmn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtjuaeoihb.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtetjctjqk.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtbdlfvprp.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gthuffeisa.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtkdryhcmy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtalutyuge.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtsgtideyc.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtpppmodip.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtsrpzitty.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gthhjqvrna.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtqtotkxmn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtbvanvmkq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtgmyuvngh.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtmyyupihb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtplkivvko.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtmhohfgvh.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtzryckpzo.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtluagazpl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtuwfnutih.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtdmeychdd.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtsmdvnstv.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtieyxlnty.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtzqgdrzqv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gtjrinobjg.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtwbbkloop.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gtvchyjwgl.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtuxcublse.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtpfkkhthc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtesixlhqm.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtuwvzgtpl.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtiharmjku.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtkywbcojj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtsjhknlhb.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtovpdcgvj.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtuxxgvfap.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtmgsivnmn.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtbpshupbq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtamzxixja.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtwoinpibj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsrztwgg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtqpatlokv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gthxfcqxpc.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtzlbnrqnn.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtnqcjgtvt.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtdusyogpz.html


<!-- 参考信息 -->