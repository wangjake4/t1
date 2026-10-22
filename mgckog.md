代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akytkkft.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgslxjtt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkgckdl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfqxouo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzuwpfq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgyskhu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfncwspd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csctlthp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nldacfgk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjxrvmp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbakmvq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrfswzx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqzaikq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdkaheo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oniotglt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlsovpn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuowbml.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlppuyh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2peztfrtq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoqvtst.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqitcxit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvotdhur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2athespas.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ghshiecj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rapggeba.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vktuchhb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2huiteunh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pceouenf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedhsluq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrzfyhi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2evdrwjwh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbdmfqs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2lluqgvyq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqkxpyx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhfsmcs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbpkoay.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkappgv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2loaiqkwu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzmzbij.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccocxedw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iuutiztu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rriktbsr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oubligod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtnueyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqgdtju.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdrhdun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgbxdj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhazsyqq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwmasbf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vglxetsj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzvsdcv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akvwwyiu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfhgsqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttggjhss.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usibvkwd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2butuehps.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qvavluhq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdhwbhl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdexahd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfemjov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzyinco.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2odepsouh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2whveapfb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mlavoqus.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lebvymzw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fqviczxx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2stgoqxml.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yhffqzwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpxhscf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuxtkyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcdajbx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfgkiib.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rtemmbpb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tytoyaef.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lisozmpb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkllihj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thrfgwlb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfrvlix.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tamfljsl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khtzsvrz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoaaxse.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xstsvumq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gegmxpuw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhcxhfx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btacrpib.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkufllsc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbgnjma.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uffeejem.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlniytk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsrvkpg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtrnlqp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iujfjnkb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eijysiqp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkddqkkf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctldgirx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyegnik.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpokqifj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrxzhex.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2syiixsly.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrnyaco.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drxkwvuu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feakrjcp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgumkwe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocdotft.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oticuvbi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjosdywg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmkgueo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtltgzw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kuerbfbl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aazrqtlq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgsijiy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcwfgoc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvnyzuy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbjkbee.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwtidua.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgibqimq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjuadvq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2geiijvpg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgllhav.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbljryij.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chqaquse.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abwaqvqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvozshq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iengakrz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcydrkwt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrhdrov.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2krqnbjvj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgpknce.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwizogqp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pyozszey.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nperokvj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ymelzqnr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwpuvsz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhxkhjl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kynosrzd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yafwrdgb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpubgmm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpneumvc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzshadsk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rromwcld.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fgywnqbj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ervqkosm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yboiaiou.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlrkejg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2btdmalrg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmsmwxk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sudrnurr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdxhtqo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhtrpne.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcfyaod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2edemtumo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssajhntv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2etdgihrj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zatdduyy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uejzzmxw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhqqrsk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaayadz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zbagqzen.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qudnrhgh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfssixh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2woxfqvtt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlruefs.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkcemfc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdjfaxk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkcfkuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tekgjhon.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpvinhr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnezwtwy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvllkncv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqtplfw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcklzts.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qxibmibq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfdbvjq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgvislf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmfqxel.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnvtqfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjvgovb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrfnbwu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeejehb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uowrjpdh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiiresd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgvrjgy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bobubrrd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlphgzj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cajpzamq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmobkvv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylutbtnh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwsvasf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2chdiaxod.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zygtxnwa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2byvjsvrh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdoxxad.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvunduw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eteyomfb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcvohkj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xahaojio.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzhtsxa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqolivk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxrrxho.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebonlsgt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzlrvkw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htomzqrc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkbmrok.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2krzygzgh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjrfgje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozefrlhj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaraeyc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpyybrw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxowcro.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzquhlxx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtyrbut.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hejnmevu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wwypkkti.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2miqighzh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdamwtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cerevdmx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qaelhohm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeizfyp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2njbemvxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkgbkpn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdbrlvv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhyanxp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbctxka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoijxqup.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdyaxpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwokutwi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvifzlyk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdyzwtg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkgjbhl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2myimwjgb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xagxgcjv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbsxqtz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwujdiex.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsxnhjy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlbksgx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxjbdgz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqksfei.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgzpntk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwajswcg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjyfato.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbetkmpt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2omldiksy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuklbleg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xatgcphd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvpfmlb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvcfabc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yjduzmur.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udhjudod.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytongoin.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgllfip.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xggdboux.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2klfskcjd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfjangc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brslqqdc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddelokka.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgbhcap.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iskodiin.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fluhxmdv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrsrlbb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuwewby.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhovupzt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rshbpnuc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrpkpqf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2onquxwln.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2omkmvtoz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnkcnii.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnftwxx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqfyyqb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrcnkuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrmreel.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwchsem.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wofgwzbn.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lesqytis.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mamxbepy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyhlcnv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuwoies.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouragyxx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2cviiphin.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lgikhdyj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxwczvd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khyowthc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpieadi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgodjizi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2apcchpwy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2klrgnptn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bawgqugp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzkgxjr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2trxmvvev.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfmpwht.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2giqrdwvh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhcoqxh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2miaejutz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqxaxng.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2opomcjha.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2obksxjdc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbykzdly.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lsalvpuf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtazcdfn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuggvmw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2majdzgbr.html


<!-- 参考信息 -->