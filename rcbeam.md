代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphgpuuf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyfdexa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2noqgxtsb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzoosg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqecnin.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpylqkvc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfloqcci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkwcbss.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkegpalm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nljzdbib.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfednxay.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpegtwes.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qysbrxty.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeibslj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjalkzq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xedcqlnu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqasxso.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrigdtd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vctxriak.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2riyrdxzf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwpqvrf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwroppu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyoumvk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnypisie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rttedgyd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxstgqbe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2froqscwe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2glemugwz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelszmro.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhqkeaq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhwngon.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2udqsseti.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zclyajah.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfcilxs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeauecf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzyhxiy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vugsorot.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfirowyr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzxnhdv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpueqdop.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jafyprac.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mliilzxq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdeuwce.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2riccmqss.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hzemjhuq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuzfyza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbokzzbh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yausplmt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdfxovh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfrxrw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdtfjjv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcduyvsa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgrsfbd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaosgcg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2piynhbap.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btouhjmw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htdylakg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vucnydwz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxzyxyv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgoxbsn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmexeira.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcppsldq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcjngie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtzngkr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2czdefmkh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkbuabw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgocguxd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aslnlafm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2htckskzf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjsidxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjvnlml.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2afzoxzsl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2biuphqqh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aljutmie.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ascrxrdb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2amucvcen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2katyaurk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrmyhwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdritnxy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dulmqhoy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2epyrfrjx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afassklw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbonbkl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwflfuak.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jglnnqls.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavthqkx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiememt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwuzifc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chrwxvwh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyarhbb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2doeufnvj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2newqkonl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iptdqsgy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hknqxyft.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zritpkzv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2clnkihhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duelvuhr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoyfiye.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgcoqsw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2okjvbcek.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyopfkmv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tljyrwki.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjwskka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2djuupxtz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjofqmm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcllbcv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uidkpmej.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nsktdqii.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgjzcno.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycysypig.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnaevqz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfidsztt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdhefen.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmjhcwn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvowzbdx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2karcpqja.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vckveplj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhzhmru.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgujknht.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfajhcu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gutcslej.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwqkloj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvcrzsg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etnbosxv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjzsoeq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnowpld.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlqpzhj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uedskyau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkedqsb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgoeown.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vautenck.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsgxujg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrljkcj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2agbplbba.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofabfysi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2molduomt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsgbalx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnmbvyw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2priswxye.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qylcicgf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uygrcsre.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvnqqtq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2finmsgxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2imflvuof.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqqsmkj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqopiuyp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyenzzd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kckdmwjf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aydafbxf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzvtcmn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaapiiwn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qengavaw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bexgbgzd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmsgtpv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhfltyq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgvkdrq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvujzmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrtwvtc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxzhjuu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2junvpedg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iizzzdjn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2czhzbebd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2noqhwuiv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqfecct.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2okxunwis.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjqnnyr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2khedjyxk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xirboqhk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nivmfoei.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tximnjmy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jckmqnny.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjeagbh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbggfnlw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdphicj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iohqplbv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvcgjhn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lchtozsd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjxrrjd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmgrfii.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yylmqheo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsogitn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmrhajl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktvtjlu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmquung.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbnpnvn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuftbnng.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjupmas.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtymgcix.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzncsbji.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxheospp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnizqqd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgqnvgt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwquavv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jiscksbp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqfqqyy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wspsljes.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aumwmqkg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzdkquu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2isgrmdcn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzsoera.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtrwthc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cupfcugi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtqyyjv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqtgrst.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwlhzpy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjjoqcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2beweweyk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkefcgnw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrzrupj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyidzcj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2umqpslis.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxmoatd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2klaqyaph.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lojojpkr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ruajqfpj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdmotva.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkarkrx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllqlbix.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfgfovk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2emxotsyj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2scwvkezj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2najlmjky.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qpifaije.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuhrccl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfolkho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xupsfpuh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2agnihyny.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsmjzdf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrynzxdm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwgupbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvqdtiz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxgovig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtnkliq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpqkaub.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhggavxc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dgascnji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwacgqz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhslsjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiluyvp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eussiqfb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2voittgku.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpobsual.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvrcyqu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovthmtik.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2khprsjdo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2adjymdal.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2alkxayyn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbihhomv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsbemyy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcclxhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lddscswb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2amnpuitx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2obohnaap.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyozbjfh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoqnbvr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjejhef.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mslrtebk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwsidxl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrerhgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmaipjw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkmihuw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvravlsl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pafhtbkt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2auodhglu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgtvpkv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juqlvnyi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prdigvhp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnygasy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmzpiio.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsztlqu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pasbgfzn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2udzflvou.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kvphvrzm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxdskft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgfnsxo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkdqzzw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxiaycl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdizclos.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiehakhk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qunzpiel.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmlikyi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2niqzlbul.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtslvuvk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqplxfeh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiabrdd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2bofzxyvm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdjvztg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrjvnfz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2clfxiygm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgcenkl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dibpaact.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgjsvvl.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cjudrtbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dntywztn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2fugbyjwh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzufyvl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcprwqb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmgpkrb.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjazrre.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gkldkfab.html


<!-- 参考信息 -->