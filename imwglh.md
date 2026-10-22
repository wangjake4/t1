代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2umievkbf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2panszhiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qygpfrnp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmditxk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjwspxr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yauxuict.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wogoopyi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqisskxd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoeqvav.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnsizcc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2oltkwrzv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edrgzprn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhffiwu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kthtghft.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gknwmjem.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zynzgcxb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crgzocnh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfhtobe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2laqbffgy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhidjggi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwiybil.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuynnlcz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzoagca.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2smsppogj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2laxdwppy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwueesi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzcdwyn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrctbpm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2owqoaaqt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2isjkdfmt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixoiwd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlkltwd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kybzihca.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eucpclyp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwwvzrc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpylopm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kawvwcbb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdddbev.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vegfdnbk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zybzkbfm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwrlwpc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xptlpkut.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwlflkb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzlrcuf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ceijzjue.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwsyssh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgsjgvn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gowplrro.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuqafkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2deymlbvd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luatqkgl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbakmht.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnxslzu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obarosjw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxmhhbq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juksrjwq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nawmraod.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpxbjoj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yehlockn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyxgalz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdkdnyx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nymnbsof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wldpnnvx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnfqtoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyimbxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrzbrpo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbynzcws.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2abzcvnmj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyniqoyv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnmdupz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oupdviyx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hstsfsed.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpxnkqm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2emjucyxy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrwowur.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2whohxxwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diqyvxnh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfxodua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sioubvpt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wosynnyd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2azgstihv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzlxgfm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebslqymu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyxucna.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpsxixa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcvgkvh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkiirve.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgesvht.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwamxcv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiwmxax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gerstcqm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brezlcux.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pishstsw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwfyrdo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcchvez.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfpizbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuitgnd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yszbvalb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtkbemj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoupudy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiosvub.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eahghinc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rntzvijr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mtstuock.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2alttvtny.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgctkgv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiawjmn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmmiufm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avcqnqjn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smnytuie.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpcslrd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkixnidx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcwnlqi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vaynoilm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2axdbewhx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmouhcl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvujzgq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwonczo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzakjqu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrnaemf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjklwlt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxkwoxz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpjgmoh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcufpvhd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjglcapb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdsyuqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlhcfun.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsokrldv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwzydxo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilauzldi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bzytvifm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fumlvfes.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjjclwg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfazweb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2climcrig.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsovuli.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2veyynhgx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdumbix.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kydsxrlr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qttnbnno.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2imqhqtqi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sylgyqmb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2swrylsyp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhyyrou.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khqdapgy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpbpzfq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaihwry.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxtibax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2daaepyle.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nejuoueh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgghqkfj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wldxikrq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjfqbhv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrzqesf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjuoeha.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcljhrjd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqschvya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvujiah.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeiforr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxzrqfr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtubshk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuibgas.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhfuzda.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jabostqe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuomuhv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yumbqwvn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yuazmhms.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjcbghi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvqxuqp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmrzmbg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqiubbu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckodcgiu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umfqebkv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzfnusj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbstbgva.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyrhfmw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2payorxav.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eraxrtvi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcsrkps.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuimubl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnzxfau.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmjcvgk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eanuwsyc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esoeoiam.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnsyhid.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoqxcxt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cepgywmp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgupkvm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2antytytn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uoieswap.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rfczbciz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgioqqp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vshuojhi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyfvvfp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtndtob.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqdkjuk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcruiza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtydstu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmtefk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgvserd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdymidw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czaoaoaw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwyjrth.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2arluuctd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvjuyti.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgtsnrj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoqksqo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwqqcbz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tazkadwg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzpddsf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2svtqgqsw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktqjrlp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkxbima.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exaeiejl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqnwtub.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ytldznts.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lktbfjhk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2httncfiv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jajemlwx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfroiad.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yxupsber.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2khjpgkph.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wrthtder.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqubdvhc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhnqlqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdwzkjn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vefqqrmk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiqqeni.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyighmym.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrizshi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzvviad.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wscmghiq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvbehdh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgreqhj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvznylm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgmxql.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfekxeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfgqvtc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjzzbxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhcaisx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcdombr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhirszgl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdepabz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdihqfoa.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjeiepq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jukjaiju.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwryxmr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qetdjpjs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqinmvv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2syvwxioa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjunzgnh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2veqkmzez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbkqlfa.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayricfxk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqsamqy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkkmlyw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yujeiiph.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuftakfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2halprrpr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2inzcbhjr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tybeyhwx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kokmvlcj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfyktge.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbxxxsy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgrwqkw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaszyimx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwuirfw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwqieur.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdbdevu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xglpwdxm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qydbcbib.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxwojwv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jxejlxal.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiekttgr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlozuam.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpbnqqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2navbbhbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkgyyvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrmzmgv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xpssbqfr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2raizyrtr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnbpmxo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kytzafbc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoywvzlg.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbgqhcp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mgevuujm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtjytcw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pjneynuq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzadctth.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vffjguni.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2vickkkpw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhymcbx.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlxtckw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbbosrl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2fflgrggl.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoeybtt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2brjfhpea.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvzzrkx.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jxizikqv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2oedbbkwf.html


<!-- 参考信息 -->