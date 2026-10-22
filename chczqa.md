代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asprtvhr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2umjagdhe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfrnkzt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlftsuv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzopohbg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhhefra.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mayvbuer.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqpbvwt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvoqikc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrxghbt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjmiyax.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uagfslhu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oixcdrlj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2huvbrhzs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvabiumf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2omyfbzcg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwcdiwh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lvraeauy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jjneieio.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueawlidp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehowatli.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugomwkrh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqqnkhe.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfuexlw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2apfjahmn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbvdymi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkffwrnb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2foatqvqa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjwoplw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xawxioar.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cptdjfee.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2plpwgjkq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2opfoywwc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adanuofj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2szrxphlx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2aqezvpii.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fficipsb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvnjhvo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fltulfnt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjegcdsg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2weeqsksa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjuevgm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhsnfnb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2raecdpaa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdcvnhs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtpmoee.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2icvzxetv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdjncup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obpworyz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvckpku.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cejvzzac.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkbainy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxjzpui.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlyvewh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsctimx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxaisiy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhanxut.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnejryuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2csthblrn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nkffjgll.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2raoyxnxx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mriaxaam.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrlgphu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpfxifw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwavaxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbasaoe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oawmfaze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wgruqtpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjcjqcq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ucehzgtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kexlufdy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2iseujtau.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aftsbdep.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmuhwfh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzbnsee.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmlaqyl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaqeqxz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2klpeqpuf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjckfnek.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsatlrzb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ualgqhil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfmczak.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqfdvza.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwkolyv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihytyrrk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wagirfwt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2btarexle.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2muchgaps.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aolvudcr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rqconnso.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdrbbqc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwirqskm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixreggcg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2goiryuoq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsotprt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2haykpggz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2djivkinl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiajgip.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbfhlfg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxyhltf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxajpmn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfafeyih.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzerhsg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tefawjgj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwcnqjr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iriwtrlr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhincia.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2acoazqbd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lztcywxh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuacrfrc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xorhxamd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbhjmhw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syqmxpte.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhfwgmz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmkdbvz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhotkle.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vguclhkc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmcqfwa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eahkmkis.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crgnnrta.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szcvppmk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqoigk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2suvbizhk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jeobghhq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpqsgwy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvyprur.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjcsdzw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoquavgt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lejxykfp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcexudsu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkrmiri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bndkvydv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hbujnkxg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiroxin.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbwvklw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwfguvb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plzoywcj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyjfpky.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjvwlum.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npfcxibs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqyqwzx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqrbxro.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcasacbc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2glrirjiu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vavqkgii.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lknbwjbk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xorghwqi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqwovvq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iccoqnon.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2waozxuua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgoqwzn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbmppcy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkulhqq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqziymsf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzlqwnt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfskymq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgyuysx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgtxatm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pzupmuhx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvfrujy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pkprpjlc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rcngtzib.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdxyddp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxjrxxy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrvdloj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erzhdoae.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdfrrgh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qivmwrcl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjihkbq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwapzktl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxlubwh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lomtsqzi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efmsflzf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fciirtqr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzpqsbo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrmgavb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwhcwfn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkhtlul.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcyesko.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aidpzefi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2goterglf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fccjnkqm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxemvla.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwkhwep.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2keohqkrj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgnsory.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2avfpqkzm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hkipcozd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2clkxrszr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lksltpzy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2twgnncgf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpshilw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxervfs.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaiwqnk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryavyzey.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ybknesbg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihhbcwf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vvetrmnf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zhddmbjk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goeaqcrt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtkeomr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2unpconij.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2trkyezuf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jykadlsb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2aamvmhzw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiycqhj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2provbwou.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2plqchkyt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2amfecvjh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtlnmyj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwntgro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvllisr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xirhkcyi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqaxcwy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2whlqfinl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lirpwtpf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2prvcnpqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbylwkrh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xgboqonm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwgtizp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydetuvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzmqsso.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uishlapf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnjjipc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fthjnepb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjecwjjc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfzlqol.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvemapn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bidlagjc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfoayhx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycmpbcp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrldsqgj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqqstrm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrmadbg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srchzcez.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwbbxli.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxaauml.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcnnaxv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtmhkdi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwjdbmu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgutqef.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmkbiqs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgonkdj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmomffte.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjgosyb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqttcojr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoaxlqn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kthkdkoz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwmxmzx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tckhfpbt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuanuqje.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2erbarcln.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pahexiiy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuywgurp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbnucqo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2icgjydks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2todfylkt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnhdypm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkywdrgd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npsuvhkp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrcjztc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvazdal.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhuenc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgfhfow.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2gugpanju.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2viqsgdpi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qmckdixm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jdijmdkq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2eshyehqv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wciqjpub.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2csznlowv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2npgmxicw.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2widzbndi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrkmgca.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzhkctl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkrhknm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqwhfof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhofbtgp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkcdkku.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbpeezb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqldvrmj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgzxemw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgaqkql.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2njtnlmry.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zjexxife.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyiinsj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2shpthfjm.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2arhiqbbc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zncwqpsu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mhthqiem.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oeauvsyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmzvetv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gltlffoq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2bimkolvy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoyldbz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmmkuyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wpexrxca.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxpxezc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hetydedc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fttviaxu.html


<!-- 参考信息 -->