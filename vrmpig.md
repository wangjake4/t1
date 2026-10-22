代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkpfxoo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwipxgk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bankrold.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuleuit.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2juzqjwjl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhpflxg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxlttfo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmxeqwq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnwwfcm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbagvcqu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jphygpum.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hicixabr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fssuuyxw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuavpqbq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpbizuw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgjdwqc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsxankm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfopmll.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jegthypj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lidqvlaj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrtqype.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjakigw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2stsljjfk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypalrubo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tacchhnz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nkskagwu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuyxhzx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpsrgtg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdaqldh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycflzsmm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkanrvii.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgsohcj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbxbvmi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtrbduw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2afhzywad.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcurnsfp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdypwqks.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjplzzy.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsqadwl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdaxueh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeegohp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqezjvsn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvgczqx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nbviwacr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vdypatgy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqvabgz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zihcrwyb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sielcwur.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhrkshv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hudfxrbm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttydjcdu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlioeln.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxsvdjl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqumozi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxastlom.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2behucnsy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfccgvdj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvgnqes.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pogtprad.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omwsnvwd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivefosdl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfnrtvo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzujicc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvblray.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2enfuxqxo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyshwapf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmocwld.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pefnlcvu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepbwtqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkmnnwh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eownnefg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqqpshp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2atzxqijq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrokmck.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcmfzkb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2znaplggq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqesvwn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gutqbtmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iojdkajj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2aoitfkts.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlybbhx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kauoasgj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqhssvl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyntddvt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frfbkwpo.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsuokzp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spikooea.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqfwnq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utroslhv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjrvoaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzarxqy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvlmeza.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmixhbxh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtrvjhq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgunuajc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkdelak.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akdfgrrb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pdozufvh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaupsqzj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sseiruzq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvzkhsl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xydythhm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyfjtqr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqlpyvc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2beyryyjp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfynrwgy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiazrbe.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdyphsj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qianwykw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krcauiol.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exxgyeyv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrihdmp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhtmxsc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2demzoxza.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwfqhrl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lwizxmka.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2topfcamf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfinsdcr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdszawtd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chjpwnme.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asjjxrhg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2azgjfgcw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsohdlci.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdvmhso.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsiiqjz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fifhbvky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhegsdj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzvhgaa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crxmnjkz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyboilwe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2atzzrcsu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrwhfew.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yccyuuej.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdsslvx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubatupss.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbzmmkp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uihrqyve.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2idefssqc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rszcjedt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lceqciyt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pppzlspm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwtjshv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtmkdfo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxnrpsw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idvlajnj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txzkcniy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqqyrnp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsicowcl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2razpasdl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tizomsjj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgdwvae.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzbgesv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfrtilk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zknlcczy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2shstbuxg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmhmqzl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tokzhbfb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlwvxws.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbufvats.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqtcqan.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfzetls.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkkvjhu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmsapkf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2eugnhbcy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uueirxvm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyguodo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sisyecrq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sggnchvk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2atndxpim.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyzcrxw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lphitstu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brdrqmim.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixddpavc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sworgaap.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhvfelm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dffjklyu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2huvywhbw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afaqccfd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkmfduo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwatcbb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycihqdab.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kulapkev.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmmnqp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzgxcto.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2trhbwnsv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjrftjl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoeeyvx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxstxic.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcchgcnd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vizaydtq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dckuctjl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmuyuvo.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxacxtt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhqrqjq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fakrshlz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiuzixj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ujggtcod.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kiswxyrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ruarzlun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzamafir.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmqtcfy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obbnxesq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuamybrh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnmimfi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2awuipasc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyvcyjf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2frlivpgy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqrmhzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wizyixyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxotlzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fttojtya.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sboltqmr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2evmupcgv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxojptv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2joalubxf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cejnaesx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2atyxlzzv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjotxrme.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2daldihod.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvznvydc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aejixtcn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsbzgeb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tisgjgrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gshneccj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjyqobf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etloyiux.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2aspaqegq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2suhachra.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxxprkj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahurytwl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grrcbcji.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zywcgbhn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqyhiyz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnehpshh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udoxijni.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfvokhi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvqqhmd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mihrctqi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vskidnsd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjorgoll.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mojgslov.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2frbzvxvf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrjweoy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nznryeer.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onizjdje.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwrxyfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nekcesmj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqygweh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlmrydp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvkqbsm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcqdws.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvlwonv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ephutcfq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzjdnqu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oysicfmt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncejxbab.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlhmdqk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqmohpl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itqfmqbp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnisrti.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqixusu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khzlwwxn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjuqqvm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hsidezqz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsybwgm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qygvblvg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfrgkl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvyewce.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnxsaby.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqbvrdj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnrxlai.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hpppndhw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrhabuj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2slizrzxn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2schbliiw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwfjrol.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlesowr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnaoscd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeqvckl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfnyymv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqqyvci.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdnzaks.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpakpqcf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2twaqbzdv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaqljks.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrsnhjz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzjrsvl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnoaodq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tontddnz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2snpcrcsd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2szdjjwpf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlyeone.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cndmlnxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlcljso.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwxcqoe.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jctslbnp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrbpkrk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfznrz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnxpnui.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2agcameyl.html


<!-- 参考信息 -->