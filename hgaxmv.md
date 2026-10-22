代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwbjptc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnmotli.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbxckkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpazdjvn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nddqegfn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkptwkrn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpopadb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykirfsvh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dysnmacg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guxzaado.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idrbjxdd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2laungrmd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdydpjuh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sakhpbkp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgybpynf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flabpkao.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tykouedd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2coepknpf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxygztx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbflagxm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhayqevh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vutjomws.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gavlzzgn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbbiqfl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqpdymk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pffkokij.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjwyqy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bccubbkz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yasapjuw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqrapjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbuqbhm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dagkzenk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2taqsxgov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgssbmi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aotfuvxz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrjhzar.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2prfihnog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuymuenk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqnqseu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgnzkmp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmpgejl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxcbqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmjuwwc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoivhtc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxwfdnv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgrrhpb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcliapxl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnppycbe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdldxpho.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlvjunj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvkyown.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsqoswp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiqjstk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyxbhys.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzsvfpy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iekvcpzh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspyyhz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqrqwbj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgajfbv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrnywjp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dfswrctq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsoxuox.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwnwuxw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2srlhdbbi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaueflt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2arrsvdwj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsphkwwh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hqegmhof.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqrwehd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrdfcqw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kolbmico.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2agvfcasa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggskuwaz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oejxldid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xouphyfp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2znsnbxpy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vphwompz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwapljk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcbfmas.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2galpsukg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxksoers.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpssnes.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyewkufg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evcbxgww.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrxndcy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zezenjpn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baxzedkv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtfqvee.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbrtayc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ariaemax.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2maxsliko.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulpxin.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cruspcnr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxmxtvs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zojlikih.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaolkgi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtzgtgo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pejnndok.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzggmjmo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtougmj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqknbvyh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnatmdn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zaafkcex.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2orzwndoz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpuktsd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuseizj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfssaght.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmfmyl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wruuzkrr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eydttoph.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czqplurc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkjkjef.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlvrqcn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkvwvcs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysipwmpb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtalwjf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqsyhso.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ctutljhz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgazvwq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eydtfvhy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnbmhvq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpforhzk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unbavvvl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbajoehp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otonrjgr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnwlvbf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mriepozp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xoidjfxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfieybai.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlttqhy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sutytjys.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2shesanzi.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwirfjil.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdnoay.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoahtsn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yunqhrbf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqvneiy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2osczilvo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aiemlvrs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2canxjpnn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czhuoolh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbweyrdy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nscwqmue.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woxqnqlm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvnoatu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2enuzkjln.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmfrwgh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qusufngl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cufjafgy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsashva.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vawahnqz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrfzymx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuayvlv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpcvrya.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmzzesd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssusybku.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwqaqsu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mixlcryr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lygvqwqr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtiakot.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pinfwelv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ildnjcjf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjwhdaa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqupnkf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iisveopg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdoellu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjmdgnf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflxysk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkmighn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzhjdzi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2natihweo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lffgbeeq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuflaqw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfffvys.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2koljctxh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lotoevjx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtkgxkp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrzofwn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxrlrbl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ninnvgni.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eurzjizz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvvbcol.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoxcgpc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tguhtxjb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsstobl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfuulki.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiimipp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgscvlt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbqmsod.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zewayjca.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2scalcjrs.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxcfewg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qpipfslw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwcrtlu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yybusldo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qophvsli.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgytdnpq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwarcchn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kodjpdvp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2enolgyio.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jylnkghi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtnfsbu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjquidw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcxlzuy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yilnegba.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgurgcrh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2otqqlmlx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzneilg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsvyuih.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kokoraqh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaxqbca.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdxiats.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxizujj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvcnrwt.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsjciri.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzfcpka.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrfkoba.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jokcatqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2aojiciyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbxvbhx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzmvekd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnswlcbv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcqawmk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnandhq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqjzqxm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bylzyqnk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwlkqpk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2endezkvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhmnfqi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oinhwbou.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxtlyhw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2koadymon.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrskxat.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophfzkgk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnqusqd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cabjzghd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwenhhyu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2giwrfauk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jailncxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hginepfa.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2psuofqkj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbvrknm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiedads.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdevygj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiboegr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pndtjwdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgbxddj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrbjpcz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgidpzl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eufkufzm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2snhpkxoe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzozwmcn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xesniocu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alhtmmjo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuztyaqc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlnevme.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkaaskj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzqpsug.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jyingfwj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkesvjr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idbalqyo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owqsyxrt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmifgds.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zefsjonr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdkfkwa.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbyjkbw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tblncesk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcrmlcp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfwmzpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2opglthfg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2glqfpipy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcarejn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdiesps.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtmqzjk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pegqchyf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nisjfkwn.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2egrsbyse.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfisqwsp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoejlboy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmcckor.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrklhtj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2obrcxaek.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dvegzmxt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkeycuu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnukqnga.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nivjfxah.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kabebcwu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2emnzxhvj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2azjxpoal.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2khyekulv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkyjlfc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxguxnp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2iwloywld.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wsijnunv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nnurltdb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzsxcrx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2whrmrstb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbgyvsp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqarqdu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzsqfav.html


<!-- 参考信息 -->