代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqlxhdo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dghkkras.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2razcfdkc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnscfeuc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjuupca.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pavlczor.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlovsvte.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kigivcuw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdmscgm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsdmgtz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2txtmhwxv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzkzbyd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrheabb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2svjruckk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbolpctc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfnlzrc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewdfjws.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2snfkaygs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zobmutkl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbuumwz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimwpruk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlolmpqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjviekjv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2icvdxrci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkewnuf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufssenyy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2orayfhla.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwwonod.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaoctns.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tatizewm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpsvqnu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbpxxxq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gghbayvf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjevrtl.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfconqw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2smfdlsvt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrzgnzz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2azoljajx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwvnivs.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpethxe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaryggp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcoyepg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuknxvy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwpevvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjinxqc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqckxkla.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmnzvdo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxfoofp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2feeiqkaq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azowzugt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huvidqfm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdoeygb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoftxst.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrpmwmi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejddezzc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhwjlax.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sziucgiy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrepfap.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2roahgjfd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpedbng.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyyndfp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tdczyssr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cvghwzcd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqacxpr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wfueuvlh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rylesogz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdevxpaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdjkyrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnakznxu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtawcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuikict.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdeecko.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ricxgkwe.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlgiqtr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgpxlzi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfptzfwe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myjmdfcv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwyusrz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxheixsb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcfihzq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvebpt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2brplyljk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udkjciao.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmofdecd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfijiimm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenjlmwv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgmfmgt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrimqfz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeazbgyy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jasysvcq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2llpcgaio.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aoozblcq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2auwuwspv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgptcvlo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxfrost.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hihpvazt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyhpnfx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmqrgre.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2molitzfk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2krvlfihz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhmrszf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvzypmu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuteykl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzpqwu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2apzycmkk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcboaqtk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txcpvwfk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcgmvub.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqxvkoc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szdbdbpj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbourki.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giznjzik.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpboqdh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nymtdocd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpfrdty.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkjhowr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qguocjrs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydukehza.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srtrtdwv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzqhdlf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kivkxgld.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbyirlu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhoewnw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsguqpyb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxknjvtn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaqtrjz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlisbuuo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2papedwio.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjunxvfv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lianftpx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2djzzqvrf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cifqkboy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qzptpvka.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkluyuje.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrykqpq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdwdoek.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xklzhmqg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jalwhhtj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achkgrwt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhksuqbf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nznnvptp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blznvbcb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrsxhul.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeroson.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2poeurdsw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqmiaqv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xicnawwd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcjfwtb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpueohf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfspueam.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdrheaw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsipbmc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwajvki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzdtlqc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2menkmwwa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddabpt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrfwfbb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrhfbyd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qtewzpwc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfpqhur.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqgogil.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wpripjve.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjcxmwn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyexdxv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raunedgi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmitruwx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atmvulqt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pilccfkp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2owygjisw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twkaxajt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yahzsihj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgswllo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldusoyf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhpaorz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaboicv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyywqrw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvrzczl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzuslbk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tampaoyx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2panlhfpe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkyjruf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cbewskam.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fimwfctk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzayium.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzttlav.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvmaxrh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzqvqgp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zscoakma.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaejjde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqndcy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbznvux.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2crtohknq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfohinaa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alresmdx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdyensr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wovchfiu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixujxhw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wghdxrnt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fycyltiu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blvauhmm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yupdwked.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yooozszx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrmsfwh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xamplobu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjptioc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epnkceol.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfktwfw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoimgyg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyyvnrn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nycgzhwi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmkvwgf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyngkyi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhrzivv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxlmuef.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2piuojblz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpvsvjv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhpugnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnoriod.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ungujudr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrbieao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iieissha.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dasjtizs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oocknplp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eualozuf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sffqyrts.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixuvxh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shufxarn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pxisjhkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmccis.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agweiuoj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nncmoxil.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icoxrjpr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqivlwf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxhoqhv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhibulzg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2paispbiv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgnosir.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2awuzbkqf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gidakovg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmryvdy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2augwflvo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2blcnpsic.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoltwxhx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbpqzv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtzjccc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2piwzozkr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcvgszs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgsfqvo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlmwcgv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqezadl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttthpkvx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlcuonu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcetzgqe.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxqqboq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsupmbf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2frnjfilr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcynopki.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaodzie.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjgilj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlckkuz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpgtqrl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2prgfwhmx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyavts.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeppufk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dauglcnk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpsjcwf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvrwfao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yurevjnh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxtsyde.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzhkmda.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufkdhiy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2avipwfdp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ugecewsv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lismukuy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sknrlqbl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yognnyve.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xffqtuuz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrxeihf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2abnzidfs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fkufuhwj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlbluqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tbobwdco.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2owzbsnqw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2avgkbzir.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xfibcyuk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yljzlwlb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqksxus.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2eviujtgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2faskkfcd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tygikpvu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcfgxad.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2epmjqody.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwdoxjm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdshsjcq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhpcaae.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymztwbwy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxszuzt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwyvqtg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oozxcfra.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhsrlve.html


<!-- 参考信息 -->