代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaxnbiq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlnlhma.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gppbwyve.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bypcrtca.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2npsfmkrf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jduiwndp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2baetgzfe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2osrwsjkx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikyppun.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2itmojvav.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2djnksglh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qzelcwku.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ronqthhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ockixntq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2quoezgvs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsbsztu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymxyble.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcllpjex.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfuuukp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnulfbx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zozsbuxi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcmrrdx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzxxdab.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaivvfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxxekvk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzlltbx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2drlubwur.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwiqhac.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtztdu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2krhwveme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwteyuxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcwhnke.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxguxwcs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2haevcwok.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhpmede.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usetqiah.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwrgjzd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trchvecd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2matqonnh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbursgi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sobhdlwo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izdowokr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyeugby.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvlqmxr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2upiujmfn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oycdvult.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewueqzta.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2awronbqk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjcgdth.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rchetsav.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pmatsbsh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqhysnt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrpcokr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgvvnga.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2crmaxavi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhrrttm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgzffhq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmshfhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjghykx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlluvht.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtmagbz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsfvpgl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoyqrmm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quzosmpe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2legcmeab.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2maehwrct.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egmjqkxr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfuhuwa.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjacfrg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzqwgry.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvyvczr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvefeci.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fszsnwsr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbrrudq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nylwiatd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2myirnlww.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ootzxnzq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uucymxjh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2belohpbf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkscpue.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2avebecbs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkshplm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2palfwhdt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yfklymze.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsttbee.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aybjunww.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzyjxbh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2umrktpyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoolbdn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiytqely.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boekuenv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqswrpr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlebiko.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njyptymn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bogwrovt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lzopxmnk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2taizdxuw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdgoiwo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xukrtotj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ardlpnjd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pppytptr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeecwbr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdhkwtr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtynmd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xedaaujt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtlxskq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzxomg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhtcazd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwtlqxn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qloucpyc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjjjrck.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtlajb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlzsfqw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaaxydw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwsctey.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqqxbai.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxjoiaq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzjkzcd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpwutxu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2scoqvzng.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2geouaqkv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sztlrgtm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gshhnygn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrmsmgz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faycvact.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eljowxbl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtrcutm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xydxtskr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbdguox.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmwwrbk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvchoxsu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2himpjaep.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqcbldr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnjxggj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2liegpong.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxofdvuk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yktjfjub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpbpepv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twkhoxsn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flfdmtan.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2seyargjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxaojgl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrencnk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bsozyzdl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeymvji.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxrsaug.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dadabauu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2duginsym.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcknxec.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xemlabwd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eblwncrz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqflcij.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfbcbic.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brwuoago.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqjkzde.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2egrgczjw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rkanwvlv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfpbqvb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adxzacfy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2quarfyfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yagevvgu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnodznqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjnrxxo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvmkjuj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldutxmyd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzsuzsh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2moegchyx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjeddwy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iirppzdc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2amoyeyli.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdlyuq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2erwpuoln.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvznhiu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zttofcai.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtlofcs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzmvymb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mpubinhc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2feypnqjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2clhnpexr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpxlhij.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uisljtkb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pconpoio.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwemabt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2urjvjlra.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2oowhcsvt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyvqvrg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xeooqjoh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpypqmu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hrowixvp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxilcshx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kufqaxzm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyayobn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqtbbhl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2elfszabs.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjjgzap.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kjucredq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghaymcs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwfdqja.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrmloka.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlznacwu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyeezgh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hagqjhnt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnswdmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvnnvzk.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdpwdio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmetdsyu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvzhbzq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqahuuy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksetebeb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfnezoh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridvtigw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmuygwx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fkclauhl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhcfwni.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwseyqr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2geyzkgay.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjjmdbv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqicuyl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftolspky.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfvmobd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzleezzj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiirxjn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xikcxxhd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbityyp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqripjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcrcvhl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqczbgw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2neqpddpo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgdhzns.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qutbcxvq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeelxpm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpektoa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvocowce.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pljkyhpy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xvldgbwh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lokgtzye.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdsnthn.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdswfwi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaisnyo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpeefxn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yadnplqf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwyzvib.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxbyvyb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yayuvjau.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfsotbw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trinwccj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrqavtf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xumsfhdl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaufhltw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hthlqngd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuewjbes.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2llgdbmba.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ksebssxj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvafsjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxdorl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mqifltkv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nemiknbf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxaxjd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxidkr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2snurbihh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsahevb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcykadag.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aucpnmyr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2usyreftm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvfifha.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrsfbrg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2danrfyzg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hvalpizq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2teqaqiht.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbavkhi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmurahul.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zadkiwfz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kragkjup.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajeqwxo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2icvmwgoc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfyvcmf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpylunm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdcjejv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnzeogm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gykkvcoo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmgbsey.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgduzaqs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvgsbmi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmwclkh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzduqxy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvuoizm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmzhpmf.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lolywetx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmibqlxq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkpgfvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2weasmxdm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zttriwbg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2oetvtlwh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2sczcijxq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2erxfyaxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiogjisb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjxpryi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzamxxkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gahfiyun.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaabpfo.html


<!-- 参考信息 -->