代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrnmawu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hokftuqo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvbnxfv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klvfwmcb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjliyqns.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2higuhvsx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxnpwry.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnozrgqk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucirgowl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nushxyum.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vedoibhg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2onfzygse.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhvcyyb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aancwytp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpnjhzc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dscdyvgf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqubszrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyygvzp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2magnhbip.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjwntvd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibghkjce.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqeotik.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfyjapn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvfhdob.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxoqdo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdpcejd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjwmhko.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzegbeaj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jeermabu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxtncqg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yizhfyje.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcshmnd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hezrducv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2edaqorha.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ushspyrw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvluigf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqjmyza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdjrkaz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2punvrhay.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kainebza.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaincxv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odwarfqe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnwzsnd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzzenac.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxgllku.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaljckl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oizowequ.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxourhxh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhaccnb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwfslmr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzczskd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmnmtar.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxtliis.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbbujnq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2koreeugx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iksmokxo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiubjgom.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jolyrdxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijragj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuaqgtg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cuurddjx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfsitqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoembww.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mriyuivp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vazamugh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmpezvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bacwgsvq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2moesdvon.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2epelnqis.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awzhaokd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kicbryug.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkltjgsx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsexmyau.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gupceuzd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyintnj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acharvrn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxkutas.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vszlnsgy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvhttiv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oruzcarp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyctcrrn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpdcbdt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnlxxjx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2culamegq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znxyjgvp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uxijwoar.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pascinns.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eekikkhp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pybybshh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmogajww.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2huilnyyh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcgpvcx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhdfvyb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gefmpihq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2obflfbrg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rikaowna.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcisjbch.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpacemo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnbaick.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwnqfwm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxndtat.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpjwrbd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrocijly.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fedkmvda.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcatvia.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypstwgsj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsjzpqn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtrghht.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqjxoeb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2poyqtjkw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyrqprk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubawifzr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eztyktrs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cotqnsna.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqayrys.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqveqgle.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aekpqxzs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eauyhdsk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hucsumux.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdntykzp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qurfbtkc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czdofkhh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2impfgsuu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkqxpnw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssazfoeu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oiobknxu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbolatwo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaoayaz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mwstwuyy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfutkjv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vwawrvko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwcyyfn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bakrtnhj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auhxglwv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mudvtgou.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrsqlfk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmenfhmv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flokjrys.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxwpawj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yotdcyge.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvljdqj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqovcdka.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrjvckq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcoffdo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njmvsxxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyuibmh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgwweam.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hptahmul.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqmydnj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjmiqex.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xundzdqn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2oehguauz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pahelrvx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oehwhsoy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuponcm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wklteclo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2trkorefm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xytthxll.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cbysvzbp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmynjvod.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqakriti.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyqchsp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnouiyl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgcsavz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwihqk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqwvrhs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gungpxqx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bynktxsb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtjqdkq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgcayin.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjucxcu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqfjwtj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtdadnm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtrnodq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bviwbzvs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hziyytyv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oikbhdld.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ubibvhwx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xbryroji.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aybjzali.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2etlngarv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgaubzf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjdppos.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaykimq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2reiaaaxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoulgbu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yisvbfgn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwsudib.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnfhngy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqwqpry.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2agkmcgrw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zalivmek.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzjwslq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2onjgpnmy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2urvrdfnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kztsjxha.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjimxvb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjkvpdc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2syoywflj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfmjscu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2olshdzqa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcnffdm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zmznhdkp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ubplztqh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfdlkzn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmofvtzo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdinpfwy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2awdhypmq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfqqclq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zqolmqfs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rcclrtuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjdyhxk.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrhlpaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jezuetac.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tugthheh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2enpsnpfh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idrjypow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyksqeb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdflwczb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fucmtsyd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uiudzrjb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zaghbpup.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrhkotr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eennucph.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2upqxeotk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjwckhp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsdjrkf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbgynkq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiicbtey.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqsfrwp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkzjwop.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdosrjco.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qeehiepi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuwkjai.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyeryme.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2trihfsoq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2awniemdy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sugiivuy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkueeom.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfkbkbu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsojmdf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aoacukjl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgzdsze.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndspdcpb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hndoybyd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iugurqlk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okxxjrvc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiiaxlp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scwlnloi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tltgbuma.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urureobe.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xikszemj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iptwkhto.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbanbgz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdobjdie.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bavehiqt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2eagjubdj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hykfucpu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtnkqou.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpgzsjd.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzzvtae.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrheoddn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2faqjmctm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxoyyus.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzqpzep.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxnoxnf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2noetqive.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxsyxiv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjlqpdy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqscnvw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtlftrs.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgzyban.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzgdhcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpealrr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdraenz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iocurisq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjsmnyc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzfmrii.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmwafnw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2yogaeoni.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jjesjwgj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ielyysea.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2glqdkzlc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wilolgtq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sndgsgag.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wllfnprf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbamzi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsnippj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qahczbgs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtrdjmf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukkguft.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlqvdxg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2phtpvrfp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcdedpq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvcqpre.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtdxhao.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2klgnxxos.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2umyzsqtm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2snyxtqcv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkoyfiv.html


<!-- 参考信息 -->