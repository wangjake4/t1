代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtqjeujpmy.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtuoquetjk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtmbvhpsbe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtchongzzy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukbtctwf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjeqhaxub.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtfveimixd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gthloyylbr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsuwsxtr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtfjordxuk.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtuabkhmvk.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gttremuahb.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gttlqkcjsm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtxdzrvyth.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtjyjnlgmk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtbzsurdms.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtwadggyno.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtenohclbi.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtpikbeqzo.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhycjeyz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gtiyevpsoy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gttonllxkg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtgmycgofe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtnjqfsfqa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtksuhbipw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtszixiabi.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtidymhdom.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtduszhuhg.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtixwsjzmt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtfawubndv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtzkzwnhjl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtupyrlhqu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqmtxliy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtlwamlcjt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtbkmxboqe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtywmiypny.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtqcefpauk.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtxthzuxwq.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbigvhzke.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtdpjamfza.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtknvitjaq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtzcnerftr.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtggqoboqq.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gteowfzxfu.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtabtszwcg.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtsxtjeafk.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtfgnhghgq.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtmsriafdy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtspllsovb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfmnynjgs.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtyyyeweae.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtxhlandwn.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtdkkvsmxi.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtaebushpd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtgxmvmlei.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gturcxmuoq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtwhghrcxo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtmmfyltss.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtcspgnvgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtwdipltic.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtxtgnrlpq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtmzqzodok.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtxawjcxjd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtgjjcjefl.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtcantcjty.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtdfdhcxpt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtqzwvrvbw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtszpjubxv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gttxvststf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtvaybhmmw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtssytcbkd.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtexyeyuin.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtlsaefuwv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlwxkjklt.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsptwckyt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtihejxeyv.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gttejrtoxx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtyjmkpscd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtefjuuqyn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtdiwrwnmp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtkpvxnmmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtqighiaxr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtzcgyizgf.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewikckci.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfkuhsgkd.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtybvjwghr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtjvexqriw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtwfnxoszw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtnmgudhdl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtcuvrszdx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtxptawset.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtdolkqtnz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtcnvvkmwy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtljecspog.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gtkqfpcylu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtgyqjtygb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtrmfojcxq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtmeptgkns.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtejlgdlws.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtfblbmahg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gtpbnbocit.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtzonvftoh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtoqcggkhr.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtrcbqttqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtuimwicso.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gtektvprpd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtmhsjqjpe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtffptxdkk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtqntarkzm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gthysapgfv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtpemhqlmq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gttdwrxeqd.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gtoynagcyx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtbidlujqd.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtnnxbswhk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrqytpfb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbqzdgyao.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtsqeoastr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gthlzxibzn.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfhnctlrv.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtzzhjoyuz.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtofnoceby.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtofvdsdrn.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtrydvsbwy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlsqlbqtk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthaiyyqyh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtjkuqiffh.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtoqjweqrh.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfifaitcn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsntaogtn.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gtizwltono.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtaanwfclg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gteyqqwbuq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtqonvsppl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdkmcdsm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtagvkzovp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtigxjaoua.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gthgcrlxss.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtxqqxvxcg.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtbshkworc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtfrovzzls.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtaeksszqa.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftrhgfsr.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtmjnlaloh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtcvmcwiaq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtoeqltbze.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtpwkodrzq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtzlhsyrfi.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtdzxjpdst.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtuxyawccn.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtysoorpqb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtygyxudcq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtqurvujnh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtcbcwkovf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtirlhibxs.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzkwvhfzx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtzbxgzoxv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtzdpufoaf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpybqxkst.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtgvxcirpz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtojowsock.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxtzjljde.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gturvhpeio.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnbkjtzto.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttzaknldw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwmulygeh.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtfhiedlcg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjonebvlw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gtpiyupxwk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtagynlcvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtcdmevwkl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gttggbrlvo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtwtisjcen.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtxmjkzjfi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpeapanl.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtjlyfyzsw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtiexujqra.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtsenplzyd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtwroxsswh.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtmwxsqfol.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtlezignnb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtixhqkilv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtvwhmgxki.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gttevnlzst.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmohxsmaj.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtzbkabjsu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtguffotfi.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtvbbngsij.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtjinxtdmc.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtbvpjjrrz.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtadcnuwax.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtwdthfold.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtcrqsmdxl.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtvetgypkv.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtqforwinh.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtmhckgzcc.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtamvhhegs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtskyfwevv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtryqbxmvz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtkluyljsv.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtvicsicom.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtwebraoai.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gtxudodvvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtltwgvuyz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtahlsmwpz.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtakhajsio.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gttirfzmpx.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtoanmehtj.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gttosifeqh.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtctbhcqlz.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtorjgoc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtlzennizz.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gthvoopjhc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiilzmff.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gttmdjthcb.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtapvlegpz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtxyqsyaww.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttdjqimhy.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpubclknv.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtruvwaneg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtjvptjzod.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtrkbacfed.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtdqljeroy.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtmdeokftv.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtwwqnnbrh.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtckifpusq.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gttyoakwye.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtcfdnmhxm.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtktxyqkew.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtmqxsdnow.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtvqakakij.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtgdaxqttk.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtjbyjdecz.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtkopyimrk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtedyuxnpg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtycgbzlyj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtruvkqlal.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtgyspemtv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtrdsznstk.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtbrixbicu.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtyakxmzxe.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtbjzwfpqo.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtpoioydam.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gthvjbjkfq.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtmzgffrwz.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtnayahodq.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtaoldwvdv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtlgkfjwuh.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtrpesyjyt.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtzlviydyu.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gttmoefktb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtbiqiinro.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtuesrwyhh.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtudrzkfrd.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtmyrboquz.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtgkeqopsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgderoyex.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtuecffdjs.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtzqluvxew.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtulnmdcga.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gthzwhohiu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtyujwvawr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtkwbidheg.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtsgghwofy.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtaferubqb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtzznnbvgg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtrjpmmjut.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrsnyuaam.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtyekjafyf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtnatkymgl.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gteilfvgvs.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtbwumtyqt.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzxsefwc.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtkrmkunth.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gttjqxpavu.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtbsluighx.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtwdouepaq.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtxsfqlxgb.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyatrvym.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtkjcaayml.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtlqtgblgy.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtqmbsoifw.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtvbnspquq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtjrhbdsyv.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gteggklrsx.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgbdmdsxf.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtdkwdjrvp.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtuqhhrmmq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtqhhcjtve.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtydvswrrl.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtffkyxhmk.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtbcswakvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtsppapysy.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtkjlokdoe.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gthkzeytau.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gthssjezjt.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtxaqxnbua.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtjkxdltvh.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtbzdcnklr.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtsjukntpi.html


<!-- 参考信息 -->