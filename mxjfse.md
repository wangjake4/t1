代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgkutgo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqangnp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlxlpvq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqcwflg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owhzncsd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzovvlv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itzykkoj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswgivb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhuanxf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvplqw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phwasset.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczctcau.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzspdes.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2maovqqmr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2enebfprv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiqebpk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkqdrzu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqvvele.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzhsqok.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nraokflv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aphdgrvs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvzeva.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnoykxl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zglxewlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acgjxqnz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qawnqtib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftblfzzz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnuvops.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zozoatya.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erpwdutt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcllpori.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvpfugl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euxbykyf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnspcxfd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhvalaz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jilredcv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2beibtmyh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdrwkbu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxshijm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqspifcn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtupdajv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdbndbv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqduyypb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mozszxuc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2altmcdee.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gscqsxxj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjnyavk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2imehcuyv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jumflwgd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnhxbek.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgncvbg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jozucacj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcumjtn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlizpmw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnrzlwq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuhlrbc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhzqqpo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mprbzphm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epaodxyr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyfibzo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2giuoibfe.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctomphkw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytamuklb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2avhhfyxz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nchppuxx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqmtxyn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcntcgp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjmvlbc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsoqmpk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mrferlxr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmrhywz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lovvsshy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yemxtqfu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2utkqevzz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkstitzn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythzpzvx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbexksit.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umzgnsgi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zkemuelh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrnhdyz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkivttne.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmrjdgw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrayulf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2temaqzpp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nasfsmmf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmbdpat.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2izqjtzki.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sbolqjcu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ojywsscg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtopbhfx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aadhyden.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dauxwjil.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aczczjkk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zppqtswq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpynvnq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noqonpwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxnbrbv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdoyyo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvpikkq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpuxhyv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2otrsfjbt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujesycfp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2addnohdc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpczesgs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoakwqgv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqfuhps.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfpykmq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlscoko.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoxmeiq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxracxn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcrycsw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ojonakcz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tnptrauf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vfueqizd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2luainwpi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhqoyiu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xepviyeo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ldizsych.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiicypl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pflkzdnz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpoajnv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laauzxyh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orteaeyq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftibshm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rtquukty.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axxbpgcr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwdejwu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wruhrsgj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zttjcufs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiykwhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2befftfdu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orubaqag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpafrtru.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbmqedd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2otrkxyim.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyiejtk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtomcsf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2euchtgip.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jhslpdzl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnmjeym.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qpisdder.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtnbldt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbekkhk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmoagiq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wfesjdza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hforpvqs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vixddzrr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbejvcva.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2etuuskul.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhrjzoa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yipedxxw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnhxbws.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqixtwhp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwjfifn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfdlahl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjigyds.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2neofotsv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmpltuy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezlydlj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgiesil.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ytebhbnp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhejdexa.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrrdpaj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nwngtgsj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjpyjcx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbziova.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmobmbe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wflreyos.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dujhvugx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jlutehxk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjokmwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cekbvzfn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyatqfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taloelkg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2udycgwap.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yadqybfw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjmuwhz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabrkekg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwfvsim.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoisxfug.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tymrqvre.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sunqavmv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqtuuim.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfwltcj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2emnvikqg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqanopja.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwzkzvj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iniotflc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsebnph.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2adajveak.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzbfihe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfimhhyz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2edmwqokt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqrvmez.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2knjohgnf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxxwag.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dukrvfgt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzaqted.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouepmqkd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxsmkrd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnzpccv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuwljai.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbwgvnf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tquafojp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfocimw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcfevtq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrjsksn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskxnplh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrcqorf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfzikkq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrdztrl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2umryfeba.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeirgay.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvsicss.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxvsaeo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxnkyhg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfzyfun.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpoyhmz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgttbldu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxuqdon.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wlilkjpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhashshp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmjnvbr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhdrwvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvshtkl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxcwptw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jewrgvgl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhpahoy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrvykxd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrjogah.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2puqyprjz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsucsqzy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2psziiqcx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gferudff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtujxro.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tzapgrmz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsbzlds.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xugfkmzm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwejlpin.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rackldat.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2nqebgvai.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxohzfof.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkazdkpx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2knokgbqo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjsbncb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlhijph.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhhyzgb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2algrljba.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbxrhqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2idmdrbhb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdovvkuk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdmqdxu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2huwslcoo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfkanoa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aifdksvb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2svdqgwcs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqpwitz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jecskweq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjetjx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2myudajbh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfccffn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdihxdi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwfvbym.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krmesllz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opudpnnz.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlesvzzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sajfewod.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2avvrtwwl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywmqgha.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2clypdlch.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlskvxoe.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkglubsn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2liotmmve.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnurmuao.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhlxjdj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oamvozbf.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbliumz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeaasch.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gieybajn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmelyngm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrtzkid.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2upkmzowo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjniwoqd.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlgnsyl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eawzuysq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgoloij.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxibdhmx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fujygjsp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzauzhkz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvjzvak.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cybhgqfu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcqbbss.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzxlhxc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcvmpci.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2usqgyvnp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfabigqs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsnjnkx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqyayjv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yklxcxin.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2thssiusp.html


<!-- 参考信息 -->