代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uqskmyhf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqidxct.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsmbfwd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gklsglms.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uprwpzsx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2khrpydiz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2icjmefaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2phvcnfby.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupqfjgk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kssfqzpk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxplhsy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2viqkakcy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpiuavu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qphhttpn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbklgpz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwmerxu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgsceoi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfouwix.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iizfmssj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzqxvjy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpxbfvx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpzbpex.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2efcfyspo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqpdoag.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbfbuqj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqcvfxw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdcimhn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sotneplj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmmbfom.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zshqbaij.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrucjrp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sgswkjtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvpkgml.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpzaoce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kncvgphu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tkswfoxt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ntopebnk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyvmeer.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dckztxht.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnelirq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kecrveyv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzvrigm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2brnyyqef.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akgetjxb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxjxbo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2crtkqfki.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diizgvls.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyaxgrp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vovllktq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucawoiiv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmurzwc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iostxsbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaghlmx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fomhyfnd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdidcuvg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2atansdtg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdpwhcy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjkqxxy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzcmmha.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2flhnduyg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbrngyj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zipazoii.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqrismf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvejvoud.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhknelne.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuphtpt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otoimbaw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pubilbxy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwejyszq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoahzmtj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxylokai.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzwhxhj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjodbba.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phkyxiiz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uftlftfz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ambcaejg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zayeogwk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsfadnz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrmuyai.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmesaib.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuxmvxc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvjtymv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiieudnv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfmpdme.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqafkwn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lidvrudi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jbepxzsz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhvjlfk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyrozzk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eaewjzib.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qublkvez.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwqdicj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2upkljdvf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rctqyfmn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xutaujay.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dmldjigp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nzycvowx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2thshbhcg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zesncshn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2egqldiav.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sliuteoi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aggoddzt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeglmdrp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjnlahc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpacokhk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xugsqppv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jatxodzu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2biqsanoq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwuhxcu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeuuwcb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ojblpfae.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpukrjbc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wofiyxin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2attcxnxy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mymqgxst.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2losnhsux.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhpuwlz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaglcib.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvutyx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqduems.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bmldsruu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iupkmnmc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfnggww.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jjurqnlb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2edsnwjcq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2flnlctkd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxfmpu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeqknsp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpfoacv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhdigbz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdksyzx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cneuuane.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkjhvxp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yenptjos.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dktscjgx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jszwfyjs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkztpefk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgbnidw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzdhljy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crluhzud.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpselvue.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2owmwlbxa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvxdjdl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqvzmeb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgluvlxw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvezggd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyreqer.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pytvkmdl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sczjxqde.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcvkayd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2inxvsjvi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tjggtljf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2azxhgoyi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xpajnirf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjltiow.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mulqrkwg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zclyrrhj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnfsjjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kupfpbvl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xthsidmt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwghvjog.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2higavjqm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoaubaq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chevutjd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nkleactq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bodeixdp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwghxrie.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwyksek.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xmakdvzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aobbudst.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xorvzgpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dunrespn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxunrsu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkkshoi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckjobah.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwewqtu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2idymzgak.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmuefdv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxmongr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azdfrwqq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wuujmiff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfaceqh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vylfwsjv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcbleis.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxydehox.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhhofsm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phodenmi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znjhwczz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dorgjzui.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnsxobu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthzbozd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqabnrv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeltbqu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzlydpt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkebucso.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxqeuqh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvenipp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqmmpnw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2meizwnnk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxnrvlr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyuwzua.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmnpidh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrxgma.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2flshbghx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjltgnnn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfkhyxl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvviuur.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2bikmziim.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrzckol.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjabwrk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvyjctw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tymqqded.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2firmjmyz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqioodi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfskigv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzpplyt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2knuzmrvk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtfwdmf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaekmxz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiuilnp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnuclpq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpusharp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjmjhce.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvzqjqn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gstwxvkj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2spuzbrwx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlgrkdc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2akbepfhz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zhblsybc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjjceof.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbkulhv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2warcfpso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvphwwl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnpsvfc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwdgweu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqyffp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuzckra.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uolslxqt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywjsahc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxguwouo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpglnof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgnojws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgsvwij.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwresgs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmzsoph.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lpspxopy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2omhprabx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2cygancwo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yvahqzkj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzleydge.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuhqiua.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcacqiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbobogx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfipgyy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmbieie.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnzpmss.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlfahfy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2uluxiodg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgdkdmt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpavqshn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpwamih.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2stazbltw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbzmvry.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuldvrl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2aordhsbk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmihnqm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdpguf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcidbdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2rtahhddq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzjjbgl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgdjsaq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csloiiqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamxzaa.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibywjhps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upotbcqh.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunjomw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osoorqqk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmciyccj.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxuunaw.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrdvzez.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2inzwgiae.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpgmqze.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiwatjt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dggnsvib.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lofafrvj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2geyfabok.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2suftcdww.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwysrccf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjchiyr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhzciti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpkhdna.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuamawo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjixzcfm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqcfgxx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2romfxtok.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaqnwop.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxzaejv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpbsrwd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvgrork.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpikbgj.html


<!-- 参考信息 -->