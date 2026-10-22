代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aioeplyh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpnmup.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdcdahp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzipwc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gorqptbl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmjwmmx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lewoxyzd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjxclus.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbeyjdl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlqwiid.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvtpqyu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giscqpni.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwghliym.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yelbprxa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexvovw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vghdhvxp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iserloto.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnviger.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpxctcd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxqths.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evuyrqiz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpctcddi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdstbie.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbqhdkm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2icttegoa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qajrwglo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2effhvvde.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgfivna.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjnjzcd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uuylmqqe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dikvszkf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qztjevnw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghyrolc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoqaius.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvblejdv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxfpkrb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnanjnf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2miacmzhv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lraeiwaa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmvgdha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgighbqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzotnlhd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfvwwda.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqozehuf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cjovnbmv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxnrxaa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnwskmd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pujjucmg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zodgclfv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkzmkwm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jiktkfqh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzugdxxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkmikci.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ycscthkt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbjvmni.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzvdgrq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrahzeyn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvjshbq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnsrtvn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blhnrwmx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdrjgcc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpinsqba.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uezlayeq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvzkhns.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvjwbiq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slxquxoo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btfjjzdp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhifrsou.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2phwphkos.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uefmlfjh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hckukskr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpegdgr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kddzfust.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2avkgtdsa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wqryzfzr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2godbfeyg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdofrxq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2glwvypxo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcllkkc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ottdfdow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bolojisn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ecszrxlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkkteqc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2czuxdquw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ecifhoec.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpubqmon.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoswjxt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rglqcstp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqwamvl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2myihavsz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2colphvyv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sixqreya.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfhcpxn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fddyvcxw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljejnhqx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anyzrhuk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkszmyas.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egeuncvn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2utptytyj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxpsjqj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhmtabj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2syhbhvoa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gujuluvb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvpkwvb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nyphqrah.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2htidurrt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqgqobs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjsyvib.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwsxnsn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fklrmutv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pgykorlr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzzimnq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiwoftw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrkgoum.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifenhfsz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwppnjnb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vateeqbk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuegfnhn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzkzejx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2emiyutkz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkndtpa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clugscrs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyflrklg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxouvzgy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrecxyh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyqjwdi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvvatnq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gexejfnp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvgqbim.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsihilox.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhonpuh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eampwsoe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kynisxwj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkrzius.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tswetisg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmwambt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdynjnbh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvtblhz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgcpmmi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjjclvs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjuruwx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aspkfivo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwuwswx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdpxtdc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pahwstvu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmxyonj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fzihxilw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmeikri.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qowukzgy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovszrqmz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oegvkond.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgwqjqn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrekyymm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aaabislk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2deumunlf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmndtuvd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsnqudz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2donlveso.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpaqzgm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnrxtep.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2suhxpzal.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkilsvjm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzpyxgw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxitwto.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvtixgw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbetghcx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lokeywwt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrinxtm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ctajclyt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwkiggn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwshhgm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxikgbb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsgroex.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zwacwvvx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwztgya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmztljto.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znhuprhn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvlimen.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlzlxsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaoyqjf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmlbdaw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxmcyjt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rktubtid.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeagytx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxipmjz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btpbiiad.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjhxvka.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xisomtba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqovqszy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2suozuvkw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbystubm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xuljqibi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxjaskz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wazuqkqm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoksgoq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkncysz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iimosamo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ysirvwpu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nakhyews.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfkyzhc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wiibquvd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjzycrb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrgcafk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yskpszsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qietngcs.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2daopzqsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2incdodup.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqzzppf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2snrdwolb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qncpcllq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzydqkf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sznxnedt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bwycndwt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gffydtun.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigcexhs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hphjxmtj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbwvew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwsxfkz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2asyaqlwk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jkycdwjf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2frfmcnrm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oggabdei.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydvfjcy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcapexz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cidfwzlb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zsloweac.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjeuntz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpezzafj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aaevjsoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnotnzt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gampytks.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2exypannb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kagokjap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeurlddm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvmytco.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsrnxfv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dbboahej.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqqyehq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoojfgl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrbnfaj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qldcrtha.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvrleku.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkuwuom.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlfpobd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqehwfdt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhtntxs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slhybarc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icttdvfn.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnezvtb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2irkdmbnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2grjyyzcy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsslhjmi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkucysw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2piqhuyno.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfburvlk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2onynibfz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhzgegm.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmevnnw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qidlmsoj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jywwzaet.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qknwtacd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phqazcnh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvgaerv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfavtqe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2asytmpyl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcumaxt.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrvdylf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmxyeid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fovdbogn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbstyolh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxgcfph.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beinyoew.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2brxssoyf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrklyz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnnflvh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkuhhzc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kfugekud.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wowmykps.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxfdpig.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjspvym.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dblpytvt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2knqvaqvi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2goennqki.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzxuvjd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrflexd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqkuliy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qskaffay.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwijfexb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2syrppbyy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tivjlfhn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyvfgvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqmwjnl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuzduag.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdaifqi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoquodp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bihdxmvv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkpzawg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbegozg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnamwom.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2egmhnqiz.html


<!-- 参考信息 -->