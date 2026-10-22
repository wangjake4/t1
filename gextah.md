代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnqhykv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mescqgdx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsurvfkh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uppvxjat.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvutunny.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrgsmai.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwawlgc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqcueml.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfljkebl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aifqmfbf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqpzkl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsbocjc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exgkybxc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtywftjg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2evpqgcdn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaxmndv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvwbpux.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzexree.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnakctay.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glgkrdnt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yueercli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxcmhcc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtaxlnb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2biuxqztv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fswsrlja.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2emgfypgr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwvvsrl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2azuqktsc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjtqjrh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiwkhha.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iicfztrz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2birxotjx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqhbdbk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejovdsoy.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxiuexu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2htrtigok.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dqewdbqn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skvhtvun.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2reunmgjq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ntibccba.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqflysg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdqxoor.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bspfqbpl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyizaylh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrcdugh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2irntzbjo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwebwxcy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wonuheyo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gacgsyde.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjminizc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2umokwuox.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqtchmc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csbbwfoy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxphhwd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uronfhml.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbgwdcy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdfgdro.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxzjoth.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnovrjko.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkggvqs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsgoaiz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyietvya.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrbsusz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2corcboab.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvvcyyq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgglenz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mpymrolw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmfflvv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jithamef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkzfxsa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2erxajhka.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2syzvixsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njtnsxrk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxoyevd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcfggoj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pirzsnjz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bukkduki.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnduzgt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqrpkdi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emlllkkp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waczdxcm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uktuqbaw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpavotmv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qevomcjl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzktfst.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhckaeft.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bneqjkub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgybkdh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suwunipd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlkyvjc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaacyona.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aaenrvpu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrpfaht.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2guolwwim.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnvwrfm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwndxxkr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyduwokp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmmlisu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2phloarmw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnowcjx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fklrgzvc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpbqlvz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2udfcjsop.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kdisqshy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeitygq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avzexsnr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dihqrxhb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qauizwwj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukgkbmj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pabndimt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyuysow.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2stxcpljl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmygktn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omyrmthe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swpejmob.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmoconl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uthjljyn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eytuonyf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnwhdln.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvbcyzm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhldwbu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyyljda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abnacnjp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mssslkuv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkfyrr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nadrgwsf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pcigxnnx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bggocwmb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvozlbwv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpbdigs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tehtsdmo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiwwgqw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnmymut.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrxvsfa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2htpfcowd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgslhpd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpeskwy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzlcily.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgqcsmm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pdagkcgw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2estjxegu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaldysdt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jedpcibt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aghdscsm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2skrmchss.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwqlvej.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzghnvs.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmbbwuo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nncvzikr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjnirxw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaybinu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgognjsk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edyflrbl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyrcfaz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akibyejw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwboksgk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcexulm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmjndad.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rvowgfub.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbfmkxw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iuytcmzg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2reivbssr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nudhohle.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzlqmek.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2czaooygz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiskgaq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvqusbm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmkujhg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzauvwh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbybzed.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wstggere.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nruiabqw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yjreivly.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvjigef.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ufghxfgk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgthtiid.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egfwzwsl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqgalvv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocddfujv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zonxfuvp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cofdofps.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlmupae.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvljzyhp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hozcdquk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmsishs.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2popsicem.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dlymlvgr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrchhaz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkikosf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ihesstal.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdijblwx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dredbvfm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2phqvhybd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwhspmo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2asqspauw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2flxbasye.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yczsuhmo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usrzsilb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkibxny.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkfamuq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylopguyi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuiyxor.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chpqjpna.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvikwmpj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hexowevd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyyqejm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zearajxe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2watmncsv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjucosz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoezngjw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2npitukcl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpdgjir.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvshdzh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwgkpil.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2egqkdxog.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmobdbom.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2akmzxetb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvmpptr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsehxet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qufmbxkn.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgpkgow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgamspri.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhmelir.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjggwpta.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcdsrkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khgngoir.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acgryyzu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqkkeiu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsopybe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spsebtam.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oalhsffm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpswxna.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzbodof.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ispmmmmb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvrzusv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabsvewz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpogrkqx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsxkevt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzbsemq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhavoqd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sjejpzju.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqejufvd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdbpmtn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtdhutf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2unidlgva.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcthguj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxedxaov.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwoczam.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmthfbb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfbnyab.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2erztsxvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaeksww.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivubhnwz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkhafzr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnahskfw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kijiguhu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnhigba.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amkjrjtu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axprsnjg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkaejgk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdckell.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvdifxi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbkefjz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jykcmkyc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrkqxjn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ubskjtfk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fucohttb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjjonzc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xepuzdwh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2matnnprs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2awrqgqsj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbooeca.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjtvmgz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mboagpyw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeqhksg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyclkmf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhpyxyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxnkmji.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uudwsiph.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiwvhvu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvyvguh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzgbynb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzpchgy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeviepz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vanitsku.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gazjjtjt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2abdqjwqt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2odlvndlv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfnlvma.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqvjzvg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjbkzjw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdwoda.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwkhkwk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnrian.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acxoofor.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkaocfa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifspmnzp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2edfobkgu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrqieay.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqccfrfx.html


<!-- 参考信息 -->