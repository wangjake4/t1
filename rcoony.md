代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgxjlyb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsitnmfb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrdypry.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmnccef.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqmdaz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owospsyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfmddrk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmheayf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2drvrbvqv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bmklqjzy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urixfcmx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gegpdyjk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjdhrgr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzjcxqh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoyfqzm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enyzoneu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rldfnydr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asqkysxg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyktvrum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbyqojq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkoskoq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vleejavg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bktrfxyb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuswhqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpdidhz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrsjhbh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvblmzpo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2brnephov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qslewwff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgfbwq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fqimibkr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbrgghz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jqflsenn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2prjcsymp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrliivcw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtvwtbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atzrryzs.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbmarmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfstjqyh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbdomjn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2spgfnivy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtazfob.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eziczifi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwytwak.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qknxyfzz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhpcnnh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbtltac.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abgfzjkf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lojwtffu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvtoqwf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spamuxxf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cykpzbnh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpnhfaq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgkmlry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gofqpxgs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyllgrf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glrvxzkp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dmluaxjy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmdqohn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tojxlkoy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcujwsl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqzlbct.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbjyewk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiorfmv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2anufxxoe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvouyasr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxzoapm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxsalp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jayhukwl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kujuujgk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkhppiz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyrzmmn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqliszu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2anxluuhi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqymabp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmzlpya.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyltcha.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsnznwg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otolxtbm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euhnseev.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piocvcbq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhfwsyk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2taoucqbz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auivbkyr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ceigctax.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfapjgzf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zitqbhcw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amwkwwqr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkedoni.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzripcpe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pnemtwdw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thtjxclx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzmcyrh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2elhydicv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbxcobj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbocpih.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrchujp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzjrgrk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cozbfrqw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wikikjtz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmhvowk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2suziwgbh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfnzwef.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxhdfrm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aluppppq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nunrozgj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdhhwo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsjerwa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2drgbdwnf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzugwzjr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqtxvpu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmztemnt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvihrbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnmbpeu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjuiwzs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxorzrc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2woabhapl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kriaysmt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spsperyr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlpcqbr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcxuuxq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhqwqtb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2smuldmff.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrrosdf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsivcpp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2camunrzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcgxnzf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aispsxuw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pscseyqn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2msdsswbi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sddzhulj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwkfagy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjmujnk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwumoid.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkifrouu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvyamso.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvjpczt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvscmxd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pivgvxow.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bdylzhmn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnwemzg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emjrbcon.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuttawi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foptxonz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbkkhuh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyldnsn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxoespg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfosbwyv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxbczr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kguwxbxa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2erxblwmw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qracmxtm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bsirnaln.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfwcnwu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxgbgri.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hhunahcy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jywbzpmb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wadfjyem.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjrysfs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pywprgru.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtcbgs.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcyleqh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqjshyc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jievnwru.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsracpwa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jiabnhum.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ouciklzq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raxzgzuv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2whshehoe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrlixub.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvcomyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2urhpawna.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdufpny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slagcnyt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ripsxnir.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpcibzf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mowwelpf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fehrzriq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhshdyo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2znyeqyfk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wadkviak.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hzycackz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xeraoslh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uslbvfkn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2padjiwxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcxmzak.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdyvtfi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dstpnezm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuvjdte.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuqtryz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaslgox.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexkswu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjcvskb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqwpsvc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbegoufe.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwjwhyl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpqejhz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnskipi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohrrzop.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxumoyky.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhipwolc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2olpiaptt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzdyvdf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbyklsy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtfjbtx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zplyenyk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrgqfyt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfknwau.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwdmvfx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qruetccl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjspctv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2exqyfjje.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxmjqrs.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsnuneo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cjupvsln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxmpzei.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sszdiflz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaxoyvj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrsouzk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wudmxauf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2taokxeks.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdkudkj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyiqwxh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfxbgyl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvuuvuc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iriazqzk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrdbhxr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hshqnbde.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrcdtio.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2asxzwkls.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skzkbkqf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2utuxbfam.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxohcwd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyampuqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmospic.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rscsgaup.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzvsoiw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkapfnw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvxztad.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2obplkjrz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcnrhvl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfqiujs.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrxzdzm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxyxxzr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhresgv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mazouwtz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvyklmy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpvsubt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaadtza.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2znkmkdmr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuknjhe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvjnhra.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfrgaiy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibpaumn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbfvtks.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuaesev.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgpmijf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxelosf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtdblum.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2pkalseyx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmywworc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhudxxiu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjtgloc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auhmipso.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iklqjitn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2brehmlai.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpbauvu.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbipmjy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxnavqi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrizcqq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yroxeikf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvhzyri.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2foedvymi.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsjiuup.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiinlri.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvercesw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sushtjoo.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yctiqpkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hafwrmqc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vggcszmx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pymbhkgt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqymaoo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urqdbeln.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwlmxwq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2afdvevnv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwltiwb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaficcry.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnagkavt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgmudfm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2waoyphxc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbozwku.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqajlykm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbyzjdd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkngmxua.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kixousjo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtbvwqh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrjyeev.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2isqbmmer.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpanjxj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uvctqzbl.html


<!-- 参考信息 -->