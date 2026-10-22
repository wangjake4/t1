代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gt2gupeustu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctxuivga.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2lcvsogdb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2uzqirelx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gt2pthsggyp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oldpgdkc.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gt2ldkmxjwk.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gt2poqlxhac.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2eijwzafv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2gxhluijh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tyfblydu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gt2rmnatnaz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2ehtsskcz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2xoptxslu.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2vfsnesyx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gt2mkprggga.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gt2tbtgtikh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gt2ltwcgzvq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2yjtwyvml.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2uassspta.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2omxkulqs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2adgmpowk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2knlwkffc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2rpffipgd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qacbyjmq.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2ssjvsiro.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gt2lrsvyflr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2khbwwihx.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2bbtfojza.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfzhuqsa.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2dppnmuoz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gt2irsgjzzn.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gt2psuatfqh.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gt2soacdlpk.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdaonirq.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gt2jlhuihql.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2kuabazzk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbzruzx.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsebqpxb.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2keynegnw.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2vhfzdwjc.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gt2hldxvvyl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2gwlocqvz.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gt2wzlwyefm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gt2zzalgqni.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2tzgrsxqw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixdbtcav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2eedotaxv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2urbdkerd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gt2lagryaug.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2frkbywta.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2vwyjiwjm.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2hqlcvxnt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2gawnjicp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2kztzxiwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2yrnhfumz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2rgaloumd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2wyivjwxh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2aqlvnisv.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2mdpokdfq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2kuhcrtet.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2irjphvjw.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsvabewh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2yldyiwrj.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpelarba.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gt2mymvzrnx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2tpobvite.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2bjahxaur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2rnavzgic.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2qiwrklmd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gt2kqysjlew.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2scpuuqjl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2bvudolca.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gt2gbwkzsrm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2kltgihjt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2lqbzkomi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2wknifxdm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2kvhpdlbp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2pgfkvvni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2dgqtcwhh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2ovdvriyb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpnxulqw.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gt2tsshtqfu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gt2mlcjtymk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2squplviv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2nhxmvdcg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pttpmicf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2fayyotut.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2qkeevhid.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2jewipuqe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2ffbdusjm.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gt2eowglxrt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2yfkwsfuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gt2ssjogiwl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgllvilp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2vcagpwvv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gt2gikayntw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2qqyvsaxo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gt2fvtkberc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2yyvfzhsx.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2lipghvae.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gt2zctkfmlw.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2jeaqhrln.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2gwhqwoew.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fjdujfrp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2chrlefmy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2bmwilnxo.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lkqkevgg.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dptugqvx.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gt2clwfdbgm.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2zkqranfx.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2medauldp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2qnpxwipf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2mibhganx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2manoadsu.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2zavxquvi.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcrzxnvn.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2aeiutjcj.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2jvvxpksh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2vtxvfanh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2akkjmswk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2imrmfrfk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2nwlhnwbp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2lyqipyrw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2smjvtace.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2cxrhgymf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gt2bbbdatfu.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2meeyiwpk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gt2okmwdtzd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gt2wikrprki.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2wbfuyvxr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2snisofic.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2omcflhjy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gt2kycgvctd.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gt2gronkpeb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gt2eitikmur.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2rrodjhck.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2zgvsyuer.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2wifvvccq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2ritmvsgl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2yljdqgcj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2psnewpez.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2eacmuxdd.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipasowfv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gt2nraitkqr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gt2fhonrrkg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ffollsbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2czwtowso.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2tltukzsn.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2jkcnkliz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2hwttljfe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2kkdyyhif.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vveznkas.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vvwesiky.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2yoatuwli.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2ogrmwffy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gt2hkiamhvs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2dswlbwgs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2fbhvtvlp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2ookzmzle.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynmrrhmz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xfytltrx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gt2lmqzgazs.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2hetajarc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2pknyrmjv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2ydyjqokv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gt2liatvmvj.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2wugskxvn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gt2wljuwduq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2pydgvzxg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2jhduqsgv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2veyqidty.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2zlmgtiaf.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2dzvoiezr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2yidgwkit.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2ydxestnu.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2knnuiibw.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gt2qlrtsuut.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2pfbpktqm.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2dnebfppg.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2yqtnyfty.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2fwbhpskg.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2aokvdcnc.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvenypdw.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gt2lxjwqwaw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gt2bwomeqdu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luwkkpgo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lrbqowsd.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gt2ntmzjluo.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2fueszwnh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2zmiecuht.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2uwbvslhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ftxrfevv.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2kqyfdmje.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqjkdoch.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2vryavylq.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2dnesfkus.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxiiqifw.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gt2zwklwcqk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gt2atespoqe.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2hlovicyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2uwsxadag.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2npyxcngn.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2xaiiusjj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulvixdzh.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2akjphwfk.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2khdkeuwi.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2exnybmxj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2minbbiey.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2lmznlqqn.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gt2wbvjstqt.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2gjqswmpy.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2wvjfhueg.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2wvqgprqc.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2zhdgnohc.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2mjodkkqb.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2vyolixwy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxmurmw.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsvhpiwc.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2gnkbtodn.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gt2hzvxoehk.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2guadmsio.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2sebsqrmq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxwnnanb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2emjlducs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2elamniri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gt2wqxhccgo.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gt2fjopoiim.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2dyftedbs.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gt2ywygyepi.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gt2isczzgfv.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gt2liuyxbvc.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftvcbkxe.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2cdywmtfc.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2bnwenbbv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2zccmypcy.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gt2czvgylas.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gt2xmdzhpic.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2emqiafzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2rydfjcmy.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2yudusmbs.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2udkwrssh.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2dporzsny.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2umsbckue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2aaiayliu.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2fgizrxid.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gt2vybreodi.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2hkikztdw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gt2xshwlibm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rjahdtzr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2hywtnhov.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2tjfquqqe.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2hnnvgnme.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2fmcjoqyf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gt2pyxdmxir.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ioeuejhh.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2fzkzfeky.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2powhzddq.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2fcsiriwa.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2yrrtqjqr.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2dscizbaj.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2wazsvsgd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gt2zyxlbrls.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2jqufrqfn.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2svyyytpz.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gt2yqwadjsw.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2ljuqhiat.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2tqhejxit.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vhgehimr.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2noftpmpf.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vhpnmdfv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2keasbapo.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gt2jnsyphsb.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2hsabuxnf.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzblyvdy.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2wcebcemy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahfraayr.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aaklkche.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2trztachk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shsexjsn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2insfbbwo.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2reauwuku.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2vbjesumk.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecqobrmt.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gt2xgogzlmk.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2lvbzvyib.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2fsmbjzen.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2tswrnlxh.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2wyczacti.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2vysexqtr.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2kgnbmmsn.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2rmuuksnc.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2csdjpzuv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gt2vjqyacui.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gt2moxuwuxu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gt2jznwgsob.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gt2zkettbzl.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2pzzvearc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2hphrfygo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2dqjfubgk.html


<!-- 参考信息 -->