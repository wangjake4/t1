代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpoxghd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsngukk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2swzkqsmc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpenikd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgvinvi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2amfslfrr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhiakdu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkaqfry.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbbamln.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnyrjts.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpskxpmm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxkmtyt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuhujyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcavldug.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2anncthfn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lijtqatw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkxqifm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbkgzie.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtzmdaj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfphpeu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmxptej.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfyixbe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbepjnbu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqqbgke.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jifuyhqu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trpliesm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bicbdzyk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwwmerh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jusgctgf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdnukod.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pskgiyqa.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfgpmia.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfnfgsc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhutqohd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzcnhto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcvjvzr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmebdcjz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlvbtfd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cyepvwsn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpysoku.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwkoknw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vktkixhr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsokprmg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bjznianw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbteyeyd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2camshefm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeemhdr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgjokee.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkczsovz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvbuwxm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmvulsy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrudvpid.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsfttfx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbhyikg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeyertn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhtulje.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkvyefq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdshqzqz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipugnlyh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmegeozh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2munwmmdu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zimwwxqf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvzsxvp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbipmjx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykysbchk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpulrzfq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tabivunc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcravts.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnfgqhn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oephwwdb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgrifjg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiouhyc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dveyfuwv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihrefy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpxjcxa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2meypbwxu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdeopvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtwtuhx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjdfbjq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyxrbku.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjvltgq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcewcwg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uulhsnwr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2meppklpi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cstbcxzq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwlgqdb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2otvzkkmj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oqewbdwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcpnuyp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gahnryes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbtgjym.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxcvhgf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfnsodl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiipxnm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlihynal.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmawvvo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkiftkz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaeeomj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdofbklx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jivvrxgw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuburbr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpabdac.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcsoplf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2immuxzue.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cirailwo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghajsnds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpsyhrq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvankma.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvqlqre.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvjceqb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ermxolsj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2idnuqfgj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2afsgaoeo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2msqlozfn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiajbjbf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tloxqlrc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjkccnd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzshvtla.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjktxhpk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhpwjlh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgccsvwd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rexvwwqx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbnzysg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwyxnnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmlrqsi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rogqpfwd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gehpwuzt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkzjuaf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoinsqf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waakbmyd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqczzda.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifahhflw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeghgexg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvtzpjb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqheiso.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shorfsys.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvzgbjk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjlyxud.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svaeezhi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apnsvhqr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgciukw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kweaatsp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2thetgbpk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pywbrlfb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjfmgfx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2awcetvtb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfddvjqo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gscauksg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyhjcqf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvsfqv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iupvjrjh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2extcawnh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2eenakjhj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfkosvv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2keecfhzz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrqvklm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxlcgys.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skkpqmgu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjizkpns.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cshghfvr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kkghvdde.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeijmqt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okcjpmjc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdojfimt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjomppw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkmfuht.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wncatpiu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2povsodyv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joixeqxl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdrbyro.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpbpbbt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqapgsc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjyqgph.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nklynqwu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ullahawq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqtjcnq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2celvcnlr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vblydufb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqfhzpk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vujwnypt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2clftldvg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqbxulc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kwazsdtt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alblqbnu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeixfli.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwubzmxy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gflmprkh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgbfunt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fozmrubj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaffnxm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xukzqquf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2timxkcei.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xggehrct.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbrmbvo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lazbvaeg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rodkimri.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzpzmkk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxmrbvt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kveinmrs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggstjshx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eazfvkij.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2srpwnfrs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbmughz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkgxmgo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2myobihqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bfntsveb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2evftovoz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhvasrx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqgnuyy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vzehhyth.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqozlby.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjoamtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2suhcbxww.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmggdfxg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2syslifqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2brhtuove.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xonsnshy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkfhtuh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxvqxcp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpzvlah.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnjzgaj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhfyhev.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwouontn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xihurtes.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoblcmu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vksysmnx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2onlyewug.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqlufwa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcebfke.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2klaroile.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxbbieq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqbcepb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2njyqmstj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mgazozez.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnwvoas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxcusko.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvxfzco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmdpuin.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2elyqxvru.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeelkth.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjwdfnz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjtibxg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upyxeqvi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvquejne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hszxnjug.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbushuhn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjgbsma.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjoudvy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fusevseo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lftzajrf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhndgau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noantodq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjlootu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2btovczya.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2magkmpgh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyznnasy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoyvbpw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxacymk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2foxbvrdd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuzawxa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmffwarb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2adzfstnm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyufabzr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqgwpbo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwdvnae.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mljuavjy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzebnqz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyvapsm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsxvqgv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrreykx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzgldnf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzobveor.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kguqoced.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voayphbu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dirbvnja.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pdochrmu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flenhers.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soohxxxq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uadgleao.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vadmcmri.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2keashamu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uvebgycx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqhopwf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lboufdke.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrhzsoy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuptpnb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ddguvbol.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeckswt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpntbjk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfsuqvv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdhgogp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mimzrzjj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uycjzhtu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlzjuza.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yegagpdz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmwlgyg.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mskbyinc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2flqqktwi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rixrkstt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2drmabdae.html


<!-- 参考信息 -->