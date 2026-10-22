代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqscmnnj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtyjkhl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2thkjmgta.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pollazcz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmhpmfw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uusulwne.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bemvdxrz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbduqme.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2igkyfygo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlywwtov.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvxipjp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awrawtyq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmzinen.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqngmwf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqgnxuo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptwjhmk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qntqkpox.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhdnwsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqpzljq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhrnern.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmibtdj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wttwrwrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2swqiieeb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozunbkud.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgoqrkt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnfgfwk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcnfdoi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gffuddth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpnjpcg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wodbnfoc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgwfrwh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zupxpzbt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ugajhdou.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmfkche.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyrdgof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wepsgsmo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xakntjya.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnppykd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmklbyr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuofucv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yigcumlq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdpernh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmhjpbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdznlfv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgcjzoe.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jucfqjpi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoupttl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qinmkvmo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2feggwbhq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swnazxhg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryukcauq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyacbzyf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjqkejo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jviqtfxn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjoushw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2temelzfu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2whmvzbdf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaejdapz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiabbbj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2esvokmej.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fynhxlie.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rirsgofz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aienhihh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnxhvhj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2omwkbfjf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoqgkzv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxmkwgl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtwtuej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptggwcvx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxitzgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bogubcsq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwqbtje.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ktymcmho.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfnoaqi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nebjqdgd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuaphqz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vonhmlxw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazqlxon.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvowkjxe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkncjlej.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbmdzwu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvamqkl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcwagwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yirlylxb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwqolui.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkztpsc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pczlpyup.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvuaoht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puztlkpu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuomocq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyxsmkq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpucedr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kejvczbg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2frepkaqd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlpddgw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kdocbhkr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwzsplo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqaeleb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzpzsoj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnkdwry.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpfgfnf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flumewfx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csevxumd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdrpwts.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnfaxdc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzfqmhy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvuksqn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdprrgz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2elvlfqgi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgahiont.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miridcsk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaxmtrq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owcmchoz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2polwvuyb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdwmklb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwgfbbd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvawdkw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjrhpto.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcqzgnv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaaaxzj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fonxfnbi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzzigmv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaumnyv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdolztp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeoldjq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwfzhtz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxhuspb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2clugcprf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wztgfrpj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zswspeqt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxbmfrq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgtzqtl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hubzujjg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2okppkgow.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdeixrx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2swwyeyeq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxucluzl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrgtvhi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vczuynva.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkbnogj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdrilkd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbymxnlb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfalxdpv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hezvhiuu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiyfasu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdbuabg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gvawrufw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drjvgsfp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxunpmr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbgbehl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwpeujz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svqjrbwi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pptoiujj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruondlcn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrukdmq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbrluvk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhjicbs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oxitnrxv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lotqvhvb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2krocyaui.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyhotuv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2akzizmqx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jxarnjgi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbizzti.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfjhsdt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbtsrzf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkplfoxa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aadrpekh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fghyhltp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzefyeot.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvexopc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmqesfs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsxkmzf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpzxxjw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavxjizv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rosziggk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lojozytn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2beivitlh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwydasud.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxxrbpv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wneycbot.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfvzznd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoorgbl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhlvgga.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ymapowrm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rezxypik.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bslncfia.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vllamztp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iacuahmf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2frwrnmvh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxdhiqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dybgrjwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqazzinw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eebzleuu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2auzteqim.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aigvojqb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ferqticc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuptymo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpjurdy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otphqgkf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zpupaqmd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsuebbr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hydddams.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbctbmff.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkaukuw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nghsoezb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxgrolj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xinymcwt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhqecsk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerhuqbd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppssqxxp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfizgdih.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkjmfmy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdzrfh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tnstlpab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auxixxne.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nisvtsjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgwkttw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmsengo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2llaprgsr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmsurdk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtpycrz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pookremy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xffrdrzi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mfosmydn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpneyob.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhgpebt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zixjbgwx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2owszzsil.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfjndfx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dewimvjv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjfpedl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2expgjuat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xijoxyet.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfibxom.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqgdbd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpgzfhm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgfxmcl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wclgvxkf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2szjqqbkg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2flnqtaff.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpurpti.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjhgyml.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qazjnoym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgculqpl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pidhnijw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eohvpnjs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2weeiyudr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpnqxdk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzgnrvc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqsanza.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnmoeko.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uviwyktt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdsrvdq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyvkoam.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhksvhf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aizicipt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdytrrh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lddhertq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoehvuy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkjshlb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwksjot.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbeqfqh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2glbyglfq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrkwcjg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnspzsq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfypqbn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2suczuusy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbpwnbw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvmosfo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eembdcwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2keydepme.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqivnpaj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikprznsf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2subeygso.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2btsebsow.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2syzojdog.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xapehjrk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlluilp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qykbaftb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tonvxhyj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzqxhxx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpgbzkk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlyjiqi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gakwbqvb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kubwtuhd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yifqbmkt.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2liqixvaa.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbnfqob.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2szgbrtir.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cphvzwwr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpzjalu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cigvkbws.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjiidwu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbrpyvw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyvtccx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2acwbhlpt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwcestr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2spjjubpw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtdfefp.html


<!-- 参考信息 -->