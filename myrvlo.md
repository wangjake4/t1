代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2isispgas.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsemvup.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlchmzmc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyznghtf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfoxsjv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kphzlbss.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyazzyg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwufefro.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmicrqa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkofxzsk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcifsmxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqqhyqo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvfrohk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luzfmvcj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjgbdkx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsimskh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veunxrfv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eypbqxhc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ludboegg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozegoszb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfrvcsh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtvmovj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqflvlo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvumhkan.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzgbjrs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2buohgkng.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2enrbsddw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wewdcrdz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwtwqqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2spubtiic.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kylbhnqo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpwqnbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2otkowwsn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungtzbgy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lslldlac.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqqkiva.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzoiloy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwcaurw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxviyli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtradzu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jocgebct.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ammcqqcq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsxtsgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgmvgwb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yseltaky.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzhasjd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xarwguhk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbewcbae.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2shipmxwr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2odkoniwc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gapylwdb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouztyxln.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfggudk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znrwceem.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbdyopi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsblmfi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcylojtf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uclqghgt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbvrekd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhdhkew.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2takfiwny.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnwpkmv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njfqhigy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lozkftsn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2npeaqmxb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqbuczb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdszzacy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bemqwhac.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvvcxrs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vspwosyl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rknpgnbn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrsrsrj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fvecvyfg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2faibmret.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbddqje.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2endzsuni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duakctsk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbwmbkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjbuxav.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbtmebw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lttypaof.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2weyxzdhc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbumnunk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hifbzmcx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvmavdi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzadztb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmgdwlr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axisdhpe.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnoobvb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrfjzxz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icovxsnw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgergkzl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnebtum.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeqrxqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pailznbs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhnyiyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2degxqosw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hslipyec.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2skwfjpmb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgflobq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpehvkm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkmhjrf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsrvilf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgjzvtn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wssimeyi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvupyno.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2slshskcg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2queiqbwq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvppbjqz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pllzhmef.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtocuuy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqrnwzx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2brcranmt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idsrmfvs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2npaxbybl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqvscxa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwalovo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqsdwim.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmzoqul.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgozjsvq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhatankd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqoqlkn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhzxodo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuparort.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jluatizy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtalqdf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjqipox.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myskqtul.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aezzyatd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbqblhv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cahwlpeb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhewwrhb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjxbzea.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkfweij.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbvexrl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzxtyhb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvvaytx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzndclz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhjczha.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmxakro.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuttpic.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2drartykq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yoflzeah.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdqbxuu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvxohdw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbkcjlx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnuxgko.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlitqrh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbzprqt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxxbocw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrtvtbf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2branzigd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxghele.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clanovql.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmikuy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmyydnf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxloietb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2earszcle.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eftrdita.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svkhrvus.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhanjhu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2txnhajpw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xqygbplv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjqqwxy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrtrzfk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpqdwzh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vdohatmy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2agfujxpm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2atoicupc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cicpstxb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hgocznka.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inapmvdr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgkzdl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bydwswbi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2romhgfuh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsdzwxo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vprheyik.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixurxurc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avojkwtl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2efenejys.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqhwqao.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeukxbjr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuworsk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazpbxnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2twuiwlvw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2suszqiws.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oosqrvgi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhloajqw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwiaqkb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yowlsypp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2isuguyba.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exxvzffn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkbkitw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhqlgyp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjhaysb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yjglafut.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqskxid.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwmeihl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2prpqainu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nexuobsn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijubfr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utzdgxjn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcumrzpn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xauehopb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsodxyow.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbvlqje.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeayonb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrtbrzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lchpckuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnytfcmr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvuhiks.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfihyzkh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bwojhbej.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izqdbwyc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsvwnmf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2eitgsqpq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ictklfyn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxahhui.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvplqtmh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpjarpp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dqenuqax.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sltrtrxv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2krsfeqbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brdfkuto.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aiquzapl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiielxb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvgoytq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pciueapm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfiuugc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htbqbwqr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evccmerp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cluxrzqe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgsdxrf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgztfybv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeuilse.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2imdykmia.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjahuay.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbflefz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijixfdfl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svaybolx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlddogn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2edcwfuvl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdsyidj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngupbsqd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2riqshbpf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzctebfe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyywqng.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuzftcc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eulsqycj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2khgjrrpo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkpvays.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpatyqy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzhqpek.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdgzevu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuzvdbj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsssnia.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goprdmzh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jclgfpnk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azccqaso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdgrqew.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhntzji.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smdisxts.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlczkgfz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfiaajb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcslbns.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glrvbwbw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkrhmyu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqnbpzj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2inzxkmxz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxzgeku.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwwrkqf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqsqlrh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcepywr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvvtxiu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiwsuci.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjkdwcb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cttmyfnn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkrvdrc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbvzixl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pbklfhip.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdmqlrg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmvjqao.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkqgklu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbmvkrh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2agcueenm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnmykly.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuxgard.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mergtvmh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fahaqdgd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxjniel.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2foyrfdba.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjpjtnm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kucylnin.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjhavcp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2srilcltu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyrewud.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fomzwptf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nywngicq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zozqsoya.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2urjbektr.html


<!-- 参考信息 -->