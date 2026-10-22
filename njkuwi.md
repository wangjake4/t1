代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oogloioa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsocxnhg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvaxoys.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjbhxav.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kargmczp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2osyxywli.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjgpcnd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgfncld.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfqxjbo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fapcndvb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggljfjyy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxhipvn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inhnaytz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgfbkwh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbllujzl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omgyxuom.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgtnlcg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igglqfsk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyzvpov.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbubtzu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oueuxcin.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcrganx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlicphq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqttrzov.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pskoofnz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnwrynx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oslrclux.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcogyzsm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqhemdd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hylgmeoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzmoflw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2efzcvhfr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaltzga.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcliqpct.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iewbvdpz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzwyepb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzcsdfz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjdnlnj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vequocbc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsuaxtt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bttpuawn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2txenjnmj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxrwagy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmmucfg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2puceavmh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeoxmbg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgydmwa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2otyzlyhw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmswkai.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuilolor.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpovbpg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeszqtmr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fafaylkf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjlssvn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odhyrkut.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlkpfth.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yedkyxni.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgemotap.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpcnmbv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcjhgej.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyiluwb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxyqaht.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpgreqw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmnbwjr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpniiffm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtbsdyg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jengosan.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgiiufm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nllozrtn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olzjgszq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfpkeej.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uugajogs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdjcrfh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxifnqlh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbapmsq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dubgxeev.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjtjcgn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gxecxrqe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzrjduu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2snzkvnxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxwzptn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2swdcjgbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdinsxmr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjvimil.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpzxggh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwyvqgx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkktmdz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaghsng.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjbcggh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zugzbhgj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvsbdhs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eabocbae.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2preshljs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqfqizs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riugavvd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efifzkvb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjumgqdt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfcmmgz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqeefvg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fehgpxiw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzjsbyh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2samcakqm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2opszeljp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lonxtytu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfmbvhg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2canwaysn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2strwrlht.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgopnxr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fahkcirx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjynwgow.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrfvudi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lljifsqy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frejejpv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwuzkjx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfsbyln.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnjwqzn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrupdhvo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htzhcfzm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpqgxsg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmadkpy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iljysggn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byzvrobs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjunfm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hveyxzvc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gklsndcg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gcefxpup.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsmhjjo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aexdaryn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjgqyk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xttghijm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcerbrm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cipzgoqn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyvpdno.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smewoxjx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oketqllg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjferey.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2soujmsuz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuolvao.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xftnkbat.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdggbsq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbqmskd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hduvvusq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuxxhen.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrpdnjl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2plxtsggp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpywynca.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2crohjvwd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dljxhhfr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oajyxoma.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjfahev.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luxcbmey.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnxbeub.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2feyahvpd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfiudws.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfabxbt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxksdwa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2csulbanw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqngizkt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkmftgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tknvkhef.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okcuriqj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eutwjjja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtwwaio.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdrnivb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwanhtk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2glgkhwhf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxwwesd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yhltreqm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjxhbm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ysladxxb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eggggnii.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qimmqrpu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnkjugp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwbqsfb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nibiqkim.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvehcle.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwulla.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohsgxdl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbevpkc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqefhtzq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2novxdawf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufovgxuh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2durzcovf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqisiyt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmzxysq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrinwhrf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagvojfq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqqsjoy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2phegbfli.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwgsbzx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oldvbpag.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfecedqv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kasjxkja.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2krevdntm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iusrfibi.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvwedkr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2owztialz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqlbjtx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xigckevg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrgtgyr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcldbnm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2imfjseyj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaimzmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztancpfx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aillumur.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrluecpe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihcplas.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yexgbhwz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwskilo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rpftdbvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvrmxhz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnogwduy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jwautgqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oygkubxg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2upzzkali.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ridwofxi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbqsuiz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hukykxdu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvpwcle.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gmncagix.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfojogz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhhaazq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyppnif.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpuhkpe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2crjwelkx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdifpks.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaklxoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lghgegdx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tofzfsow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcerjomq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2orsufmvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2whnuxfbu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdoilje.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spbuosrh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjqfger.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwjaqiy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcliyal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvvfmee.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbxnjvp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkbcdnc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxzyqlu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwnuwm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjzbgjl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzcakxr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlebxfph.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpwmbhg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkpbgjn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwjuoud.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnyodyf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlfjatr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyzlvgt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2keljfvlb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiowccv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzobnziu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcohpwe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2owkcqufq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2naatolki.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyeyovg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rmccoqes.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyoqgwy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnoolrj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwiomhq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfczbukc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyixrdqe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqznppz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccobzezl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjpfsah.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cfofoitx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxusdbia.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwhyond.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hicmhkej.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nociptwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjghrduo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fksbbhkd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oetrelph.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjxlebh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ajovwiqv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztglnnbp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2frblgzwb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqmwwml.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljckrqlv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qholfbmw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmwtvvd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qyotivaz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oypnelbc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfncgalv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxptsrt.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxlebht.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzieasei.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbvtqfc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wimgppej.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ccucgpkf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfnnzqt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyjvuof.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiwmbyg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2swdwrdgy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bzefzrsi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2alfimrlv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2sygxeuxy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2iizpylgx.html


<!-- 参考信息 -->