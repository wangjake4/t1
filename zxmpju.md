代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsfdjqa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhmxnnj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmzorsq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2awvjznxm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmdbxwl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rchabgat.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkastgjs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmngheep.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuyqgvr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vigolrti.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdobqhdc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqcsjti.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrenyfjn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeabgzqr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyziwlyc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iokzapyb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rruymhzn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpidgsq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2igzlcdqe.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycowmvc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdbrkdd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oslgqszb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztalmdxd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2obpmzkqt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzvvcec.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xgayfnaw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlejnjy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaqmste.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2avgzxnpk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfvaglz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyngclcv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fthhzszl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2efnnxogk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voljipqh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jifrtosh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sekqufva.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2obfylfzl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmemlwz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2czgjlutg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkrslni.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2aaijpzzi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pntgreui.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaxpfqq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2chirewjp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2avhafhjl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcysqrng.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxtdxhy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiebskt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzadqfkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzaomfw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liiheblg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrvhziu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eroddzxq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpuufwb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctysensz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkxbkw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmsarum.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kghyjobr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qddyoizu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpykqvkv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2moaygept.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rylgexzo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npxzdzar.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqseptnb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjbrrjk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kniqmmwq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvrkwgw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2imircehh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2smqrrkqg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2barqzagi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsxmkzf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zngqpmyo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2adnahcdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjfjwpe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2atmzvvve.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wflgmcre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ythgrhkq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gixzvbfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnorspjp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ductvrvw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjdpssw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htpearpa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwvzsxt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaijyfd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okdotbwj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkeorhr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeqmufp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlodoui.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjcdfbk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtsnkor.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sapvqucy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrertvvk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdvgrjn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhgzvpb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aissiqcj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqpclcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fogopoik.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2snfbpcbf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tobhklah.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2thnoonkh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uoghtthv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2opvmpelt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbdkykt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkmgvrt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsqjqul.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvjvilz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jijhmflf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uplwtdok.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxphatrd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oysrzbvl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrmvxjj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpepxtd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzgbjun.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2evptzeog.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqblkmjl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbtirke.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bsknohxu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bysdrcxl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwhnwfo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vglqhwtt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdluyeex.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2todqmvue.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sgylwjhk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wygtuzhm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2anwebinw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wewbtnxo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frnbrdad.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clkvlfnd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggddevvi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msbbaxir.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wznmzzly.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wagrmced.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfajnzs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnskigj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vopxewgb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzqkzca.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfprajjp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjtgnlz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnktkkm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnxnjfa.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyoiibj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cttbzhmu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvlzzmf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ydembgmr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfenyglg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haicqzzt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgdznto.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjweqjgf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzrlexv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrayxuo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xazpwqsj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqxxmro.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2catpkije.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbahaja.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nexwzxbi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxonqvd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmypxmsz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2orrsatve.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uimxkntj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aycklhhh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhubpwk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzjyfgz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2absllzbj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2acftznnp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuerzuz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxwfzvs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vmifgvwu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tluiqdap.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2arzggrfc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzrxxln.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxlybzu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizoanwr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igblggga.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecavofpx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywpfikj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlogrlxp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbqvfip.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlhcwws.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfsbfop.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwqvaex.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jccsbynd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izmcreub.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxtuyqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rghyakub.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdrzplj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwdvaqm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vylzhpml.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knlwmzho.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvjiyed.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzyssoe.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2whumzfjf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2djxtkfqq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujudeqcw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vonifrrb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oghotmze.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wajgdckh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvnnkmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrmrbvd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2frubprce.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fojukyyu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uesuvvzq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euejezbs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iryimhhw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqtuovg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkabitsp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqruafw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuwtxfo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzwbckz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2eftheiji.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjinrfh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeazcuw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpowcvkr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2acslcgbk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slkebbjc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zanyhwhv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2eohtotuj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2oisnfanj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpmtruy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gorpmgzt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2grctokbr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhppkgu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoeskxh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcvhijj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqoevgj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2usonpxta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsifbru.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ktexyncw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2henpqoxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplrqswi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oghbnvxe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zizlwkly.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icejwhvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jepewmlq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkcdafr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avptvbxp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xvohiady.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wljhdflu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cifosqqm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzmceuq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdisxxa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gizsqrlu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2khqtojrm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rldagmtw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpwfopu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pusenoam.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiogqve.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnrcxfo.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqicpwk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyceeflo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmnmfuu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqrogcy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdvnteq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzafinh.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbmohqq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2edpnsliu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaoawkw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnqwgzp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrpfatl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnfdzyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2htdglaby.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoqebjm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfztmlq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tefifivy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rychzkzm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmrabx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znnnyrgd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpwmvrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvychudj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuofizpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdpsncq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqzzwdl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqljmkk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ttepoohk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gorkmhln.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tmahfxeq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oicduqpg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxvarkh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2obebvybw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiggmjop.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qvizmyev.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrxqpiu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcckdfiy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2acjkrkte.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzteqig.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfzktxj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkaulsi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxtvmuk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwttorg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pteoflzw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqtqpvr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2urythduc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjershd.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xxupcyft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2flepdhub.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeiomld.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoownfz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bblgkbaz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pmopzskd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2naziwtfe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2culeqbhr.html


<!-- 参考信息 -->