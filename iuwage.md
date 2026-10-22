代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlihsqt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2llznojcu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlgsnc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zduclcva.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rztfvuqg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjasxlj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvxneby.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyzkafp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrqojjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyzzexz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxksbgpl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiyrkpz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnwsoax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvphfceh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxtjivw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqybjcwe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2btlpoyxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qftohnup.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mesjpppu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2feydjzts.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwheqse.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpvcxly.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2saryucqb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrdltot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sumifnee.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhbsbpm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjhdhrz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdomchuq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2arizlpfz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbdbqx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hshceaqr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrtslad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmldnqb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egfpvwnc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyofmrt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bahhyidy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrsqwxk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyajske.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvawswlz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khcmlwuj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oagzqutw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msqtheic.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izlqaxxl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2albkddcq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2guqlmpqb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbtnndo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzurvlg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhemzgg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiziufwu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2eezzgxnh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkzsink.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gfajsgmf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyznqyc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dsetbltf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpktsweq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjyiubj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqrkbob.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2plmhncgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgtpfzl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnsxtnv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wpekacgj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roshmvzr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgiybbh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfrbssh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrleidlv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cleqafsj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zsapivoz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tidewoup.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hblbftuq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtylptv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnidqcnm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rssvdupr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfpxbva.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwsjfxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwdydgp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgnhyif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfoevhi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cyagpfng.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkdwmoh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtycctcm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fznrqppp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwtdxkk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiyccji.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2shnjchmn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2djwpxzxv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfpioqv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2burcabxg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmfvsnd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftebglkd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2youkhlbk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxyiymz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdbyxkl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgwksqx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxnkjep.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwweycu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rcehkfhr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rtedfllh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhjofkg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgrpbwv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmblikrl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aimsurnp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2upzgcwxt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zamzfzew.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euaxuukm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2syabrjzl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofysexvn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mccpoqpr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafclgfn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwabhedw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfijymj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cckorvnb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqvprxj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2feytlexp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czqkrsds.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsmhtey.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxumybrm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuhzbzi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlirqiog.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjplmet.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bygtwhqt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2slwhkvxo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zizkprxo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gphhcxvb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqopbpa.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwumobaq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuerxevu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkcokuo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsomfjt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvddqjet.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqewrywy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdzzhyr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwebxxf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeuiqrv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcgmvtu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dqulrfpb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiolfwk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipreymnm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjgciau.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uowqqprs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcqswgu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tmouxxjn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2chiphoup.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2blrqxrsp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmmzgdc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ykevxdpk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcjqqku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2knnyhkle.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nciidviq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvrxud.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtsaucw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyvzxwq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duroivjr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfsxxyi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykblicue.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpzjpac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoywrlsh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvvtraq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpwkmrk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqipyvt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvyhjgd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqfyrxz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhthfwme.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqphjpmo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teyqeqvu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yptxiirg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqjsuuj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcbvcqz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfygyti.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdovetzo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gssmabpx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2smszjhza.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nscvpepv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2titddrae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2syobhxzp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgymtfgj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwoktir.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lilnfxlv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyinxhq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2upgiswwt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxkjclc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2glxozysf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urpykkdz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrnabjo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzjmybh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2khnmnrzc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgaxscv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whxivdbx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbguymh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgyxafs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agsabzwq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivginfvd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjjtrwb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pponhwrg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdinyisg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2omlqepai.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qhesegrk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgezmwxn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdsihln.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxagnexr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxjyraz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fptdrzam.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnfpsar.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbslbzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqfkdfz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxznewc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgowfka.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gldafupy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkquxav.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbrqwvd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpzpvry.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrlbzuv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uejtlgka.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vaijjpee.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcwetlz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkskjqr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlxhqct.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmmzykt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoslhvv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvsllda.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tknfjoqh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bchsnqox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2imkpselq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2juewymmw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhfklew.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrwctka.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2oopbhqax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzmhcms.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvikcxzg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsumnzw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhohnwld.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnccico.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcljtsur.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqdcxwe.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlouecll.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ervszkhq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hojqylbi.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wukyzhqi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hektwimc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwugldkf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wweulihu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqxwwba.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrxguaz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2maxidrpn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgqdxgi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pujmlavq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lptqzlye.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynechcnn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xktyzucs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzikthsy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2uyouhcdb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qifeysdn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoyrbeb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfkssjc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrrrgvx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcfkrbd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvzmla.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlbqbpz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeihmqky.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwqqeui.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nkissanb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdqiqxl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tciwdwun.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuntypmq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2htijlzmz.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exupkdqd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdynioub.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oponfmxc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2itrehyus.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlpjfju.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hscdgdrl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2aefjchbp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgymqln.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2guhgyeli.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2eokzwzqi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lncmpyny.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wftdvyex.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2drrwhtnt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2khcdlabt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdyekap.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2uvubblqi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajanpkjn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmddolue.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2osshhslm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuqpgbi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxiscww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgclhkf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cykmuxip.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiyepxt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2snvtgoje.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvoaxlb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2meismegc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyhdafl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwnovtd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbijshmj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2azrnrwia.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvttsrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhhwrva.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkdbuiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elvgjbjn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuolyps.html


<!-- 参考信息 -->