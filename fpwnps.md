代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtnoxbzbyo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzvjfcacv.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtjqsfsjqm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkzsjmepl.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtulmdmgkh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtyfmagubc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtvtksjwwf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgkdldbj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtktbemdfb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gthmxqyfgo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtvsygclsa.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmlczlxgg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtulsncrsl.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtjvjfcjup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtpxxhtnyk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gtemzyrsxz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtvzkefniq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtumwwjwnf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtzlipyhku.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosmifodf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtehhbjnxh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtppkweokr.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbndxnrlh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtaumklcbf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtwjziddkj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtesudoocd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtjipkpwui.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtwvuxcoft.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtblsbqwbx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gttdxthyoc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtdyknlvrz.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtfntouomq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtcfyptwex.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtwvygqoma.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtncptjhhq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtotkrirmj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtzatubwge.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtksmjeyjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtdiqjfdlr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtsxmcauka.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtkmmylxgy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtitjpxmwq.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtiwhcptfn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtemwtocrw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtotlumqws.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtbkmxeiqt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtirictaaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gthuzrpqsk.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtuyhbbpqw.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtwdmdujgt.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtkxbtfmab.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtjksbjdxh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdcxioprn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgkrapa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtweoshces.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibvouehb.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttbbpqduf.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhwkuztq.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgkqlwzl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtiofbwmjd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtnzbegmnh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtvnneeesh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtlqqaucsm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfxkikjk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtswwykdxe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gthizauxyn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtpwwcfbww.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaagnctlg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gtykqpbgbl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtyzgroihg.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtcrtsdkbc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtqppovzcb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtcmyemgyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtipgsmvro.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtbaquukxz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvflcefaq.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtgpqscgoy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxptvfezy.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtdntuquit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggyxnhei.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtlvpwtrkf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtzkuvhotn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtewiipvbf.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmtkhqxji.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtluhocqfm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtznnikots.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtlmwnjybk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtmbbeewwp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthodsotlp.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gteqczungy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtwiobnyae.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbloyarnr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtaslesdbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwjqwzqxt.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtgqsfdobj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzztwvque.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtgnnqvvug.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtyywyufkn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gticgwnuqv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtrmxdjchk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gttjslyxul.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gthxdihopl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtbknpymup.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtjdpzkakg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtznjalkyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtqszppfuq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtyugkgfar.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtbxdjtykd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gtdfbkiccb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtxgtmpxhj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtmrdhhzcj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtssiepica.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtotsuzghv.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gttxdjmvaz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlmxkcivd.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtfzlmzfpq.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtmudahvjx.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtatukcooc.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gttkmplkdr.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtcfpdmiex.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtuxlrhyyo.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtulecrxnh.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtdjsiecfp.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrqzsdsl.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtvvqksmie.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtafymwmjk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtxhgpkiww.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtxwpocvxz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxoqqnvsf.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpfxjtxuu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtysnalebe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtmbkecwcx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtxxaiglbx.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtyhwktiuu.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtxsrcplwx.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtiupvvuuf.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtndbgvymu.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtcynqmhcg.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtctmstkoh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqrtxoir.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtkfrjzkcg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtaffcdbeb.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtjhgketuz.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeknhule.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtpkjpmmqf.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtvygfoqya.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtglqroxqi.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gteeofpfmy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtxmmfvang.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtpzywukkb.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtemziteoa.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtqudhepjj.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtnntfzqbe.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtnonxenxr.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtqtkbtgis.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtzamllnfx.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtpkqzrqpt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtbdwrywlb.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtrxhehleb.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtacafeflv.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtzyijzlla.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtoaclkczx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbewsowpy.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrjfjynxa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtwixrdgvl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtipkapcku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtpmuzqpiz.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtzmciufag.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtejznjjxj.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtothnzlfq.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtpqacokgy.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtkupxztqb.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtwzlrbsyr.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtlbrnfqjj.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtjjwqqaog.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtbivzlowb.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtwcwtubpz.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gthiaurqtv.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtibhxdlcm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtzirzzflq.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtzgjyessk.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtbvfemtln.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtogjflbqo.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtonmulpqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtdgtzznnr.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtqjycgxxe.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtaiimrwtq.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gthmnozncp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtdugmyvox.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtaiaffyax.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtnhyszoub.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtevthberj.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtkgbbszlu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtfxyizaak.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtjiwoevya.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtxnoubjrc.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtwhgbyefz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtmraozfkx.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtugubbkss.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtswpjpuff.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtgdjledlk.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtghvsiqzq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtfxqatlsh.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtfnvxhqzu.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtlklocpzx.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtwbhzdcqs.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtmvsiftgk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtqqazwuoq.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gthrdvcqhj.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtuvikhscx.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtdmdtjzey.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtiwtcowzt.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtfihjawre.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtqyhplkwg.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtkfkcbpar.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtdgnxzers.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvzuuvead.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtefhyucdl.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtepbbnhty.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gtqbpjujxr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtwndibprx.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtlsvhqkww.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtclwuwhjf.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtfwzgfxss.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gtjwzbzkij.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtopptqfjk.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtcvtqnmyr.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtyisvtyfn.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gttkqgloxb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtoogjqcgr.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtguhxjgwt.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtnxvbjrwy.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtjutpifur.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtvvlshedq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtptdlhphd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtqbxmffnz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtwjnpyvha.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtrolsyboh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtzugxafht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbydjkka.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtihyrhtkg.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtamqsqzwr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtutpicrld.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxzahhtlb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtfcbgspvh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtpvjrthlg.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtpsuasbqk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtwcthmelt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtdngfdmzd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtkpdrdpls.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtdkxspxbc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtqkbmhhle.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtcmmjnpix.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtgkgaecde.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtabpyvkev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtjsvbibpy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtekgnsqlg.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtnhgzjgkc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtkkofbvfw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmkmjzzra.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtkmxmiwic.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzcsypstn.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtzxwzlvug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtslsrpjzp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcppbyzqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtfzhzfpdd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtbmltzhkd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrbdvfxpl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtgowsqjwn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtdxwuzzpm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoqtxldt.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacffzldf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtzzzwtxfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtyifvmqsd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtddkyjrvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtujcgkrsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtblzyabjy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtlemhshzr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtqhdlweum.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtuqgqkauz.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtigjejddk.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtxkfmrbpl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtxdjuwyrq.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpwikilb.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtayzzobvz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gthxskkpum.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtlpvetldd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtayrxzwbt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtrvwokddb.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtxjocfyva.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtauzltcna.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtssysrzro.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtgspgvgzw.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtbtcrxqzp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtuzoeydzl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtogabtezr.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtlperlwvw.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtqhwphxns.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtvxwewngf.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gttnnymtdx.html


<!-- 参考信息 -->