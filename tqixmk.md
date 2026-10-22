代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcodktl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvmzmpb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaulplr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdgykxg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzrzdbe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoglqunj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wheycgmb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pihrdsqt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaxxjpy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjqdfxf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrmmmkl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzolvis.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsmpmmq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbjyuro.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bposaaok.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncumdjrc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2phbcstjz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onnqqmzj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nspcjydl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xeesaliq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2spodcftj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwphqdqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2owctmlhx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2llhkohvf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgggsom.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ufznecxa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inbbswmu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgyesmd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkxejcc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iizhwmtp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxaznxw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnmggcv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcprmddn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjuclcu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzubcpg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiyztor.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2okagctyj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlaickg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbzmvap.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtznrhq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwairmf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeaxjem.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2unsuozxc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nryvhtee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kchjdaln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvdysyg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxxsdd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2njgstamv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfaxzyz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xzimjbeo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2odcoautb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgtomkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnylvvf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ntknkgcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkevfkdb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nfojixsq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2thtudclc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byhpdjfk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhxtbmg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihlpkwj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaspnqkz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvzcgfi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khmvzssx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrujljad.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhoknpl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcbwkat.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzfjdzr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksztdjzc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpwgirl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrfdkcd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2omlixwso.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhjiwge.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjqfeki.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiakcmz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2musudbhr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmaknyv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvddsrc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2evvzotmv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymjkdsc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgxvzaw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nurimtga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2neebuwis.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2icsqtgvo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxowaqqz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtciafhd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcytidn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmibeih.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzzjzhl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izcmktuk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgmkghm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgqjuaf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrllyml.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlbnmtx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csobrwht.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyusvny.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmuzetn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azfpvkkg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbwlfqs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcmvdam.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcsgucg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjggdztk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zynbfoqb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onkywlmg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnadzhmx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chepftzx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rshbbgjy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sfakuwzr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqktoow.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuhvhow.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyrnhyt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ththizyq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eckkxayt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gswfckbu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjcveuj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrblmnq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fugimyol.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qnamvswc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmiqgce.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nlinhaxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dludwejg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnsmxkc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drvvoomg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxdmhmh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhujbus.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2znrgnuul.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzsbcxt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvbdzhy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2efrojuig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzsuflu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duylkcuc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgkmdfa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2magjlucw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbenzkw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdiumcc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nytfospo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvevcear.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2amhnegfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lauifwjs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gacdapre.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwkfsan.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhiyhdc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cchdtqbq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2azbvxfje.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ujylwvkm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjtbolt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdpxtsz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tbimyndr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkcpajf.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaeacyj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfawxqa.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epesfybo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqvhpea.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdjpqug.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgufrrc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvilbeyc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2huytdasu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yigqpbzj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqztqlyj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmzxtjj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhvetgk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yocsqyfp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgowsiu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbypklj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpzgmdu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxbmuzj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyokaan.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhyhyen.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bozahzle.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2euhmyele.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjiwnvl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bouimdhh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kmisnmxm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbwbfwn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pwttfzlq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnoxgtb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnwbmim.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlruquv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkowyjjt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjxsfib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gesjsmiu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwgzsvk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwwywwp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mklcjrqe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diefhies.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2znamcbtt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpaigtg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfewyumy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywwdvvr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnsadnr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegxzkla.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tvscdynp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmgrsfw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2isbncqrs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnpzpm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgihpzq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrtymzd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wdatcsjr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wzenctzp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbpmwsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avgpbovc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgcidcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mklbsumb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzdvvqh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeqmrmc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdyvxbr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbxypxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atbcafpn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiewena.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoqquud.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbdmjtf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxksimj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2njooferf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtorwen.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimumbac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2voufpnjb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaqvadi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjeuvvq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ybizhmyo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzghrbhx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszcjayz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdirmwq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2aofzcpgx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2acbpasfb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxiasbd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xovqutmd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2skpttled.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqviculg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmfbyxx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2coqngicj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlcuwne.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mxordbwh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvfcqpx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njsuuhrh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrofxdj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzzscys.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcgmqxc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjfvtll.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjpuox.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndshvvdz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvdyfjb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pefwpqmq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrwtoix.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoypuwo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piogujpm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrjvtsc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2egccsgim.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrynrdy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xbydhupp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyuebor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sezfbhau.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zwesplss.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgsfqtq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwaisre.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kckcfviu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2huprirnd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hcznzedg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuvgbyc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsttgkw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeowabe.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cthcppfo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzqpxtd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyhkerx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtkecgk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsjqbif.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ietqnswb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzjvdqj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2itpcljtj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlcqfpd.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgrlxrb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2girmdome.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdykrijr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2umcwzscq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yruteurq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2bgylbdud.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uxefruyl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdmsrcx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wayrrrtb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykftovhe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzkfdqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llixdyjm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfkdjtc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygpzney.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yvubwvgq.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qgryaglk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjzlxks.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcpqcbc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dsflnqsp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmrlit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qixriuac.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrocdyg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfyavu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyxdhty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpzfmip.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcznuke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqakqfuz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yiivxldc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvjtcsn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prxbhfhn.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqpnagm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpiakhf.html


<!-- 参考信息 -->