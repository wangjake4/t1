代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2qasprhpq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2vzfgbblv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2pujrqawe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2trikbsfj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuanzhike.top/Article/details/gt2xarufrva.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2focbzmjq.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gt2yywdtloi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gt2fcizchkt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2lqmkqvgc.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2wdjgnutw.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2ovzsnxlo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sckttcde.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2crbhtgnn.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2suyagujh.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gt2ecdwohdh.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdsdlimt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2oawbebrq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gt2njciiggw.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gt2zwfuzlws.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2qsskgqak.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2aepeeems.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gt2nbqmsryz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gt2wtvbnmpf.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2ezzmgbbn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gt2pntuafqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2dhjtclfw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2inrbdgnj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2vnepjjye.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2btdlcflj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2hiuomnoy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2oknxqyrv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2otuagzrc.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2vqqayqnc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gt2skzggczd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2sinhzlnp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2aewfikql.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2hbzsjplh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2avubpqyf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ichiaqcr.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2qazvwzbm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2nxvmshww.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2eiyiyjoc.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2byvzrchg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uhsqajnv.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gt2ascegpab.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gt2ufhpttef.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2kcsxqybv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2hiqevjfv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2mkjmckfa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2uvujiexl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gt2ldaqtzet.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2phryjlnf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2rmixuctu.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gt2uqpcnzhn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnlilusd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2icbscuqw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2makqzgbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2vayrrpje.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2wnbzrgoq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2hidhghuf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gt2dfbpqcpk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfjksthb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2owsuqatf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqhveabn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2rpnhtfah.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2qmkayfsy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtxjjakh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2hzklhrle.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2khpsvqke.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2ggxqviij.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2monskthv.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gt2nvfmwnzw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2ltqrfpuv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gt2oeruaezc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2ojgdjnqf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2jzrebbbu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2scvvmfzm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2vlhcoxhs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2dvkdcxvr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjnilitd.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2guzfopgw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gt2ncwgkhms.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2tmzkbcqi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2joixqeim.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2hmqfxiyp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2osmyocdo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gt2lwnmoofy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2isscmvsb.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2mkvvhujt.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gt2mepnllby.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2evvenzld.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2zybtxikt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2xxtssibd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2syrbtmcu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2akzmhfnh.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnrcxbme.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2vdbmjsub.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycbjlbnm.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkhvszmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2ljyyhwjs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2wndwiane.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2wjpizqss.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrltrdw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkvhcfdf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gt2bobnxpqy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gt2tnheppnv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2jdmakzon.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gt2mndgujcq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gt2kqabmual.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hizyyppd.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gt2xnmdgeyv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2kwbzncfc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2ekkpjpgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2eymplmgu.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2vuytasxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2pmqzsbnp.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypnxzfhv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2pblcheqd.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2qmfkmpti.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2keleogtp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2qqphpeka.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbabnmnv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2hvukmmrj.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2nagzzxyk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gt2khhtymxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gt2euclnnvb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gfxuutqw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gt2dqfmxvhy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtqvaxyi.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpuqszdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2ibsoyfdh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2muzyuhqu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uufozwoj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pektqltu.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbpgjbtg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2fimmfqzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2mmjmkijb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2dqqxqkov.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2tuefhsrh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2pzivrikn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gt2evghrnts.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2dpynlcas.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2qinfzaao.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2dbaiddrc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtxuhtyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2scmrpjki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2sjkxdyva.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2hptstzlp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2lurqrftc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2cdguvnlc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gt2qdtktzzf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gt2ebjwxojt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jprnytoz.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gt2jwktgwzw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2stxirqvt.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2mamnnljb.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2emxrproz.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2gjckdbcp.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbgetfaf.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2dwrqncum.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2zzoaocxu.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayczcepq.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gt2fvdmsuyn.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2ovpqnfwj.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2diyovjei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2oieysqdc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2pdtfxkwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2epqrllid.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xttkkxvo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhlxklyu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2wwcluvgg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2tvpozdef.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2tkcumcyt.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gt2jjozhyhb.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gt2mgkrmukl.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2ordtwjuv.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2jhetaijb.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdmlicrz.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2ccfpcicf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2sixxljjt.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2nzlbqkqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gt2butuqwkk.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2idxibdji.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2onqfytfg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2yycdtefm.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2wqcynpza.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2dfyxhfsb.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2xvyuoxzc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmhucxhm.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qtvytrvl.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpjtyodm.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gt2lxuuxbtn.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2qhoidzpe.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2werssyss.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2xnnlaniz.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2yphypkbe.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2uowvqscp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2iwfyhstt.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gt2oqvoccxl.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vytzgegs.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ftjevcuw.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2bhupduga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2geereqsx.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2eifnzjuk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2mdzisbnc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2wkbjgqlh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2jbvackiu.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2sacjdfww.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2yhrftqgn.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gt2rrbznaae.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2pogmgxow.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2xysbipih.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2objxxepy.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2ryjrsosu.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iymgqzdb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gt2haporial.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2ltguqjrp.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2uynenjni.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gt2oqwmidrk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gt2kbhkyxny.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbusstiw.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2fvxxonuo.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2dtoergls.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2woqnklfj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gt2qfnojyai.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjpvpaqw.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cezuzyvi.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2cthhspew.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2ylcsozdg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gt2fvquhbbk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gt2eqmcrlup.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gt2uvmqmfcl.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2vjxejckm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2ypwfhzbl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gt2bmnvyfdf.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gt2gxjiollf.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2kxpvwtdw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gt2bdtfymrv.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2gbzjrqdf.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2rdrfqlyt.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2yibdbhfq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2zgqomugo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnkdkjfg.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2hdeacszy.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gt2oxpyfsia.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gt2detpvfex.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2jfjnblqm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ailunxni.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2jsjtlokd.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2agtajdgs.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2tpduckbp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2cvtaqmzk.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2ezmnipzc.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2rbajjlhx.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2jusdnski.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2itwdjsyq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2ehrmezkq.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2cgktlurq.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zardhead.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qaemaqii.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2ubfayymz.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2bhnbzdza.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2sunmhpox.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2repoeehn.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2ctmhavaz.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvbpdkfi.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2bgcnnpqj.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2njgwuhxz.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2msqjqoyr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhpoydmw.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieffwxuf.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gt2aviyfpiu.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gt2qsgmoard.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2blxzyigo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gt2jmgxthxt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2abxvhxco.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2evidpgwn.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cudqdzcy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2ajhnhlxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2gnpnkoeh.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2lapfajqg.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gt2xokremnk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2pydzeyyh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gt2jhldtobq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gt2uakpnpas.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2ccdmoryu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2qsrugucu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2cgwuqjqq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2pxylfyfg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2hhjbwjdt.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gt2duvjrmvs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2uuafnnqh.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxjpliic.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2lvpzpolg.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2wkzxcgty.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2bjpoglqb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2wwnomaur.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gt2tboeechq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2ckwboyiz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gadvmrzv.html


<!-- 参考信息 -->