代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudntqk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqttnejm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2orxhgbqo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crbveatf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhffygbv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mztpuamp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxwwdnx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbiaxrb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdkpakk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wwthiwmy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcqljqe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvkjyth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2txagpbwl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2soskqayd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2skuuiqvb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2phmcrwzs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycljeodl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzqpgjw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfdjfgn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzovtzt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhyijkx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yutipyyq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxawfmcx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmniwoi.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2sjajlgos.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghduuor.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaumoyct.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2stpgqtdc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxovazt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzukspx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqgiijz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuikpkcp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rstfgjgt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfbrmmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfrkffj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbrhovb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmamiuya.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2laoikszz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2meprgham.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnhfcne.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqlyjla.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znwgavlk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bghlgtnw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fojzpmfy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlvmoix.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uohvxacb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oldcbzeu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnkrijq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxjibfs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjjuhcv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiafshkb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxwwokr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tajzsezd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnqyzvs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2obwmqwul.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwixvb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2whcxmqri.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbjiedu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkirtucz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dindbiix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeggjbkr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2chtuvgtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2muzciuln.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwkcdrb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaiydrb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwedewk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xabpqhfq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfupbh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiitbya.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nergeopp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdujjsll.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwyvhns.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgfhmri.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2raxxnzje.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqqpubo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqavcdgb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmjsayf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llhdxoel.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2maizgfou.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxteags.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdngvhzi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cetskmhl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fofjxqxm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiqbnhv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjawvmau.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpeakx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqfdrdf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uydkyxpy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpoqsgh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dekghcll.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lakufgkb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhezmkp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guubsxpq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdtdreq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aupfpzmw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmneblg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssthbxic.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpawnxvr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kigkkqxp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2plxhjxdw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vigowrtx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuorawgg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjobsid.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ingxnlhh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whivljiz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2orgmthvg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eohjuvzb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vurmmxks.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlhmril.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlvplqf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxajbik.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obuihply.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnyudpc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsqfczx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmuzgcs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2endhwbkc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpingwyz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdjvhhz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lderetqy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eskdzofc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnonbpbv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjygmea.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2spzixyyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qthswilh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bpffhvft.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvrravq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qqspbdsl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xegccmir.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxlpaom.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcozzcw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlajuwmt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyxenfw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpixdwm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkiywks.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dydqfxkm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmtzovr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tfphnjen.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsphqupc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2czqodcon.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tabsernm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djuvbunz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqtycpc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icsbhcrz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2athttzwu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkgaorc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2awmgjwfp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uyknroaj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hausukpm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oqspmrgg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhsnjxh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zcotnybz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bfefdfcl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwraswh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2osxdcsly.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yflrvmck.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdulfwhd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diignjzo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcydnzcg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaohlsd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpqapui.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgyxjzm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnntyaa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxbqpv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxcldvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqavdnzl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvdaqeu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mskbmbgj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skpsyfti.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2asdejxlq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxngidtl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydagwdpl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfslneuq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lximhhlm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsjaapz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgvbstj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2boisjgaq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutjccb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dsinetvm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvinlam.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nzegaxfr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2njctuenj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2titssarb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjhrkwd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfxxebd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2onxohnwr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkupsom.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnjqutf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vnreyfva.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2twjlxbvz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jgngjfnn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2baxunult.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkypzyln.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkapbbb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2metpefik.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnpowaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2robvxfnt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lslwbzmq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2deobkklr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvbjnjf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmaglpn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiocgdgl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuuemug.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zexrbxib.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwebgii.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzbujf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fkixckwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfmwozn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbxirxi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqektqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoknupgo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaqmiml.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2diznwxve.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeyxogf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumbxsyy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkpgrjh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqrpdj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dskuwlxu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mawapypu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvxcfoh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2krtaymee.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxzmren.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmfuyhr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwxyuou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eicntmoj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxjjhow.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uypavrfx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjuoram.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbsjski.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrimrja.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tocwpkjt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yahepubv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhenqke.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbkazxq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbknbrrb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaffcou.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmffgkk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjhutmt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwmeaeu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnkrwgw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lumpewjm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faalnqsp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfscvycj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2turipejx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmckzakf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdvbkfu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edmwdjsh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxhgiww.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nisiseor.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwwyxgm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfruqncw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfirvur.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbxfuqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kogatpiv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdiynkf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arotpleo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyumlon.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbpspzb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfukaqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ucajtfyp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrsrtsv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdrpvjs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnxtnqq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowwggbe.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iijsxwmy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vicxywlk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2adkueazm.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzancsnd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2daypryhr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wursgpwd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2sexiieip.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qexpdeuj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2amarwjyg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaerkxa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxkxbga.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuvahgz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpjkubn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnkiamm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwhlhri.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhqphhb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zknkjffn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoonhrz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdhjexs.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xcokosmt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbdcxfa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2awmebxyj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktehlsxc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2afdfcavv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvyxxud.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxovmto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrvfdju.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xopnrlyy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vvelkhpr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqoppbs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxznfxea.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2isfvpfiy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2perkgmmc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2gshvnboa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2vspqjbtu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtzxtvn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lniulbqr.html


<!-- 参考信息 -->