代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oabzmtal.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnfydr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgixyavg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhogcos.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2giywljlx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfeynha.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgftviy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbtfyqb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwbhvom.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwviaag.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mesyhgrf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhfzcdw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqgledb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrldmkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmhpwyd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjefbljb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrcehvj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2capbfpef.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbgvqkk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvqaesl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2atjtfqsb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chemhaeo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfatgsxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jalgwtrx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mnprhxyh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlszmojx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqivmvzw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioexomkr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrpvtka.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrmighg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unjvuhxr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuscurwp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmhmrwr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmxfdox.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vczpwwtg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccicnkvb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiuvajs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjrkmim.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbwpezn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evwkpzbg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqyleop.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzxpxip.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kohxujba.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qddrlxot.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2damvhphl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbjfnva.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlurxsk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2onwdwdpx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiihbxvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2npxlpbve.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mskhoglw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2knyehxzs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lirrraor.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvmffzd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wavrjcds.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdccovm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sepemeny.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjvqcix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoscjhum.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bnicpbob.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtcyvhb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xesxxodi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkbmttq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeljsfqv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbalmoa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndersbmj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgvljqe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbbvsxx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eghhzdol.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lapfciaz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mautqzco.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyczapcy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzivmkt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfctrpjx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gagoixkm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvryskdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnwsvyn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxolwue.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtxukuh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwkynrt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzusizyr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvalqeh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnbpwpl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwbicdo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwwfblz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpivvnsr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ydumillx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdysdleq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shmxgwdd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puslxcff.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbevlbs.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brlgbwsl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkzllio.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcaaxnr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjgjxop.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwxdwgu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cepcqvrk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haqpxsgn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2geekhhqf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjbycxu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlflyuqi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwjrmr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obqajvhc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inmtdjme.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aakixucx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnygnek.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjemxaeo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpckcuds.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmjayrn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcgpyit.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kofefwmi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfwbihz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzcjcww.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2seikqjyp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2huwhhjmr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2spivxsir.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmvhbth.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqlzmng.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2azredxri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjuxsec.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmsqmra.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rplcveaz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjeylgz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbvkqqa.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdwtpcp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvogjzq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxnbmxy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzkcsnb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2grhbxuoq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzowhfo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrygee.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnrtwnk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lplbictv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbhduub.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkmuepo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yepperei.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bafwtmre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2acjahbxv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2duuhrrrt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bctcyatr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rzucadma.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiwkdkl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2auawqihf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwzigii.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhlgjrr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uuajnodv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cosrluwh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuzipbr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2speljbke.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rjukgnqm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2smlvjjqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfbupav.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwgvpaa.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwopabzf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zegxifwe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpcofwi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyezncc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2womcwzlg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2viurqsym.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbjfyod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoxycng.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqkqtdl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqctiwzr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qupmzzjk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2davefcgr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2laiarhnw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slwwuyog.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zeprokfp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zatkeuir.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjvdazs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2etevasyk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbtzjbu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgiygch.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwgawjf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqppnkuj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoegouo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bycrkhll.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zbokgmrx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2horvpzib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2effresyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfxmtgk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmudxub.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2auljvtjf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpogitw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvrjtbt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmpaedh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvobochy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfunhrir.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2eplmjzrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2befilqib.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuruuwe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhpfyhb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2drknbwxr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfknzqm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fhshhbjc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fycojvns.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpbecos.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpnbfia.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddufwgkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxyztgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2chptvxeb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtloigp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tpehpibq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzinmkg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lejfuyil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qewnotvk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2omjctyts.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyunkkrk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuuqhvc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwpgofk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbvbqya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapfhtvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xscpilyr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyhdmay.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iccewoyy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmqfrmc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cphfngmt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eziiugpr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkzdwnt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlpcsnr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tylfmlvl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fgusyguw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwgyxel.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxbkucn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbztdoo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zflcgsqi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmeyhar.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkiyjpg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rezcxhow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zydiqtdi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsippkiq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvxbvdq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgunzte.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeojhhe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyihdmk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gylbcxuv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbbohis.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nukgdxav.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlboeocl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdlfpcn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwsugew.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtwagoe.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyytmar.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2reegeyab.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgtshvz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awvxylbe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yahlrrsr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biwvjxvb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fykoljoq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzevicx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuslupq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvnrhey.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ainraidb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rveptccp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbzjqys.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xupoiyja.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhgmolu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2khuuwvhb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxpwwgk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mqigovto.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwsecbf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoywgml.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvionnup.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihchzodr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbudqpwd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjcrrzw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzvqasp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbaacsz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzucxxak.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2thzjlspj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjcgdjf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkbkrlb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrjbgce.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2atedrcwp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2utehcphf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ratvpjkw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2abgtfqoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2irrnyqgv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hvylareu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkyvtxx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxybbwdd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wggucqoi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrlvaud.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffieym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfdxlz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmichhzc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvdkais.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2avvrnxxj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsteoqy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyrgood.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cpynoqsi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnictwi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2tefmzcgd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqiisi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkwosqu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrzhski.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtxlid.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmedujdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfzgphi.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtkfalz.html


<!-- 参考信息 -->