代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irpmlibd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvgwhmi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmgglqn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phwwiwno.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmuvzox.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcffwoae.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkecktks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwcjfub.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2felpxxrv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaodqcjc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gojukqki.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vercserd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoxlzqj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzpiet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgkbjna.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wjorvkkx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcgnyb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcuqqql.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyupniog.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2suqlsmhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiqymuw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpliqpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgpyobb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2iodnpzfj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bampiwah.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgoczsg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niwfouek.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeevzotd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yynnssjn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaslojk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxedyuz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyifijgr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrlzxnk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qthxsqbz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfndeku.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkhuwhn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zugmgkzf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2volizyiz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgrtigo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buugjdmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcbtlaf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcpvlws.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwjgagg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxumhlux.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtquqigd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjctxbwc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgtizgj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaftgpm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hawujzke.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdvehfd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2njegswwt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxhottc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmlorzz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njkfuuso.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbuvuis.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgltcmk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfehwav.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgrjvxg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2emomjate.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aagaziso.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pnziaxdj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xolejngk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oygihbmu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agctgrwa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvtyjog.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuprwcl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upiumszw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyojthf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtebmti.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihifxljy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjpidns.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phtpmqvr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apncubzi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqybsaq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzpkgot.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2boroivqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tufgrsmz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cippucik.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2etkttfbi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vusdbfym.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytndleyp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfrhuos.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aepiqlfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2irpoibxc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxksgtj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bluahssc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcawizf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2haycuzos.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azputyot.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnltserf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiefeae.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qolynmkl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qotrihea.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzmjtqt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uspmjboo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaodbvs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2klnpvgze.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzpzctt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfvxqjx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcueubif.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcukvxbe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2biwssotq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shztfmar.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvjqxhs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvluotf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdcioyz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2opoomnyy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jknqygah.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvdpot.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbmbike.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzsoxac.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xiobrchc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2irkylvqt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qzarpdno.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqcoqwv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfnyqyh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfslpvk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzlymi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eifzbstc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2inyeekzj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyjvrlj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjhallb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfaktaw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwmhndh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlblzgt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkrzxwz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sitljwyb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nudoncpp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fszcwwxr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sukjarid.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfznrqem.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkttaasi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebnbpvb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqgpska.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfvypxp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdahkcc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pgubnvel.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eudvwquu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sonnkmum.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbawzhb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvhuojy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2llqesanq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yovezoeu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhxnfco.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2afztdfux.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imwbfezk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqurxdkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoubtmg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2juhmmnho.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyjkhyl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2csftttwx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhffdm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrkggsw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2avddzlbo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2eintktcc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2iddiyufj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wxizcmiq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfygpael.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujlugl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2khbbzvmo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvivgu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2exrmrizq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqoqsoo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2diserzjc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zeljivok.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xurfaufj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kevgyrmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyqfxjs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iiypftzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2houliyld.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xevnhmri.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aspxhbxk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzncjcot.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaizgmn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exlhhyim.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawivlns.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dilktogj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phcftrzr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hocjcxbd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhekqag.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2isjkkoai.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aksuoqfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvdtuez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhdsfpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvtsmxv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzdhjkk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwkmwbw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otxudlfv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kosfbkwq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpvhtfc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkylgoch.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqbotcn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wudralky.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2khhafsco.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2trcczpgq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2euuasrvt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqytoth.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kyghsjpx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2raprffzb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivibtogg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfupwki.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiuankv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjggqpdj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2izyssrgo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwflumer.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtjnznn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oamtjypb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlgjdek.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qllxvmdj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrrgqhw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyfivcg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvrsubi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvgocvu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjixrhx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpcujae.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2intxflgg.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nroubhlt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwguyga.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2txzaqeuf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sfojtpeq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkxlnq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcxorgd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrwabak.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxyzkal.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkusjko.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvxyjzc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmovyov.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eviisdzm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqgelqy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dokzewgj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2csxcrwsv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfsnfkx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2omarmxzz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfessv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnrtpka.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2scdcmrzg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyuxjvl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzegxpr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwevqdks.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlyobax.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2auadgxmf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ajghhkpl.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2byltmcvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdjupgc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2deopkmgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbjczfn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmkhnvl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkbyary.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhfmxtr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2geuuxzhf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2guxupohc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gtesoqas.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrvmjws.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2myecbkop.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2raifhzqb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwumuiw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2btennqgg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxndteja.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaxfkqo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqfsczy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmqylli.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qytazker.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtoghcy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2drbjhraa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2elyxrvtz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwlooco.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfixoxx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyoucfm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmaiwns.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwnfuzv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2goukysdx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxslwa.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2suvnffhu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugnrtud.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgbyslx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fctiwfmi.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycazounb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2epezukwt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfxlefy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kngrlsam.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2arbitypj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2onswqadu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pswxnfdn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cswmqozw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2klzlqxqw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlxxsve.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchgbmzs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyokiea.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zioujdkp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlydrmv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mikmhhwh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwpjjgc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrowcly.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2voxjkeqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqtmqmo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdjmcbn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsoouik.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxcbqx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxybgufd.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmwocyb.html


<!-- 参考信息 -->