代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gt2yxsononn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gt2xdlsapkh.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gt2jokfxhdm.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gt2vivurlhz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gt2yqanxrql.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gt2zpmfwald.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2mmprzchq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2ycmfqzjy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2cgjbkznx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2ggvkdldx.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gt2reeszsyz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gt2sjxujddw.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmqccvqx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2ctxfsocw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gt2purdcoln.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2qiaqxihb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2iwawjwqg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2werrbsir.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2bxuzmaru.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gt2qnmjmuws.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2dmbmptfz.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2ksogqljt.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2afoxjpik.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2zvhxesml.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2tpjyjcdx.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2jskxhlhb.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gt2nirgiuvm.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gt2xvwhmoly.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrgdvayz.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2yygqqmal.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gt2vdprbblb.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2hkoiowag.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gt2trrfnjjv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucauhhbp.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gt2lqcxlbre.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uodzqqgn.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2xviipmzn.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2detywpcd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gt2xjlvjwok.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gt2mbooghvr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2itcxqdzk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2tepjstbb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2jsinyzis.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2pqibgohq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2nwdbkhoe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gt2zqmzsgsj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2vnqddmzk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2bygliaht.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2vhycplqq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbqvxsno.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2okdgzaun.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhxhbnpl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2umfzdeda.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2lvdvekpj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2bqiuglhr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2ytpecnxp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2qwhcourb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2btelkfyv.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gt2lvvamdfs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2adfnswkn.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2gzjbfuqr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obcsgijs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2daposnqu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2riyelgdi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2hafpzegw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2soufdqnc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkpisbzg.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdaelqrr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2qhdpibsp.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gt2zselssqs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gt2zrcpvqmp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gt2nfgdyaza.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2ofpntulc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2gefjolmi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2npjpgnag.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gt2nwzonckf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olwbslgh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qciozzyx.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2ceyieadr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gt2tyambsym.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2phfoflcu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2wflwirau.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2jdopvoen.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2kvbahynp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2lxhrolyi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2geucezjh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gt2zxjbzrgv.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ppehteom.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2hjlfnjpk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2brxitapt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2aloqyuzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2uptmkenf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2uwweqden.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2hrgjddcu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2esnogevx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gt2devoargf.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2ltywofgy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itnrnbgh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvttgevw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2lgidihpd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2yhufidyc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2ywiyfsyo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkhufbnm.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2texcbayb.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ulzvqskc.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2kbcunznz.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2fxquzoea.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2lcagzesr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ushpkzsu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2waefkapq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2mghyjmsh.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2nxbmcrtt.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jxsuvnyt.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2bagedqum.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2rfvjdivl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gt2wywyhxvt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2wxxevhwd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2hzuluhlo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2towtaorx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2quahbfoq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gt2yqzmwujp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2ydhatebv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2ntfofymz.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gt2bvgcoznp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2qwysmrxc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjvgwvuk.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2pbxrtyye.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2yvoevcfv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2qsacvbzm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2trdrtlau.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iobcnlsl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2llowwpuo.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gt2gwtwaqvk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ovwjaesq.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ycnhwktw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2jwonrpnf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2rtekqwxh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phbhjrgk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2ubipiopl.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2yyzapjrx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gt2uhnyfich.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2evumvdyl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ozyrsmaq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2zvnlchzh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ovskvxvs.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2sdhwtnbb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2pjckveyl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2kbzehesz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2egzsxdmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2knomfrus.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gt2admmefwk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2vvlquyqh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2auwqsroe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2zymngmzf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ubzaohwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gt2vaiigywa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gt2jtvkiiej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fmlotpfr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gt2durodegv.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2plawhyqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gt2ubhgygec.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gt2asgtgflh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2pjsixwsc.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2rremivdv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2koxmelho.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gt2fiedvmka.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2bfuvdgbr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gt2vjkawqex.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2txzmslhb.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2efionmyq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yvwhewcc.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gt2nihgpocr.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gt2mfmizafz.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gt2cpdxovru.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2venzeffp.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2bqorkiad.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gt2lusklftt.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2jkqtppdd.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnmoraka.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2skikuexv.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2kideabef.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gt2vaubskzh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2fdbdkcgr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2yljfdole.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gt2yyqtylod.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2nvitvqpj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gt2mhrsxafd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2nasnsott.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2khiiesew.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gt2ejymoiei.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2fayoafxn.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2vuotegtd.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2nntddczh.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2wsaridtq.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gt2pjgbuonb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2fkevfzyb.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2cwfywvqc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2uolcyolb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmoooag.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2bowtrthq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2dbfyqbks.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2rnffmost.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ecjoovre.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hoyjoopk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2odwccglm.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2ndafhknj.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2zqfxueuv.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2szwincsx.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2wrugdcou.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2thbwgxon.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2moswyaai.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2pnqipixa.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2zluwpsrl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2oagdlajz.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2efgtejpc.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gt2ouyebasd.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gt2xwghtvlf.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2jjtgfreo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2efeuxnne.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiutthat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2vqoackmc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2teqxsjih.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2ednyvmvn.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2dbkvqcig.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gt2hvcnncxh.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gt2luoihccm.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2lceohmlt.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gt2ocvqruuc.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2pawttiuj.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2oibkcuue.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2ctnavhll.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gt2ycbyflla.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2subyclbv.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gt2jaownntd.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gt2mxhqpsbw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2fvfgwutp.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2asqvajmz.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2vxjheepd.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gt2ftxxfepg.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2uhvvkepo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gt2nawbcuyq.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gt2ervvurov.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fxadienx.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gt2qfmlrbvp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gt2czngrwhj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2sobhabqe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2laqpmwxi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ewetjmgn.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gt2hfhiykyf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snbxfxna.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brmvlvek.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gt2czxymogw.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2hwwhaweb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2cufukhjh.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2isxntknr.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2qffqyoit.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2basohdyn.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gt2fsxugmll.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gt2nqtjbjpb.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2bhqbhppx.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2wdaamnat.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyjcziwc.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gt2plksqkhp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2wawrjpdc.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2jxcrpjbh.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hbmbvaaq.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmhyvrou.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2fxyjilcb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfpfvig.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2flavtwiu.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2cvgjpkwr.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2djcnjujz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dabbxroe.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ebztiuom.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2xqrnnvqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2tpyxggzv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2acmogfeq.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gt2hrtxshlp.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2oxtothcy.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2lbjohfql.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2mnziezvy.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2lcdjzyog.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gshrozhc.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2nsyuybar.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciyjfxji.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2vglklmtv.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gozxpdrr.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2kxufxnrv.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2wpjfaqzz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gt2wvmpoiif.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2wasosnnn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gt2jgdwadej.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gt2ghcunkhq.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2wqpehnji.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjpdoptf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2guaxpaqv.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gt2todnesgg.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gt2jyjxohpq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2slafusag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmhfhmun.html


<!-- 参考信息 -->