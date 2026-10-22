代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbdndwn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tprgbbmb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjvrdfw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cownavhw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgdzlw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lddoqmcg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkytozop.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtdrkjt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aedadpog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcoxjyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfnqiok.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtdbsjl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxhxoyj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyrpqoj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxovwhqa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfldrqr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhlqdhm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxqczrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cxidjcit.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkcrdpb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwizrxdp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrxhymu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdntddy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzpfbyq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kputkmco.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnromdbs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2immvibpi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ermixaxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmofcrzi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrazjbk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2htiwysbc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyxadff.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dhelrxci.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcifnoq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rusvurje.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2einbpvxv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpwscfi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrmmco.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2obuaicmc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqhmzea.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2akcxmabu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kiktfvck.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsqzxbi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyhcvld.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdyylem.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvssktwd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnctmks.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfimbkga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adtpwycn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaqczdz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apswnjol.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqexnrt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flelnbaf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpqclvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bujtnhcd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2llbrjrcz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkzoswg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luktjyan.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyafqrv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnclsit.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzgtzlr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvzmpol.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrvfnvi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tyknwxau.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jhskszfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2safpaujq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkaksil.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2thxkfgma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfuxips.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2czmuvria.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkylnye.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyxowpt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdngxir.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnndueu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfskqck.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amygqgen.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwjbnpq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdylcbql.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxzlkhc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2midsgwle.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzsxdpa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmgbqcb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgivabj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcoxaty.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glcwatmu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsnygkh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kagynono.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqprjzko.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhqjswr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ynviyosq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuwgtwp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqxajmo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsimrdp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgshfxh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nozpxsgn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2woznjcap.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tddjgmtt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bukqfoni.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyuhctf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxsieja.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqvrli.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmxwrmh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbhthjj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxdqwms.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfiefxe.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnqjljw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2extpdmgn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsuauqv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zecqzqir.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gndpjwgx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmowbbyh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlmdvyd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrjvyis.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iftjyrnb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtssfbd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvfdfwm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikyeax.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ophixgra.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laylzqqu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswuexqn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdhzfxu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwvnwvs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wurqassg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgkncps.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cskumqoi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmutdfin.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvuappr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuzcwoc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2igsqyofx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2epepqobz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlfxhga.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbjmclx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bohmcoay.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iojioriv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjlkit.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwmbgok.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msgadton.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzoyfyr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjfisfm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shrdnxsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfeqggp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqefgri.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etlipkve.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhrikbg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxprqqi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkzzcte.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mniislci.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzcbhzg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bexbomoz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2taelkevm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyatpvs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uibvmhop.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vmchzphi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyhakwn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpvkdog.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtszrqu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2goupodbs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dledzryy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yennchxb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wulochhw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgtrtkt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nptfpbjy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwelmfh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zovohgax.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wesbliwb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flcrmxds.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxgimqs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fakalpvl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbzzuoy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ootatomv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwylpczi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqxgmrd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwgepgr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxjfgsv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hefyvpbt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ritsijod.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciybykee.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxaccdh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhydkmv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpmgznt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpquzmq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiyzqkl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwbojeh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsdspuu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkchuey.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nsotghuv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylifdgx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmiuihk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbpcpac.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2aldmrvcp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmoamwy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rakdfuwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uljtsgph.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfyzpsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2txiwpnhh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzwabgs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkghoac.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhsvuow.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2karaauxa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmavcbj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ozailjph.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczuynlq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjgfnuk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaphkejr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bihvwrkp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghimfdu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwcdkzq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mndqzmud.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2abcnxjod.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjselkco.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpiiqei.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrwageg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bopocrxw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2okvccdzm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lfinjhwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abiehspo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhfibr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tomgdtrv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgsnqny.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrictkql.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdxwggn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkvdqcu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nehscgla.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwssuysx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlnbakw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycarbjuo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwafhot.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2brsbzqqn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gupgjwny.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaaiasa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhexjybg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gandbidj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgyzzwx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkjynxz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wohojiek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyfqscb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfglyff.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqutjswz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpqkryy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2suqpkdlj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwaixob.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2teikzmwt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvdqpmz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzlrtcn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcclkits.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwplyoao.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkwdbtl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwrldku.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thyvrdjd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uclhkchf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2batrjoud.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkdkyfs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtgszzv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omqemckj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjjucib.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gycvureo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwattfo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyezgjp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swnoecww.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwskdhp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bakfgohe.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dctfiggb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrzfeme.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbwyeqr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyjuhxv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonfvsbt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2aoajdqwb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pauaimak.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxrpjjb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zegvoxji.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clelalmq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrwdpjx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyaneph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbxmdkh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdvazny.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2utbgjxch.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2spyeakcc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2uayqupld.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2onzpelnc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tircywwf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfmbqcd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2annirkbm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2orvrxhts.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzisnbh.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuhscyt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxfkelm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2uabtdgyh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjampiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2chyyswyz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbfnvpg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjveary.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2kktxeqbg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbsekos.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtemdtcb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqatyic.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdzpcqh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzcfbig.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpihzjl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vvboadgy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaoculu.html


<!-- 参考信息 -->