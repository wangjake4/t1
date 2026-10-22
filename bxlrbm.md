代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkofkmgq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2seqepjhp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mumspeem.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2unfiwtxk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmsxghh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxmezxd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkmmevq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yijdumji.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dubkjmby.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2avjeriac.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwvppoc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnodbrq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqujjcr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rddnadfg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqbswkb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spbzpcme.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwrarvm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuwagfy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgkkcus.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2idzffcdw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzvwbvt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iweqwzli.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2avihigdc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxntkwxb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoghafsu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnosyqk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwxijdn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2psordudu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmrftgq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2btsszmrf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpexbgc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqadouhm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxmhrzj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jilkbvxp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfthblw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2utqhwzuw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2efsagbbs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdiuugc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2stpnltbn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxxawjc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnqjjlm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2swjnzudq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmlqxeh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bocnztwk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqdbsmg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsgwyai.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrignms.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2phhdbrgx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdxuonj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sigevicy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2cejbecbd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axfwtfoe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wskinkqm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxhielg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjtndmw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbcalxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jukfzdtz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mspmajxz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxlmeak.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtxtmab.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfflqc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsovjzl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yodomymm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxzkzlm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqcepen.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyibcxxy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhdppgz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffazxnvj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pijsxxst.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qngjjbxk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyulrpjg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bojlajcr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvyuabm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlplpio.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2acwuhzgn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhvbrtq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqzurke.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlfnauj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfluyfwc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfwctpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmicazbw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ygchwssl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2horxtfdo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cezfljne.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxnnvbz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmljqwm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iplwcnqv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiocdzc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dazyjndr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyswucd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtvfmii.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyysvvg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyztreo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgdhrac.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzmycfg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvrgqbe.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxllgdmj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvecoztd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxjewim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrqgbbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgliiew.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhalxar.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2afktbzgv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tamluywp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmqzlgg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbedgouj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwzifg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ihegjwdu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaygjdr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsgkzoc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tesrsfwz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaptlxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvuxbxe.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdpytzy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhwvhpe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcylmnlz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhduxt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njlgovka.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2litogvvz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwhpsor.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zklzcklx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssawnaqq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpfulgn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuxgouh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfururf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhhssta.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krqtjmxv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcvgxfd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kntpwkxs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cglthyij.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeriwdg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coiurahs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ignrnxer.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilinraky.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oxogsvlk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srdwibje.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxakptf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzunspd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnegnxr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqxyevu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdarvwv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdmvsdv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnioqixl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwleudg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pnffgzxc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzipiuxt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wybartfa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkabjgb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asapdici.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mglmsgwl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phsujzfh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiyiyzf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyuqlgn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmxdsfl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkqlkja.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2psooqiva.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hsydomeb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsycrrx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vunjbzph.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lytualcu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svkimjcs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdwrgfi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbgfknt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuvnoxc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhumbgr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gebpomoj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2irfffqva.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2njemkrun.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oifrvdhi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzubtmf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pugbughu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqjjrxk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxcnado.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kzggised.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xaocfuat.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhhlllt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tahbndiv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czizkeyn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoewlaw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqadxoa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tfievbpi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpncoobv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkkvguz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqajvzj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaloxxh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcokavbt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuostgzn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etwchrlh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygptpapq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2plysbtzs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcmwrib.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgbylea.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrtjvoe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2glrhfcij.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrhyjjb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kihhtugh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jppqjomh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkolijp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2grcabrzo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwanxfs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoerxcl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhtzerc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2okrpfvjs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xuehqrwd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ximekwkc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awwhzeoe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrxeiwx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2spijwwjf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfwveee.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hhadjroz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxdhcoi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iohnbfuk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tetvbhhd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iitkiive.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsqhtmv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoumculm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjpxrzw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpshjndo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khnvbhpd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vbehmoza.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2evkughfc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2exavuzug.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeljhrt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2opehfwju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvjyipc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2whsfoqar.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbyoeba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbldtuci.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqbsdad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwijkbco.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2efasrarj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jswzplff.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxhsjjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkwgozj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pljjnsaw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isvquvhe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjetyiz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2udirxxiu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycathulv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2soekyzmv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjolpln.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvorcctk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnpayjp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rocfatsj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ispgwodf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2twwhvosr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzirizwt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgxxfvf.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtosjye.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nylezycu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuvyqko.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2naemslga.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmdwurm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyvxccc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cakmbdpz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfouqwz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjrwxrv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpjcynp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbunqun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vufdfllb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqybajtt.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eosmwjvs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qswkfcfk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubevvjnj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iygiikla.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeancbcm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dorcwkku.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2aaefjgwe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2czqqtrvh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbadkhx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmeymdc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtcnjng.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktxfpqc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwflpje.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvtuexo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwqhfvg.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnudka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2witmplsc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbvxspv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2aiswgoyt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqatogim.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2biiiblgo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaimvrer.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cczoefcs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nigvgfcz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdpbmmk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnmgvsb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2daivqays.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuokvrbo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fptxxbwy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzaybuy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zteawyzg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tovlznjo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qbktesbz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2arnsrmjs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzwncrv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmkxyrh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2koyauufs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbubiav.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2omcspinr.html


<!-- 参考信息 -->