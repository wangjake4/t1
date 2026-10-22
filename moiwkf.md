代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbiryjiz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2kylheufr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iypevyer.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gt2ilmzcijg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gt2eqfvmsaz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2kmofthkk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gt2kyewrdnp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gt2iujbydiz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gt2aiecdljz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ugaqafoj.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2tuidzkqf.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zceuoors.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2itnpbxla.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2nsnylppl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogtaixud.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2hwajpzpy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2mvajhrvh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gt2gmdqehmc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gt2mrmsjdls.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gt2cmviwswv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2hkdenxwr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbooxdrg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2vcalzxox.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2htldtzbj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2sguvvvbc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbsylriq.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gt2atwajyib.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gt2bhbertwm.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gt2ibuxtyvq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gt2jiqbhmxo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gt2xalbhnyk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2aglrtcto.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2ciogdcyi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2zjqruqfo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2girttubq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gt2tpjfxuqb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gt2isvfzfdm.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2gamfzxul.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gt2ofyfxksq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppoqefiy.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2yyvbdpaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2pbyxagkr.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gt2yattmlaj.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2lipppaff.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozwxuzqc.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gt2vygmyosz.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2icbanmwo.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2sunsunkw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2rrvlvimx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2neebkiwh.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2xyanfsxs.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2dvtbaptk.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2elumnxpm.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gt2pxwvqunw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2fxpgqccs.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gt2rtqovjmf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2pehnpnot.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2zhzsgdpj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2ylhzdvrh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpletfg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nefbygsw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gt2wyvoghfd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukrykybe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkzapduo.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajdxlxcv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gt2xpaevwuq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2iapcbmzj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2yawzhzrt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2kbqlnkte.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2jdrgtycu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gt2zajeddtx.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2pkbgmomr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imebcozw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lrmbvupy.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gt2zzgmvqwv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hcwlgyhs.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gt2opuvmwte.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gt2glfexkro.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2eaouyxke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2fxcmziuv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyvpassc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2rmdipkvn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gt2truyertp.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2lwufppqp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2jfbekudo.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gt2hoyqognf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elbcgjyt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2fdwvakwr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2rvwfqjaa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2dmruwmkx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2montejbe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gt2lkoxlhco.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2hmdedtxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vyncctgb.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gt2suggialw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gt2jjvhxlve.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbfmgqhy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2oxatxvhf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifxoiefj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrvlejcc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gt2cnavfwhv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2wudmqyrd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2yrbhdyga.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olevdzbi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gt2ivtkkynl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cakhwmrt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2dvmlxvya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2qxuogsld.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gt2wktdmuta.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2kpatsspo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2anrmdopl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2wmbpphyt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2ypbhmltu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gt2jkphjamy.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ncuvrvmj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2zhynlwlz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ucbvurzl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2erntmzpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2rbnpxrnt.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2cqlfcvjg.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjnkxyba.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2amseemyk.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2gireftxi.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yagxgogl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2nlaykqjw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2xirftsqy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tasitkpb.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2aufewwvt.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2itblqsyo.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2pcrjloqh.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlxgmlni.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2tyutxylb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2epyeoypn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2tawpetkw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2sohhivey.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjdvjvpw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gt2bzeoaxxr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gt2mpifbcef.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2cfgiacgg.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2xzimedjz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gt2mrfnrotu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gt2vzrhnuye.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2cjzeipxb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ranxqjbt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2fqdqcgwi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2ihhqdfud.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2esfqtrop.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gt2hlwfftad.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gt2hjyqyoxa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cfkogvmz.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2xfiovgng.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2pllsuqvx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2pbcpptrr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2gnuowzdf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2etzrwjin.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2dnoxlhpj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gt2mhhthhyu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gt2sblbhndg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2yjwwqakr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2qhuljjwu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2njsrbdyi.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2lqfpuwxq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gt2xvcdobag.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xcobchwj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdodzyll.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hsuguoxq.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2fxwbqbfx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2zzqsszbl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2gwowapnc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2qhylsdky.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2mryhdamq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2vmuxtbrp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2nocstjoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2yyupyfwf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2elzwcyli.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2rhahzojp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gt2akxwvvlo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gt2ejvjiqlj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gt2qfarprad.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2skzpygcn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gt2shizcley.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gt2lfvdhfhn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gt2hhyygwfi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gt2caarqldm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2iqwmsiek.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2czrdisem.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2bpnhdnsf.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2ktvwquyn.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gt2sbxgybcg.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2jxbmszbf.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2zedjtiaj.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpkslifs.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2imjoqdlx.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2gjdcibgw.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2dafciyml.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2jbwjojqi.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2qmerisre.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2kwocgaop.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzrqkvmd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2qhdpjlyo.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2qdyykexm.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2gyouttzy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gt2lmkmbrgw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gt2mtvhzfvj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gt2thwnwqyd.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gt2ijmzfftl.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2gvgijqds.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2bmogskht.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2naafwvew.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gt2nbxexnka.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2lxfhztdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gt2jhjyrwcc.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gt2tbeimdkt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2zcnrfxed.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2syjllocj.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2bqdttada.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2etvladpi.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2pxoqzbwj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dxwedscz.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2ysrlselb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2kctahuch.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2vfjprggb.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2xvdcpdaa.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hegkzlrj.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2oebijypa.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2beylhdpt.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2llbjavyv.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2qfqvwcrz.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkahhslx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2scycuyld.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2cwgmwyyq.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2iekrcmnm.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2ginofmky.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gt2seghxtgr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2mhzvmusr.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2adgzstrx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2geljmvzl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2adsnuaqg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2octdyequ.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gt2rscvqahv.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gt2ichlhvdb.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2penqvlva.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gt2zlivlwhc.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2fgodhzqh.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2cmmabyno.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2dtepyopb.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2xivdpkfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ctswtrbe.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2vajkeesz.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhyngeik.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvqaoltp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2zmbyvdhy.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2gljuvlec.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gt2ydyzwjoj.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gt2xydefspv.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2ietikctq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gt2wyanlbhd.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2hfmcqdrp.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2gljjntgo.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2lykrtfhc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miqixlfz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gt2viwsogwr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2rtjtlfhd.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gt2spuqxfpl.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2glygammw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gt2vgazvinh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gt2rwzgwjij.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2bxvnvtbw.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrjewyld.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gt2witdxjhi.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2whevjaaq.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2bqcrxxmf.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2wlfgwlgs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2ajbgvbkl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2kxeebkzv.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2pashiyfs.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2mrriczge.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2ydpsbaxl.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yykxhvtv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2valibtqy.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ufydtuer.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2nhtpovyg.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jymvacre.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2ampnbcjk.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2mrqgzpuh.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vouttwgt.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2behusnvq.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2eaprruep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpzdteqz.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2hfhwpibs.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2moranaii.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2pwmpfknu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2ibwnvudx.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2irvzhjlk.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2hrijkjwg.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsvamhco.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gt2tzravfzk.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2yovxgecl.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2fopgvkea.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abgjwjyn.html


<!-- 参考信息 -->