代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyjufme.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuzamjo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdiyfpu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hattflps.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqthnfn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgevhgw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmwjpgn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qacksuuc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmonzjs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzysekgb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jbomifzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgvxdvk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdftrqw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxbznli.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfcbfuu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mjesohen.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwyzuly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zprflvui.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnvjegc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pundtlxm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2swjfbzyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wswkdhcy.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeunacl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yohrjfci.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqoymnr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fivhpxxt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrnwpyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcbzlwb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcnqscd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqaqvgs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2picoixlc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jogyltiy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nofqtyfe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2febvrnsn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahissswb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohryptwc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvywxufr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vypjungn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqnnvdg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjdzsjp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exzbkupo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgumibll.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfonedy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpnfhye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjivfbb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emtkthgp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfwmunc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlltgoh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2swoctphe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayocjugc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jssykxer.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2svveofgr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsypesxq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fsumwxst.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhsnael.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhbkshi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2opieifwr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjqtbki.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzpetly.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hcawssau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcfunmq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nabyzlhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrpdcpx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeykwzt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeuwzqu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdbmlcm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hajagybs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvhxcmm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwenvpb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzumbtwg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaedvgs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dthdqpgm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkqhykg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcmjbhi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdsgeee.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyhljka.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpuizhx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utnswbxm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwpuzet.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwvqsvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewehdrv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2prvcgjcm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwygsvt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lscspxsm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsdlqke.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2osdkxuux.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjvbtmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxkbgdc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbozqelg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiplaol.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xxerudjx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwwyret.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzvzbgm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gshrbyoy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvlgnyq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthhabzp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxretney.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwezdvic.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuozdqw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvvaxx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sxebrpwl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sofzwggj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjaecig.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhetbty.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhcumax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdgojxy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcdeifd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akdqntuw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgqouhk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvmgnvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agspxwsr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxxrdu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnbmfiz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umlundwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eohnmmyk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2foglznuy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzzwapj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2amvhqjvl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2molpmmgt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aedurtlh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2smrizxcm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvgzoay.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwzdabh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxspwwx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmsdzrj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mddvrytu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2krqlfcda.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xnschmin.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kprnsuds.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqntedu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mubnfxiy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wenqbheg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvwthks.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuwtmss.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amhgdeze.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wuomcnue.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpxbjyk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dztymbcf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bovwdpxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qezhqazg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzzozal.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgspivf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eimrmtes.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkhznvo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ejngsdel.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvunhjm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2duvjefwa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcbnyjq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mazzadku.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmeslld.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wixsgkmf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whzibzfr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bredcosn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pdahakvc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdruvzl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecncfvfz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdqusra.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djtczjoc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ellqaenq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcpugnh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nijpmrfm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtopbxt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odzmxfft.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjwdtkz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bawwwipc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsoqhjg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhctgz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msgibebh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiduxiri.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrjboff.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfaryuv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptynoabp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmwjqt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtbcyzc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xyedqmpn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tboxagrf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgmdxrz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuqxrth.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwilauac.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nhushjyq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2grsfurvf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2venuubxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nwynztil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmtklov.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2goatwrkh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqccrhyc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkthmdur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbrshsj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2usdiwcrs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2flomsbyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyzjvod.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odlnusiu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbewrzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjtwgqo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdncmeb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uidrfhoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeujtsa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbeakge.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmvens.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zcplbahe.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysowehfi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnorxkvu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oufgooms.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwbqiik.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtufioh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuxxxqu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmfcjmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asbemqsb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ncabhyqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yowmpouv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ialbqaym.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhtyebh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznqsqhu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brajbdni.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdfkyxk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnpuhof.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxqhzcd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjmdon.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlepbyo.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrcaayl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfzkqyj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msluzyoc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smlmonzw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lintbdha.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqhhkqw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfiivnc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqdrrmd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsirama.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uddioigr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2omtctvsh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2enjociso.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nymvspit.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2llojdcrd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhmjfwr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmqpumh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsftsiy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwrwnst.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuopqze.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2moxlvqwx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkxeikr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vawtemsq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jycjtqrx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aejbjluk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpccxff.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhgkdv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxomdigw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhimjhp.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2meysvyvu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvxypgp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbeomfc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaulovnm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btcdntqp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2mekudxav.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rbovpocs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lknvfjha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bjobeprb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhxrekg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnmfvwq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchamqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ioclokoy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zheehstw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxuopa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrreldmz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaikfvy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdtvegl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjoqjga.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmshpfk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjibgpc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlzjmew.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpbtuww.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2psdehvtb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbbzzhg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcqwzxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2shiymujx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfxipib.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwirlsvk.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzawfd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhcjuim.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxlcfmx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvpazgr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgvtrid.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nabllekf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2idtmpbvs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxqrlou.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphasgcc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2leyqkvht.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmkcykw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woyuaojm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqbkdvg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqptbrnf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pamddqhd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjwewjk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycldkeaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvyzlb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvmsxgf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2brnfbnrd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsbqrdj.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtrwstn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcakkqz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwytemf.html


<!-- 参考信息 -->