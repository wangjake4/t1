代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgobkzxq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyskoet.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekopssvc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdpqxnp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrwfcnx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuavogjq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzbeqf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uutxhgzl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrknnzo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkdktot.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysklkvfb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kauvofba.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhezvzf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntedthat.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmuynsd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhsxylg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzcrccl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufycedwq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwewjee.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnowetg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vodoiofi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixitmplq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2acisxnsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2drztaqqu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkxzzuo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2upotfnpp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lwblbnog.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkcbfwr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ialqkjdp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2msqcjrjv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gguihdzn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2emavwqsc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2isnwtkux.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfqcecs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uisveesl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2exkffjlj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zokwomvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrgnxzz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueavudsl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzblbja.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yckmgnnw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqxvcie.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxjvltu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eignglwl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2optahnqr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2anlyfmwl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpuqvyi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egdegqls.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qeykxyks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rklipiin.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gajscula.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmazfgqy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsbzkmo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtvzpju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zltteslw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvdjpa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaejrkn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoduapt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvcyqbx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aunkoocg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scrznxmm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsedafe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vietlaiv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2heiawyoo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kghcvbjc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxlxioo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbbgerj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lblkxpri.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mouvzbmy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2svzyfiyf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gruvapxt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2judepikv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgxncxa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2znoxwqjp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeknzxd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hjksjwqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxrvyxc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qulzzrue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qylfudtr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmycucs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zooutybf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqlwcac.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsabmmet.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwfvemc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoxzzif.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfycjes.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewknokuh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrcyykr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2catzmgxt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdyrtxl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eznrkyyz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgtpamo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voyoehgc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afqiofbn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcrntbn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dffxeixh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnktfi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lavwizhr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmosephj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnhjsg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiserqy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwcitkv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtfsnrv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hllviaqy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wosyxuxz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiahqhi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdfvjrz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpxdmdy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dplwoyhn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iplnxhhf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csegdxog.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdhcttc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtlpbhk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2huwrvkxr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhiwicc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2udzknmig.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zakbpgff.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxayxdk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quicdiks.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wygqyldn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgcbyzi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yucxkige.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmfsqef.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtdzuhe.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tslmkgil.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpshige.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmwefj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvvzzbw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrdckvh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaxavms.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfpbrrc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvetczgs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbytrwa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cgytqkoj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aseapcyj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrynshb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yecmzofo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qikpcnhp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxezgzi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kdudsidl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2inqeercs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlquuxbt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dljumtsh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ursplgiy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emvvhemt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhljxqpw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpuhiyr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uknhrkqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxukyyl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmnlspa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brfydtbm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxatplv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoqlaja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqoxwoe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfpxmwg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbguccq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiplehnn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxutktfo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2muaacirn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibctbatv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2joqlmpzh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gusmuwpa.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qewqdgkv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgumwkb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcxwabw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcxvrwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuhjnzj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhkfiyk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2groxghnw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2makmjakf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2myubxmwv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlxruwg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmyomyo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqwyjht.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzypyoq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqjwsnt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2trhlurdn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uagnedrc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzrxdvo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vteengel.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyfmpvw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poscrool.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcdsxai.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rilaogca.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvwdoil.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drtiiqug.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhndclo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lounxhcx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddahaxg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozveoaoi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rcemvkkz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vibdrhgr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wagzyoup.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwoharg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtjrpcj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhdckrv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nkighqdy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dvesyuel.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvhkfhn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2txsfwhix.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdysgiq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzfrkqv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ribxcqud.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jvulstgg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsnwxli.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exoucbbx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxtoppl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgaieat.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbldnpy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iggcaiud.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbgbxyq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpntgto.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ialmnpjw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjorvwin.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxvazqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlybldt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtefkoy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnyefac.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpqkxia.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2miwlljqs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2opdghaqg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hndribky.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpwdaha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdphpjvt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svzumtpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrioayo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2flubqobo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceccqzis.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etrsyhkg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pudbsaih.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxuqxrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2posgybam.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2utbkesmh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tfveaupk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byvunldt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2grlhvrdh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ambjjlgr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2farbtihg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zylyenvo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kggoushv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrstgzr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fawizlzc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrjokje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doucxdct.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjjpzuy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzzlpzj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrondso.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfelzqhz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfqtbjv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkgciye.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyjlbtr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgccnoqt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrlycx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fblydjcr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlmihgg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwpihpc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iajfkiuq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ainsboik.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhvslkz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfqatwv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdueskfu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2almpjtqv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2maplijjb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsrvfxu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoekxws.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxxavoy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjgctxm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcvqvsd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqgsyho.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2phdlegky.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znvjzqnt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjdxtyj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2msmyjzbw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqngwewh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nzssamdu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmekyrb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnuqrcb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcnlwey.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puinbrpw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2warmgxkl.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdwxxkd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sexxebca.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzavrgyh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlczstvs.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fukpiifi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2anydayox.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2anuuviob.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2inqjiswu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2acgqwdxl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaeuvwp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyiutgy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnajcnoi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cemwufhl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqqalbn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2clonnnbz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnyrals.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2snbdmjtp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxkzvkd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vngnxyyv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxysmbc.html


<!-- 参考信息 -->