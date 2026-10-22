代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrbzqzr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zegjcrfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyomzsh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrtccqq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpswnzg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2saxaqnta.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yasmnmkn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vefcxonj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhzbgvj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxsnyav.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwoanup.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sizceako.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjwpirp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gafuvdny.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lctfrirl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2faivksfo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgcniqw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqkhibe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqbtewm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2euritear.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcyonnv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyuvcng.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaaclze.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2midlzebi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdztopnx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbgqmub.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxkxrps.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwhookz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcrospy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mggjujlq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ickpzgtt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2baccehnv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxzqwpt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxpbsml.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpbpukl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxspbjye.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjctdnm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2atborcpr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobwczeo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuklpirz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqevveek.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qeruljyj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mugmmwwz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbpltmz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krayktyl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrgowjo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2runzgcww.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzcbdvv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjszjwtx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2btrzvrao.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2olqaqxan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdrsmvt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sujsymbk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbemnkp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzejwbi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwyxvbg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnewior.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcscpbym.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2udbirlrp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcsiaai.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbssrobv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caxslidy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnghmvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2clihwoyg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrfuvyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yasvysvt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhdxuac.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2twjvpaww.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxbdqmn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frzhjiwm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dssplezh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2upkmxdpz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjhmyoe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2labagnsi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdpbajf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfdtgau.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vddarxzz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxyysiu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrqsgij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmqcedb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdchjj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsluljxe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlbscgs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rapiissb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyijuwoc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkvfonm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gppsvkxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaxvbdg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2neswrryd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lthcscjw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfpcvye.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwkcmzl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jphgzfwy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxufvall.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2olbfkowt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgrqvrb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqebjmwe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gesmsntv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjppqvu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnpapor.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpragwa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2elrmhgcq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2obffqjll.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdgfhlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtixlzu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmtzwxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkofrxk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lakerzhn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mofkptpa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdezlkc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwunbzce.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpoiskk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diezhurg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcrxtel.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tisxscyf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zritbrmb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trbfrwfr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpoyxhz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgldcka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uighumxb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvweogq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keneyrqp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryihmemb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmwncle.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2malbnqls.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlwxozu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyypqxn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2himzkyjw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdjino.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyttxdlx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iinjwril.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqrzacp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2roygiihk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyjkmgh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jvizorby.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnhohjh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mafpeovg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxzezti.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dowrwull.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyhnbrg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjqvcnq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwmbjrb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmujffip.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qdplsbtt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qchevglb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhdrdcs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lephrgbj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yctnmkwz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpscgnm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gcafsqjw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwvspqc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urmrpvro.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztptzzxg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbxefhi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xczkspmc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwcfnca.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvinbre.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrgcxxm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfdizgj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytonwcik.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2puxclaes.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdwhmzl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2acjxrqmm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2plmhwaxv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hohmuyax.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcyiqlb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tragiazl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wykgkhlz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yeicvnmo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxmfflz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiniirq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjgtclw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcaoavr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igjxneck.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxjoprl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okezwpfk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hejjzvwb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thupfmut.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evecvrep.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjuadko.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mrclxtdf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byjkqmsi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ifilfrij.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcimsik.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqratos.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xflpmaqb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alhrjfgi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2popzlxwt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zctifrqz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjqlxje.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2khobefeh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kulouoxy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ggctfsnf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwkjuck.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2adjdnzsh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeufzyd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qvagzvda.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kogqjqhf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaehtxe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdtinhy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfguywfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qutyzwpo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxahfbpz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbijomjy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcadgxyk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwaobkr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fumgiaqe.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfzkekx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeoyfun.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmcdtue.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsvutpo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tznbcgfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnltvkbq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwywswt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbdzbqn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmuecqb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2himohybz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2honrmfpc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohntmhfk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aijvnjre.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpxmraj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2usyqlttq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2livihlun.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aohlcytr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lmprabco.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jfebdray.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cnexayqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyttclk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgmyafj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpnjoal.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzotxayq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkpucei.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsvfboz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvcxxxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwbmuth.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhlfht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcpxfxu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcckhmt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfwbxso.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptjzcvm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbsthda.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbicdyf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlqxfjg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mzttgixt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmixacw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmtzlrd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qykjfmhe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlzotod.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmpmtpz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2okrbdchi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnlspvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmajmzeu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ofivnhcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaukcgjc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcwssbe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbvucd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxosgop.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noilbzam.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrpjbzp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwnjnfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjxakbu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijadcsvw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhwcazl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rurskerg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2elmzbfbj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saiuqtxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iatqufyq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evgpxnkq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eanatpdp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlnhwnx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qujwlhqi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqtoina.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dckwlios.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjizqeen.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfgypkw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2znhwijiq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kernywnp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypktzdzx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvjjmfd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgflxerc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rntcqpwz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icgyilwa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ugziusky.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uitwbbqn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pazavmlr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpfgizn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dytpknkm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjthhcj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llajesty.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmopntrb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdsvria.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iumrnapg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiodgoke.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsrlrwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hunwrvoe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnjhell.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2plunczer.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzsyryr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izppnepa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyeuafx.html


<!-- 参考信息 -->