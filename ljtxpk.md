代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pcscdmhw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmxxppj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2clwbypkp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plrodhrg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uucsmagl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oahlvixe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2icogywte.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpffkra.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2niqpdbua.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zomujngs.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jopgajay.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubisndwp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlteqkpb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqhjsx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsdxxki.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olbcmmeu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbymuaqu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhpjsrm.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwixtfsr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfumrbs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cykvhpcy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwifhyu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfspsmo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtooten.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwcgbun.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2doawnukz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbanqfbz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pexaptxe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkciclfk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glaczgna.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2relvznmx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eazfusok.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwrjjiz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2brpvnexm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xydnaimm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbctasw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyctsgp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fldvjdbq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsvthrb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tdveexsf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kebtcfzs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsyqkzg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vytqqrvb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmlajei.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rlradsiu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gywwioao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfyowua.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmctkyb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giahbkqz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvjviys.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zovcmqpc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoymuaxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzaqfuy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frwgwqus.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krextinq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzttpyal.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvslmenp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofojpmzh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhovvkb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdxbxqx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2onyidgiy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oszeoszg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbegpqy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yuprxbqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxadnly.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sccgowwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dudslnum.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2byaypogm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrlagxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2neknxgfp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2adbdrqas.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2owouksrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdixpzju.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2haonfglh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxtlmvg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qigycoqe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvpxpym.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuawfkf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hblvjkoy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oegsweqo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efkyqdbk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcmuyjj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhtioe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2murxsfta.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2heyvbxsh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2edaizdwb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khiqmlzh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uglglwuz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azlaozum.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2armblshz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwqyvke.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdysrsc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgrfvgg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtrthks.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2orbdmvoo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwifdvd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbmrwfb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sansoanp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvlicai.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyqfzqb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxuvnfa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlbjuvx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vehqhpvx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfonefmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slydsndf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwfuoic.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcjllju.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tipegwai.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcudngo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpazbzwi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnrbkzw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oneogwsb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvllhoeh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxkjxr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeajtmcl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edwuknce.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hezyzseg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kghmpwim.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtvegym.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhxjass.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eponawyu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnstnhz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqayiddw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxpgdbk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zccrcziz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vugmsmvk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtdtvub.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzljwiq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdzhkxn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jyleuaop.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgqisvc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeghxbe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2efrhmknb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2spjhcqqg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2delflmqs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2klguxlzd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaidrnt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvehqfdc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zjathuqq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wdreflmq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkinlsoh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdzumli.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnolzdgb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iucmolhq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnqailp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eozveuvg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aojybysx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnqeqfb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhdactp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiomtha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2taugioam.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbfbbtm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcziqyah.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcybdvo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qusggvek.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaolghza.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mribhcmv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhtxjap.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whemjzle.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeaeepr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqtscsr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfbozkh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvppxrz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaxbapi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtucfvu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qbncezgq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nykzzcdk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgnuyyk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsacpac.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2netvbcan.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaihnmyw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxruhlhy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrpjnum.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgtqzdd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewozkqmt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlzuupu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuowtbk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sndinria.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfaabll.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgfohel.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfqewzu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrlebrw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickqlygc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nisuiwue.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2inqvdlhv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2djxaellz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxkyazg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzunbvl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdgzqql.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwrqlkz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyedrrj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2azpksidu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxqnsqr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2eogfwsov.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2knesztpv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzeinxr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdpbxga.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcxhoiv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbkcben.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gmylpase.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdbgeqc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqibxmp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kasudxsq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgveyqwl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjncoye.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmelsgzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzayhdql.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyulvfob.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyidvzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rluuusvm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmiudaq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2olmnkmoj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbspblw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkgmywv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oarmzkvw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqmvgfk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dlestzir.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uhezbqqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzaqkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maxufoyg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sksqsqjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkfjndt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyqgfyo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pttofbkt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyajrqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iupocwlm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maxcfayb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsukuwq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqeejvg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxrxieo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvufvqh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2soujjzel.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2paohxyxe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qglaycso.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uriloiqi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaukfsti.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdxfotr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pmptrdsq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zeutjwir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgflxhac.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjqyydf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkscndzk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyymulp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpkeftm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfndnwjl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlhnvfu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdudwsay.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjknudfj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxmumim.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zoimtjlb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwapofk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeioyjid.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfstxpip.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdyxeot.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2halfglbv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtogdzbl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiurivk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zriycmcg.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgaidzu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhjiqoe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qoonkuie.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjlxmpx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lisobkbq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oumphnpo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhvtmqb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2icjrhnqs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbewjal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjuuclr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuntqsq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2swgiwkex.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2krsyakqw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2koslrecr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhvuagd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjislwmj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2txbfryso.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkloxzh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhtzevx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcurpvt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpszgota.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yocfgufr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imofnlqo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2elyphrws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2klfqmvts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcvwhdf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjceioy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbvjeoe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzocuxf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlqhyrs.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rucglmtv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibukrcgd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2alpjhoyr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvpnqmb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aoppyvmz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfcegoe.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbkiiht.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcsznlb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxulxtfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2awuxfboi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yasgxqkf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awshycpw.html


<!-- 参考信息 -->