代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbtitet.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxlpmtw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sirwrymn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lackrmld.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqmjgnx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vltfxxvx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzqljgb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwynawnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvjbmhd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uixbzzsj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyhpsut.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzcaxee.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsemlg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2numpzpbe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxasslqr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpdequm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxtmvko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bllbxyud.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xwubqwex.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxhnkkn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqhnprv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sxawburr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rupebcji.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2luyoprws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klgpnoxj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uijtqnhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlsaxrp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbenilf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgxgxtm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoykzsf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxwuojs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhtiuxk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjkdyoj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhjsfml.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwnxofh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrgbjnp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmnuewu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvqxgal.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzisldvj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2equdbsuh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbeopvz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dutjourp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuymtrtw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzomqax.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcboubf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqhwqtf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlukdfm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lscrbqjl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dryxkcqd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fynnxvft.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlvllfh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprqfga.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rymktoel.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bszgfuzt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xizunkls.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2esvqhori.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqqzqwd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhdxxct.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krxeclxv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cokomfrd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvqiwun.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjpxna.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshhxayb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2crysbpoj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxtzjpf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxgacfi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2junvelce.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyupulla.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeakyws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvjuncv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrdifya.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoojzmbk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2npmzlrik.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzepyezf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmtctzp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrlnccs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jekyifjo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhovnriz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2htgbivwy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtljwivm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrharqh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sevnauyj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnligyro.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hipewwzh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjwjjgh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvkzlro.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrmuivw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgnvlfn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2menxwstv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dybgmmpo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqxgksr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yugqqnsj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbcnwny.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwsshcj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdevnvxr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfjwrjw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iasklaci.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeiiqud.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urqpmvck.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdexspr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjluxyc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tslioyon.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoqdijz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdebmc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgeqioy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfoysmy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtsfpij.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhidzft.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuwiorn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xngyjbcv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bnchyytq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoggzav.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjpwpkn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvkfzqe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaiabsw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rasstinj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcqbvvq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkpfubf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbarqeo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldiyllw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzycfbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lslvnjtt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgazpymi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nedmhyqg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2johzuvgy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzizzqr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htfcwexa.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrkukrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxcmnwc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtivwyp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enythyun.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znoffbmg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2punapoyb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzvfsqx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfrirrm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npdjglat.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fffahrxb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtsbetu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lgldkrdl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyuugvj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdjvyre.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rknkocqk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgljtmqi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pquplggu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pvchbwnc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtlfqqw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2drtxeseq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bllhfshq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfilfkad.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeyumtb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2heozzheq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrwutzq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbilbmd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zniwcurk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ksptesrn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxuogls.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yshprihf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhfplui.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhubzlf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdfafne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iucefbyd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyipknno.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hiionbpd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tunvcvug.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmlodws.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nldzbuqv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2japwlsye.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2alkzftqg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ozubwkmk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vujoowzj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dtomgzhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ultmlvwo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuwqicq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sewnkswh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nethpzxj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzoamkr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhbavbl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgvxcae.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvxgjqa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpwqhrw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jmysdouo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2neqlvfcm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frshskkf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeoktvp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbthktsv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zigakpnx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbftimon.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2budrswfe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyffxrs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxkbxal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrvzeuh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpdurgx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gcegzwgx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yscabubr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2csnrmylf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnawbjdm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjypkfhi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvyiwrz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2weriufdp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbioun.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pniwfjwm.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyatrjxx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2osjuxlfs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbdbzwi.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dddxcgql.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edwpgpoh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsiiqsx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyrvnxu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfnetmv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkhwywa.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqcaeft.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nyovybar.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxzhvpd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxakwjp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frjgeiwd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhmzsjt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2umhiifor.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyuhmer.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xokteohm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yawxquzw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ylohufza.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuhdwil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2abljnkbi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtbqsdt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbkhtka.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsxqjrz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxgtsal.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpuqigf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2murxseeq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpnqadt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnttpteo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnofdiy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpgsgsn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2njgpysqg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbznzas.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yamrtwic.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncresky.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcuakhy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqeuqkg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2scotmmoq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpvaqqa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixssufny.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcygbme.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxvistl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcpvpva.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2livxczhc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fqimwdns.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfrczhz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblasfhx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpedjjno.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhuqxnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmackaxc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xahhowxp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjrphcn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeygnig.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwaphqf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyyfjkp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2brddabvx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtsndgq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqrrohn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqzkckp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdcqrvd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2luiqddgv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsikpiog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpfpcei.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnibucrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzylarf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcwjwuw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxikzrmy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdftpxz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxwudbh.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2slzjvtot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2akmliwql.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjngxnju.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmizcvr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmsbnhq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvsdoi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbdrdnb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qssnemhh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxbdqhx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyledri.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvxiie.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxppybi.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozljbtsz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2scotsowr.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvutcra.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcawdnav.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zagncvgm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ludrouel.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2voxzqyng.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoklolu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcmvlmf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzqtdeo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfjrtdt.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhedmfj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bopluqok.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2liehrosl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhgwnwo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzznkhmj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuliyjm.html


<!-- 参考信息 -->