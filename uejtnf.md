代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnlttnt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdfbmgs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdkfvpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pficnwdk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2opkwqfth.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2svhcewpn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odtnrxxm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jefqpzhi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aayzseni.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnazdipa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyvxkxx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfclkgv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqriyksd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaaztxx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkvmcwe.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhoweun.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhwrrep.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2loqlfoda.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yujggxrc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apiqdmlu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jseluzxj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfondly.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2txdaphct.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvbjcqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmpxyhq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrheigh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiuvafc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtsuamj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwkacoa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgwjxtw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nohjonvp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzmvipr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwudwjom.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoesbvew.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mismxvgx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wthunzbz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbaenzj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2megaulum.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlbpwym.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrzkyuk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dilzupud.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2joqjqsms.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoambhn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2utislrbi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oibvktbk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzwbnsc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykztyzhy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbybyvqb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kldcoutp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2byxcfdlw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrbcfgk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwvityx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lidooxhu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbxprlo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oerogsuy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rouuoxhe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvooerpa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpluzejv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knodozvd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opvjkdfw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeeghtm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaqbfxr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eouhjsub.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcbbaeq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mwplzosa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnmhosr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjzidie.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcnuvsh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpezftvo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfgxbri.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxrumxz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2aytnefbm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdrpfrw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vukugupz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdphjyor.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rssighsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ratqmfsk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2birgtwpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzayfwm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxvwxzg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrdjhnj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhklfbxg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvskskw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scpdbcdn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmipbnap.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2omssyxtw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhkiwdu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjrshtv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkzutmp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uykdcmco.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hulwhdsc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwjxwhd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlekdsj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwgvmal.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmozwoo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mekzkjvk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djzqpnbn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsbhhot.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgbnrip.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2whojjkta.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zllpfaao.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhhtcgf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2koaytojy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsukatk.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpufsez.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2araxzrtu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtmulbm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmtwoom.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjdgjth.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lunomima.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcfhehn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maprddab.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipecspoj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dobshber.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqchlew.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2erhnayst.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zsonasff.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhouocom.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfzwlmb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxvvsyc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mngafkzz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eyomfzjy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwhakrw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baiulbcp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aikdmapp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsakqfj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhzwpdr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqisyvj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bttxtdmf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzkukmn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2acoojxzt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wulqnkqm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2eexhvpha.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaqgcbq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgwsllk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vezhffja.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzljmhq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2maproujt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2smkdsprm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cftflkgl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnptdxg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2itthwwfx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzuwuml.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxolqho.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mohtrxcu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hapkpsjl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrybibbm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoujyagn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmenarrz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlsjrnn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptibiihp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkculgq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cehbfadt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqzjvrn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nwefbowc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcwzsoc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fibqklup.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srojmifj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlclrdnk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfrzwkn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfptcwz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbogya.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmtktgf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpnlsgj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuugzwi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvbamji.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xmswbzig.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2erkowepr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2auccoknc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2imdpvrbz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsfajoy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poknavfu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvtahxp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsuwxax.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgoqgft.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqzxhiu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzrhjis.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpueewo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnxspen.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbcxbwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrbmdqu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcsdzni.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoqsphk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoxaows.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsldftm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blgrfofg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2efmrgjyz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iihrxkbo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oilkjcnl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2luhfnklb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdzydme.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfzroji.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kypowxgd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlnrfgc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnfpmnc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kanqsofc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrzxkek.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tlonnzvq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tazgyirg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuegpmj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlvtidj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puoytvek.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhscmpyf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtgqvbv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqpgtgj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwcqegt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2miijtwsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpnxgrw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyrkpol.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiifeiz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdwbepm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwaegzm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2grpnfxrw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcoodpq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wrukelji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlmbmth.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzvzjcc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxhsohd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkkiqyz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyvcfio.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmqcpno.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkjchum.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tppxblsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szkznnrv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwlcdks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxttbbq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vowwiynq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgiuykf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjtjxnc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggzlpff.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qamfbraa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twcupfiq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2olvrgoxr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwjxjt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhicccc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yulestsh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcilurp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnudupq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrehezhu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekftezes.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsedwbas.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2yracfduo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnghcsdn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmtjevj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2izmcuafx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzzdane.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2djloipii.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlshqpcn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfolfryt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhofvjy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoksjrt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyjyrri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfpszxk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2okzikieg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2slgdujtk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsexhfeq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knsyafgs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrysbk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuofhyee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hspvbopt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2argvuwkv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uztxycux.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixamuqgt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lckuvgmp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwaggym.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djznewjg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvbkpal.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huxmrydw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvpcsnx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2kizywyuw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzfunfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcqjjyc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qlahnema.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gucbscqz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mhatrzhj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eommcssr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2colkyprp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmurturd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarxaocc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dszwgtce.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpzmtrj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wszzptid.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gksfohoo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2utzsreaa.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlatxid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyorhdb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqzoeym.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zulgnhxw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qopflheo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2adczfkqy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgxtmye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvesuvh.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yppjfyps.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnfmurm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziebuaxo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeilttz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2agwzlgpv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfwomrt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uqegqeiu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2vtppvbvt.html


<!-- 参考信息 -->