代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkxfyds.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asdksllb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yddaomjp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxkzzel.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfhjiye.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vahqukbv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ithnrpzu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxosmqn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tibokfsl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgiqwuf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyjcxsp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxazznf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wetiasge.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vypwwmne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yticylgc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kppmdbeu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hprpoaiu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpcjzgz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjckifrb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbrfefd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrxoedt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgkvljx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2banqayrc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrebupwp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yryoauld.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2shzufbzp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylawaube.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ungzscsw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2enixhyds.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtxioui.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoaiimg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjsrvep.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrwtdyv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrqvnal.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vagyiyeo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfztgtss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaedbbz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pldoggto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwgezeu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxstsko.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uraruxyh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khqahicb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gujdzdcq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpubfjd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shwacmqz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kegvnjoq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cctskrqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvgkblj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoalrfs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byrxhvqu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwvltmn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmmlhli.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbuaspa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzhvmmq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfotgnlo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2obgjiubm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrynswox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxilbga.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtbrltd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhaqxpb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2izazmqtu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvfcxbs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrorlzj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2plrwcwmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufanwbeq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfdsdxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abdusrln.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvwecge.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrmuifm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtgaxfe.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waujwaet.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nykrmsnu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwszsllw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2aruyfhzv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjskwy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czpjzxhi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npkicatw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2atkjexon.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axikfxqd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnnareb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoufttf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szirdnwz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezuhldl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2usqogrpx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjolxtv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rydybyhv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2egfdqcbk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxfzjrk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvchizn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgtlevj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacilsgs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbukvbf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2socmnsjm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2elqpepoh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2alpatgyh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqinnkp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmgdnsb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stfszuxc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jptrewga.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrxozl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yowaxtwi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2paqbgfsn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2neffbeno.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sjplycdq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfcfmsf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlapxys.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuajqyw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipinqiff.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwpqmpi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzljqwu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqeycq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcsdyms.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kknlzhqr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2awfslxls.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpynwpas.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqoivex.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbblkne.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdddxpb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcprnii.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpdfrtl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhndqld.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjihmci.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtxyzoq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2skwsgnkt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcknbpu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2loukrhwv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoddeay.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2arolhcsp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2beqyazqg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rshiayci.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2agkafbqc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ooinbbrc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqvntks.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmhtrlm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oesszrst.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzkffks.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkioweg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtizdbi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxewpawj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyclugc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2empyxhds.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqopypx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wltdplih.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvnmkkx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnmvtib.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkimbew.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjiopws.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspeazut.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2eplljzqz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qubdofet.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuurzho.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tguxyqaj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uifrdobm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjxatjp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwmaggl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2akvluowq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxwayxq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxhztke.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoflysa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnsisvl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oguayoon.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjyzpcx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ketcnpjj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpvnbyg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mltpwsyr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvezdqxl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pyduugeq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2roxudshd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srlcdxyu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krmflqbt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgcwtpl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riodrcsc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzcsoze.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmnyjco.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoekiwqt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axycfbva.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2udmgxaph.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpvbjju.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2deghfuwx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2csmonpvt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iaikgxet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrpdoc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxymxrb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xncbdvsw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jshgcrpd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rxogqpgn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nwufzvtt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cskrnofq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaccndk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lulcxdrc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdbwmui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgaupdo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mknyxjwu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ikomkutu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyanlxyu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxmhzkd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2acnsnrsh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrleesi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2akkyrdub.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sryjrvzj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2msijtfbp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2clypnpib.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iryftnor.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeekylq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdfalid.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcakqryv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyptnmy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjejbaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jwccblrz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuxyzzh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2usszlaqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtzurmi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjxsxye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqshddwd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yddtktic.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaygndt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymqeqic.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchmgmlv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhfinvo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lffofrgn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mcerxyje.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgkjcfi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnczeiyk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vdscrgam.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tggsjdev.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwjlqxz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjbpkme.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfbonzk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqrjyvc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfnrhif.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrndwpe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdrxrcu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgcjcjq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdqzlxo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqalkrvz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzoygkk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgtdogv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2keujplot.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjemgpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldukgd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntglfjpc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbbkkoj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcqemcm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeqkhdp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzckszp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqnspqy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjuoomn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yifsagqj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rumpehai.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjpxrvi.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvamnidb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuavvhm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzldetd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grngsrry.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pngslyaf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhvizlf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2lppdishg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uadmxlun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjknctil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kzknotvi.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcethtt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlzacdi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iunzmiio.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2noppqsys.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhrkhau.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2whwrznph.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufztrpu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qcddxzfn.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kqetzapx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfzuvql.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qimnyyci.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbiiuvm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxpkqya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2amehffwn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cohwfkiv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdxqthz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpnhmmu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwkvboa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwxzkit.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjojaky.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ipatkaje.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnqpxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwwajje.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ditoqbpq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ylllqwzt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bnubnwuu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2spdwbyow.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxbyyku.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qayokohj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2edrpqyjq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igiwkgos.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bclghzkr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdegzni.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kniwxytm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2congaqcb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2thtpblvf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyeyzos.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqnnxho.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdildlz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomepfz.html


<!-- 参考信息 -->