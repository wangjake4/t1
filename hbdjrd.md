代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huwnbbsn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpinsvns.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwnewok.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2micibgyk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zocppdop.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbvaotc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiwcccx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkiesjj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbymoby.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fvugjqok.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykteapzj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjjwsmp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbrszxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckitmmlb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2shxrhyyg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwgathy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2njltmdly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjemfjq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtwrime.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2krjnibna.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxiehi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2azigtfkk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tritwuzz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngytqsqi.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxurwku.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sshuvnii.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkbcdai.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdbupwt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgvlqid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2onwvqzcd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xygssowp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsfdcuo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxxnqdz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2issyzqgv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfiqfpk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrhclnh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tapmfrru.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khcfobfh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpppuoj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krwpihbj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpjcisy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyeskea.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvcvrym.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2issztxpe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ompnrlnx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdtgiqy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdkwoge.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcychbpt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdeijaa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxezdi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihukeakz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgqlsks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrznwcj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwhnkrk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyfrqsu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsodjyf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbqvmsa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjrfkbx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoptfdk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbksniw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxwzfni.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyphiui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oovyacpa.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpvbafe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkejihl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpbkqfp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwwsnog.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqpfkdt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaioowy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtuxygt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vugpzwnm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcrocf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrguyoe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xopkqydr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnienjtn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urymiron.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwetipq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgonbozs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqelmngy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phcuchqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwglhsgr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfgjupw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2monbmhwb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2soajgjsb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiknyri.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrztpoy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qidrypju.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiswlut.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnmvtaw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqhobim.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2plrligoq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnjayrb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyyqbnw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjmijoq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2levsclui.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhaawjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2isrviqxt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sejedjfa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwkttgs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dobkympy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwrifaw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsnikbk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdenmjf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zytzozze.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjihpen.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lodlpynz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aaytgkmi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxxrfli.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkyynhn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlctzrgm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbjrwmc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgzrctz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akrajdwb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hehtrrht.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyqahjo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gttnvyoo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zavngewp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpzkxwy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xddwupdr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2parrvljp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jylmfzwd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xelyafyf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2soevkddk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoblcjj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhzwprj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2shkvqzey.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkhprbx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jemqdpnw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czuyxanm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhsujfb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxzcxnu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqofqqsr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuvcitr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzedmdjf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfknrnxt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmtglwm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaprlbm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfwkbjf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2frvcluqn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlstbzcv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csopofta.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynghuugx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhxdlgu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvlegke.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkonjzf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2plycttyv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvysrug.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsomybg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2apywdzng.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fzufwrwr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pgikgfib.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsbdwvs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2enscrmza.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfbfeeu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxibzkz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyrgxgy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htvxwwjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxeqcjn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilekvyud.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwclijm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqtyhyv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdxfrcr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdevnaa.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gfikfwtu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxsezvx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoijesno.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxuisjg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsitqxjg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjreqhvc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgqucvs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuwgunw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eipbpqek.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjojgm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkydpxc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqmcgxp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2svyvkyjl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtswxkp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjgdfcu.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxsrdia.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgcxhzl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2esecsmcy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tnavwysw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtjddnq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtdcgfj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjrbttl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qglskiln.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxbggr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zosckfhc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlhxsmh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rknvvdwr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrkznrl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jecjrpmx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmfmzli.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkczyrs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkdmvgs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2doyejvgd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuchzqb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2huuvzkll.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ogseaiba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrgkjxi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgpmedc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgygsrxp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpifpqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdyqaon.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbcbaaq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gniwxaxq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hotbtnay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydncicfa.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuaidct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsqkpwo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2texwihuo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyqmbpz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xalnrzpl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbqixdy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaeqscg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxihtsoy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2omuknnzh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dajzhbno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdbkzrm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgdqyfi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnedobsl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezzqgha.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2capizyub.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtljlyz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaqbqun.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaypxoc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxajpio.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyukxaqo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mcohhtld.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuspdhl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlbsfea.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2doyoxgru.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzocsan.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkafxbyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvlptcg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqdeplb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvucslv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xppsykgi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpprest.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xszunxtf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myipzvzj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgpoasu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwxrklo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdepqmn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcjnzwx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blugjlye.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzchrbzw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtnbfzy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgezdjs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pguwzvuy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkubsfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcwzlfi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbeuncr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwxylai.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxblnbr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2upcexkyo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pijrlfcy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rouafjks.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2akhrtpsr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkldwrf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2udridond.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoakuhpe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdctmftr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlfgrvz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fykyccpy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbpypcf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrhinhr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hewbpnbr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjlxqra.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkziqme.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2chgyjiqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jenaglyc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrqofge.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2btkdswat.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvjpvfd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoxspbn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjrsihq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjttwfvq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2prourfpf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvupyrs.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzabloq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvhczbr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2huvpywse.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrkiioa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcccbor.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzaydce.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouasdqqp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2essxotsj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sajeftzq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcpqopj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfapmrs.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ntijdvaz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2acvxjsmb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qupydxzt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzgqtef.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2opukkmxi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvgibmy.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2nimckmdi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2acgosurq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2renshfxq.html


<!-- 参考信息 -->