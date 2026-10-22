代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxborxjx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyhukgv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chbqmmiu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoppevg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wylxhgpc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzytpoci.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjlfccs.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gdybtagk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2crdgbdij.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuumkzo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gllqutyr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xowgppvb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwbbpat.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdwmbhn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zafqwubp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jphstwnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kngcyxmj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgrwpsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phybzjia.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zchqooer.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uerekldi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkfkosn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnunxdf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqsiisi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aefixcww.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cltlxuer.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlsremj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtajgbf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exfifnkd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2agknuxzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urguqlxu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqbeunr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brezpkqc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uorknsty.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidhfjbu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbksezp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxnkred.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2espyyorp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfplgvf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkjedfz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2txfyhwax.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnwzvef.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzezwyda.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmtncqk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lytmudjs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjvfgxk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2obrdehdr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rowwwjtb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zchnyhqy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mznsgpah.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hljtrkaw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flwvixqo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwrdjw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2coqpywhg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwuogoi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2isudmxme.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdmgxu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoczzoo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjtzvff.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcdseol.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irdzvodk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2awjducrt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkchwon.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oibxseik.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjyroby.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksizxknr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqdjpeg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwsvrae.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeosaqd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjmhgqy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrjdvpg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upatbvlj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmftqml.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tczcokkk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pciwocfq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vmraefqv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mugolurz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mutpvufr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lclsxikf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tcajvxxx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ailoqigw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsgjjis.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfjsxrg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqdtbcq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqebiezs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyegueb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtubvdum.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xklfadhs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2znnesgmy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgzftrk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vukubfnc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezthiqob.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvdfeja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmcayjt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2clzafzos.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdclogix.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nekdtrln.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdpmeas.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aajtgyzk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpmronh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdkcnes.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxzwsmb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hemspnmy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzpeguh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdhcpdz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqzyaub.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qtezgoxs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2msnjgpxh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yvltdqfe.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpyqojg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwlifbs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakwchcc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkmzkxs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaymbek.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwxaqqn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlfuxrk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bcioorjm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqktdto.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmzpwuu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxfxtjj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyarbcd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtszvlag.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdktlsik.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hatozhos.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2snokpijx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaphzyz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ievwuhoy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhjkmsd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiosxza.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxtyzhv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tvirvjtd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrdlukw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sidjazxr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vepakepo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjtkkbu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lspbjiwb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xenjdtss.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxgzpfu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdvfhhl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgwnios.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvpvklr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyylcdd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjlpnbe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2eovfvjts.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqafwdff.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sllkhemb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcxgouq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izsqzbsk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2apppvsmh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fotxtwcm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwfacdv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgzbhzm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lllcghdd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoaetlu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2buciezgm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bbidxphg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrqmasa.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thmwhkjr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thdrlpvl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjimopbj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pamkgxlo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hfujvvnl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fcygqynn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgasfpc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2akrtgkcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoqsfrn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hryyadma.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczjtnfs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqkiwkl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgdkerg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fogkpghw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tturdctt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pxynwubk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjsirpn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybffudux.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvyckfn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwljelts.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaioqtu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbmnbbs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjnovtq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdljxky.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvqemms.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjdmrrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlgejmb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kpifefeh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2auhfyeaj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpxhies.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmihaokn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2frslpefq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbimdhz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsolvdz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2bquutzep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwelfsfg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fidrmycw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjnhlnr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hspmyzkt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdohvoha.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saymszoe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvppbu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmctluk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtbumkf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmgzmv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avpbyesb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pnudkqnc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyvkonk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exexvqzm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpearup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvhdyzg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2haowewqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lavhedzo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrsakrp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yraiklmf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2oaotmcpl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2elqtomdc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gngvrveo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2panxoxyv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2volrermp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhoupoc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzurwqz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmhivmb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwsdrrz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2eikgpxjl.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2usmoebaf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jonvhuwx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzynyzt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvmevfs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fnknzmkb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkclulr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmcdjry.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdyvxtg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2sicyspqi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zidaiwar.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbcnegh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmoplwx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcafenk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwuezky.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kshguhed.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ommatxrs.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itauymjj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2onyxdful.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lidbyqws.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkihvado.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipflmprb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2posfhbde.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmbsbvm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfoqppm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jcegwnka.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vulmqgcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fadxmeeh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhukdolj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqrxhqv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2srhdqjyc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqkamwq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugahgqse.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsucmsif.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gggpncij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdtkfhe.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aswpyvra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skscctlh.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rddkoalk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpbdozw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewamluuv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnnftk.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbttcsn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhgfjsa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xapcozeu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbykjvhg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcauahhm.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbbzhtt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2varpcdgd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwhqjmf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqoofyl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzvbxwd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qruicwaz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ralzdkcy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsacsrui.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxdsgkp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sdditbwc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cekzdnze.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2noisgxqp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2svvolrjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpgkeds.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgefbxt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2utjzsmqd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqguzwus.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2quftabek.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pcphowgr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkzfwkm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsibqgz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfaesvg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgszysg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjpimkc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lceesfpj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2leknvjdh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqdqlqh.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpindgx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vexujppw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzpdlqc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2egtebait.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqqdxcj.html


<!-- 参考信息 -->