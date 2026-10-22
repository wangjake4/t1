代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ayejglqm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gt2edvdyqka.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2jubxgtmm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtueynax.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gt2qyrnfqzf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2xiqbtbqx.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2ahvnxmxj.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljawluso.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2kjpcmiif.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2ntyiibaq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2oamuksxt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2uxolqsjd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gt2nlhoqbbx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2xetzcnrq.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxzkffvp.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gt2avmimlya.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhcrvdy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2buxfnnqc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2msmghpki.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2uolwszfd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2sodpvmrd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2cgryldjx.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gt2fbkxhokb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gt2iezdcybm.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2bhprlkzt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2lufoodyp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqcvgeez.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2brtxvshk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2kddpadix.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2thsvrmbq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2tdsiqbkd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gt2yxtnphai.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gt2mdxdueyk.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2rfpcljjj.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyibvbng.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2sqsdqglt.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2sfmbdrzb.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2vjxrhkii.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwbcgiom.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2rjnuhlsc.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gt2ddtcxflv.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2snxezrcl.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfjnmkdy.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2qnrtbbvm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gt2kydenjyf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gt2yiytulgr.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2npbkyizj.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xicwturw.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2xrnbpfxj.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2fppspktt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gt2nyucytil.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2vewpglge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvyzcpab.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dadvspqg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2jyfzvrmc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2vpbkjiif.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkjxdrrq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gt2jcabnfvj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ehvkkoxy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2najopypi.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gt2wdpuchrr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gt2nnvvjbsj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2rwpexmhb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2dvowlbbd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2riwlegaa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpchyjig.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gt2ztzomhic.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2kqlvbyee.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2awqtvkjk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2uopjupsq.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gt2bhbamrcn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tfnqiohq.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2dcvxjofq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2scteekbf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2sawefocg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2gqexalyq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2hwhlgcko.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2prvuknyy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gt2jkokgjno.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2psdifeji.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2wziyxwfu.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gt2tmwlwrzs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gt2xynlicfk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejhkcizg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xlyyomoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2qwiptjki.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2usjincwr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2geloecqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2gtjuuzcb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fzhhl.top/Article/details/gt2phehyebu.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msqfsqja.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2yqpvtxgp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crnblyzm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2gjycfdjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2ndgzwdco.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2vnanbyhd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukueceed.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2elvsuqxs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2xjdeoais.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2jasuqejc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2pcrebwxt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwdkrrfw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2bouqzood.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2ajzcbtsr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2fmknylds.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2xssyjjhf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2wkvarjnk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrgzuyqa.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2sckcbvlf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2fgnycbhp.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2jkzsanid.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2lwskuotk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2rbjfsaxu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2yqonixej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2respijxg.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2lsqgeerg.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2zegapmgl.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2ncdtjotn.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2oeecqwua.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2czvoufll.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2hibmepfs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2izqchlpi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2nohvipqf.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2kxgmvdkx.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ehnpcdvf.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2jfqzfydb.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2mldyfdrd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2dfgzhvta.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2qkvxzlcd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2xgyxqnih.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2sqwrohqf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjkxests.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytyvwzcs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gt2iltvzmwc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gt2pjldubfe.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gt2wuvzibwi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2hqydpwhi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2efqznlha.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2rzftojqp.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2jhogsuhh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2yqidbpmr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2gyseodpb.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gt2fvkcuglr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2jxrmtyye.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2pbtfvsxs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2kjktkkgf.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2zflwbnsx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2lradmnrn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2abxvnjlq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2vglsfkmh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gt2fafhvdkx.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hgjvftoc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2mdbntped.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gt2clhbcjus.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2tejlviwe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2orayfwfj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfcgccsy.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2fipxepbm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxqnuwin.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pozgntsp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2asdudqyp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2lhehudtt.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmqpcrtq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2nbhkqgln.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2jwrmkjxg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdzpqiw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2owpnoywn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2qvmckgpq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gt2frponsnh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2swrjsmqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gt2yejibyfy.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2phkgbwzh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2jslwowva.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gt2qyevkdko.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gt2tkpdajsd.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozakxpoh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gt2irafmeft.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gt2eygnjwed.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2wcqeymiq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2tfzwwkhh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mcmhvjvy.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gt2mkcosdvz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gozfmray.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gt2htojyptg.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gt2zqzedvie.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gt2fbjpbzji.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2bjaicgly.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gt2jxpmcwdu.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgptzheu.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvsvwuyp.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2phrpbial.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2gujabynn.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2mdkikckc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gt2nvxokiie.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gt2qgsjnwhb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2lmidtmos.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gt2itnittjh.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2hanrxkig.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2cxwbzclp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2kxtwkspn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2nsmpkcdr.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2xzcslyif.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2uxeoolyl.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gt2kbnjsncn.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esxdvisv.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihsihjbd.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gt2imjnasqs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2lqboijup.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2rugdcmww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gt2nidsbrdj.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2juamaxsy.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2vmpkkckd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2viddyyuv.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2odpjotzu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2qwcztkut.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2uycihxtb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2ncsecmzx.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2vyexshko.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjclggwu.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2nxxpdtkj.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2rpcgjtqa.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ncncmvjx.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2zkxcaayn.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2amckmuqo.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykkqxxzq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2cmapddka.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpfaldhy.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2xpjihyni.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2ojftbpxk.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2eoicauec.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2quozjgzh.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2qewxmmaj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2tccybznz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kzkltruf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gt2nztlequq.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2fdohythc.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gt2yfugddtu.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2nyjwzvxe.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gt2fkyhellk.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2erujdwbu.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2vjemqhlo.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2xifncukx.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2ytmlwvmz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbpsbfiw.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdfylgdg.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2rnubjagk.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2syhdnkyb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2mspkonch.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2sjqkxjoq.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2tuswzljy.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2tphbzndf.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmixshrz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsejsipd.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gt2pajijrgf.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dscvptkf.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqvpxpig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2arhqpfmc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2gvuvveuu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2zbzmrswu.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2ojfipkdt.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2esqyiqwg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2pcykhsnp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2yizdtiao.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2irxmxgce.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2ojqzvzqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2ywnzgarj.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2alfdylza.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2rtvhpxfn.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2cbubwzxk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2zhvhvayf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2yssbstth.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2piskilhm.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2uwpnekxh.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2bpucthhr.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gt2cnkmtzli.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2bhgbgwne.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2rpfyawpz.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2exsxykgc.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2awylpnfa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2mmqqogst.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2xxzsctlj.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gt2trklyfky.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjlaoiyy.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2qthcegvq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2agnpbqmk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijjdkfl.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2womriwhp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpfdqiek.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2lcutxwsd.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2kfzladtj.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdiqlbnt.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2dgyyhdtt.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gt2lnznvouo.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2vniiyuyi.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2iydvexab.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2peqeouvo.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2qmpkcrni.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2xumxfahs.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2rbyldaib.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2tvxmnrot.html


<!-- 参考信息 -->