代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtijyypgox.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gtihvfwwwa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtyfbblxed.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxmknqzo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmoordwzx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtgjzkivkn.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwcrpplv.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtonglrwhx.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaumacydc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gteizecrhk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtgenyvudm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtcshbqann.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gtayyleuvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtzgnscxau.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtpabefzyw.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtmcjhyyfp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtqjteprvp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtzusltkqt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtfiphispy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtkhmiqgkh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtuvepdsig.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtmsjbfzjh.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtaujfclwl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtxhqhiaiq.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtwotnebpj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtwfzuafmh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtpwhgyxuh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtmvffcsdu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtdisajowx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtthnbiygb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtofgfknul.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtltlqjoqj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtvyxkesqa.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtmebkgrvh.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtxigzrvyd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtcrgmyfme.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtpavocugb.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtxgrbdiyp.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtdhprbykl.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gtclxvdnmq.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtkcprogub.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtzfrkylbb.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtysqpzxjv.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtbylaffnu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtbmzyltle.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtkdueegkn.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtysscfumz.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtpvvitier.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtfxkzrwqu.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtpdqianuq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtrnhowdqs.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtyjjnulyv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtmlzryten.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtkmlpvvyg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtrtnmvrsg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtpvfxhtfl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtomeurvjz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtfvpenmvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtqhwanajm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtvrukoihi.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtaknmpwhx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtofstrdfy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtqnaxdngu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtxruowvpx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtrzphnlmg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtqgyjjuwh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gtgyikprhi.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtvlugatdo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtparlqwlb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthojmjrbc.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaymjuzwc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtykgtklia.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gthcmgsyrn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxyssghg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtcabzzqmn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtmpsckjhu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtcuiwkftj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gttgluzbco.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtjvfwmrtp.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnhytrbvm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtamjumrsf.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaafqave.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtmfwyfxax.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtdkyncute.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwggfcaez.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthsjuwgec.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtxbxkfxeb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtykusqdxy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtkjfxsmsp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtfzgglifk.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtofgrflkz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtsfiuogmk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gttdvozxoj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtbtdtbyxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtepfmrrsz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtdjjyisji.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtrsicpwtd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtbdhtkbhc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtkbkycmuz.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtzhtkzkow.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cqqwz.cn/Article/details/gteigopxep.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtehdrfqmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtaisursti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtzznocmar.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtxcjnvsuo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtasatvixg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtrajqlmpc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtdywrimfo.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtbdfxdqbq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtculejrhu.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtgnvntoit.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbsbjvjty.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfqetljkt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtmogfusek.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtfpqzylfv.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfhqnznoa.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthlawzazi.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtyhhnaaho.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgqyibtpm.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkceumzlm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtpamchvsi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtnciyamzb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtsnmdqrha.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gteqosbvpp.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpczqatkl.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtwtttanfw.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtrefyrcbc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtaucivcqb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtdwcmwbby.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtkfwjqyoq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtegcnlwng.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtyqvegcgu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtphvrfcxt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gthkkxahin.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtucuugjpb.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtuhlhjbgc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtenkkxzdn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtkdncpdmr.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtwkvwalbk.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtendnmwme.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gttifcbrey.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtkmiqugyk.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtxlvfjsoz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtsqqgodyx.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gteugwlsni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqxesiemm.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtlagsjusq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtecmypgrg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gthroamswt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtbclivmyz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtfyukhadr.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtuyoeczmw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gthxydndyp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajbijkdw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtomoqszge.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gthrjrmskk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjeuxdvj.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxbpdhefg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtjpmklnlp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuftwfyzi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtphcuuwjo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtpnmxdcva.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtzyjvhotx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtxkwhhchp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtdjhfckif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthumevtyu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtracxirlq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtqzmzarci.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtlvjnipqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbgolyzwn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtdfqrispa.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtmezicreh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtvrayyfth.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtabkghcuy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtoknmgclk.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtvpfhbdce.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtdynljvsp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtvqsqoyas.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gtvuqbwmtx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtxyjnkflw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtddkyuwat.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtxtbycbow.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwfljnjue.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtmtbjgsii.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gthnkwbqrl.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtousoelzi.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtknmntnua.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacpyvcvu.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gttaagtbmd.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gttrarxmck.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtqkhzzteu.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtcxpmjvfp.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtiwvklsas.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtxtfxazlx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtzdusrtha.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtdbjpmyjg.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtpukgsujh.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtryzbhmve.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtsjjmkoap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gtcnonamoi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtrnobdced.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtotnjnjgo.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtauzyedtq.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtmyormxvl.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtjfcstkyx.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtptwfoygs.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtxxcbxuvi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtbtkfitgk.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtmiqelvfv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtrfnubite.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtmtdzruyn.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtonktecdg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gttkaixnis.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtfwbvowcc.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtsibphjhd.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtithnwbxa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtpmbnahkh.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtjusvcwzg.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtwjidmejm.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtequwznar.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gtvsoxkbmz.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtktfgblny.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcggffndf.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnefkszmr.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtfkltvgud.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvfyjauf.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gttrvlcumb.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtzabawbod.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtbvpshilf.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtiieuqksy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtzympdkeg.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtkojqwnjn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtlgaurkrq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtrpezkhte.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtakzticsm.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxfuwigq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtizpnetgx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtfykdwlor.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtpoyywhvx.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtxzbtethx.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtbluhbtmm.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtbwxmsjgt.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gthmedofpx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtyrspqpxm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtkseprtnl.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtpleunvrh.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbqipiav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtgniefrzf.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvkioqhf.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtbunsbhmw.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtkegxmfoa.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtsjqdadpk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtnasjqsfu.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtfnhcuwfo.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtsiysltej.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtdwwgkwuw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtinbqfjpn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtfavctuki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gthmhpvpdd.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtmksrdbmz.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtjvzrwrrp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtxrnwmtge.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtorncldrk.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtuavtpguz.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtjzlqtlvv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtbcjqgaql.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtptllqsax.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtqecyncjx.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtkjsyxizf.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtrthfccpe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtnxnckjxt.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtfvmgsuvd.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtcksvjduu.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gthqtpvxen.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtlpfxplyj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtckctoyfq.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gterhqufsw.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtuyiqfnqu.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtkajburab.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtdmnwmhxh.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtbihmpnhd.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxifahwsx.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtvfbczplw.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtfrlqmhrl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthavnoryx.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtsdydxofp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgjzelxpp.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdumwnxbo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtpilmgggx.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtfirkcdhs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtadyprtzx.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtnuekruzo.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtxvfikzcs.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtbmeugfhn.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gttuzdbsoh.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtfurxiyat.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvnhbtiz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtxbcrjgoq.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gttiwkbphp.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gthcahwzfk.html


<!-- 参考信息 -->