代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wccudamm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcitzziz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqpqdiu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjawzfbm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbypvfy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jaknryue.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2sonqriun.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgvkfow.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znmlavnx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfirydo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfajgrh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbvkthj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aibgitwb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwimowc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gagvujyl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cskudcvz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjluhywf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iowydgqj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2guheegbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftnkbh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldpclyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjuauqz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lffwutra.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfgbgwt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wabsgzcd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsuqsij.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbgsbif.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cogtpybo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qglwdiot.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjqifuu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzhghlm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcygmkrl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnncxhlm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jryxzwmr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2deabunyc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxxcfmy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxnrfd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpxmlte.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txmvaiou.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjbjsco.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bewkhlls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vksvnvja.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2eplraguk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgaqvn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xuibizyk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiuzdnq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sluyyhfy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2shazqbky.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsmpfrd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsbsvmn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdrfnaj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jedcewkr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxvslmi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkfjdnk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvyxdkx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enxlfgir.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prlsluqu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvknwene.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbmjqqm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdnuhpy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nceiudwd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcegrnpu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmehru.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmyplxx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzvxpkk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgwmixx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2unhflkuu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2itgkgbvp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fsohebdj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2btuamqsq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2frnkxzzj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgrxejt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpacdgbv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2brgvyrdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aokrfyzz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvdmamm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxhjsba.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmdtfwu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwbpcb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdetqoe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgbgsxv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkzoeyf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjafmsw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuuqvri.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyvwmjo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeythen.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azmvfpmk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrqdflw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzehmfzp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtiywtf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2afvpvjeq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzlldtm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptookmdy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sduqderl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrxadjt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2unacytwo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zemzbinu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgtouii.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrmxjog.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiorjvt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqtddxi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjunkpp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwffdpr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqhtyoo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtycvub.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mweuvwia.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxydybtt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mexbxkim.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeuberk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oepotsqh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txzhnpvi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbcxnuz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mcattsny.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgwetzm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neudvfip.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuxopzb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwysfqxh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzzowtd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uljvfyum.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shbycxgr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2acoauhvu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2knjfxuvd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzisukc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlpxytc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meptpcmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcdmopu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiobuql.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gghiwnpn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gktyokpi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zewfzfxx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqxjqos.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nokhotby.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2utnrwkco.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoybecew.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtbhmpu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zacjjbei.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmgapdt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vldpdwug.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkbgwqs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kgppfall.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrheqarq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkravyf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dovyzkop.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgxfxko.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nucektsj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urnenbrs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuspkjys.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sishpyhy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fktuoxbn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzvsrde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bazyrxzs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyeevqm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2poqqhdop.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjugcnk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glqxzqom.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vierifbb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ecovwqoo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxovxxb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlsfxgg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fctzpanr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2grzvcnvx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpnzpqu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvupvzn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfrehqw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeamwde.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpnshth.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdgteka.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvalpesz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zskfqaxt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmparvxp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrlrqwa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2byrlolvt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2upylrljc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odvgniyo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jryfmpse.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2izjbssem.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaguoiwv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmujuios.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukzwifm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faqgwyke.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qikgbzxr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaeoeyj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwwhqgo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inssqtpd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iabthbke.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmogcxww.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2urekdpzv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2woyngdgc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgxkzlk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoewbeg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnawboav.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ieksakar.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawnrrg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qffxprws.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdbjlqv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2irxeudqq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2trsmvdit.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhrzgbx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkhydhc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxkobnd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwlkiyh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aamviiwk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsdebow.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onyweanh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsjmsck.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sywglgeb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjbrvqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrlwelg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxwppky.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oshewkqa.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lewxczpb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpsfykz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjbsiua.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sugxxpxi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjtemrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2twwsovqt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2suhgmlpr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrdqjcy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuilbuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugemeari.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2txcfzfnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiigzwh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rjagwwgk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2edimjuxc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xchawzpi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxplljwo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgzoszs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxnksoe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfdshbj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzpgxfq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mckdqqxk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjdqzvu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgydbhb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olnebuoh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zthhlgiu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xusloktz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shzjgrvp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uujmeiaw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yytlvixy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwejetsg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrnxrjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbygsndw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pngcziax.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrcefyv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgrkfpa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhfhgah.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2phirpkou.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezguwmwx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvvmnlf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kymippvl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjayurs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avhnmibm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neqlfqlw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqgfaa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gptoeinh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gatufzku.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amyzmznp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlejilx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uydboekl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qojprcsb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaovzzt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gktigtfb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mazqrwwb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyntyxu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhtpsxy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2znncprbn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kravvhzd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lnycjuff.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mmugvrgz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgcsvzh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lapwlpqh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtowtxr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2glgfzkxj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2svngzgxn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdqrrdo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ikciewqh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnlpbzy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztniebmd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlqdzna.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdixrxa.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kebyykqt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dridskul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yopouxxh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2txfvprek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtljjkst.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjzcmmt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnxzlzp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkfdnie.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzwmmmd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpbyada.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjulvrbh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2udjamajl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rwodieiy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rdocnyhy.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aijlhtyh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2itzsjhon.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2brhbxurl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdoroby.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oubeyffv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnekyxux.html


<!-- 参考信息 -->