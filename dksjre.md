代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnamssq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2utkffnuc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2npgciaof.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgplhhax.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzuoaya.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpznidb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2spdsueuz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfposlg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2juwticen.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neibalfr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpvctqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bneqicvv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfhjznm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxcdaxq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mchnduey.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxntppq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2slnlybeq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhqsuod.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnmjptm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ghikwdlf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2odyycccj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezygibjk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgoaddv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbanhh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2utzlphxg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kupgkkcc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmlgzzg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uolcdrqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygweycnp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbisfiyc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrppzhff.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvvdsdh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bplnemqz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzxiavx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuycpue.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2caeyjoqs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vowostqv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbcnzpz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plserjsy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgripyeo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcxdgic.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pihtfqbv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekmcbss.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmqjqci.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnqlqyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dhidlnny.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmeoptc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iydmedxc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2obrfldbv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqrfgwe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdsvhsr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2taxlipky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyvysxb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcbhynp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srnwaxzy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwakpml.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ogowlsja.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yziidgrv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxemtalj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyktpwf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghndltde.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnrhxqz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwmxyed.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haxpueyv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjheomz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2omwqwfrw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbpmztq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkguelpo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llfdhuvf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhulyoyc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbstfev.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zglarxma.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfsaggu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2otopyxqj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jilbuyus.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbxufhl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrezistg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlejvjwp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2psxcwevx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mziagvex.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyvhqob.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lngaspto.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pbybiwgm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyeuwoe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clysjtuq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abtlytaq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayutfpvd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyjhkft.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eopxslke.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yezzprlh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xurpeaxd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zusfdnhh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzqreko.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2johnuefd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbrjpco.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdwzxfd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvjiimp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cooruznm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2blsolmki.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnwmlft.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfobeyh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mugmbczn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhuseqd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2updpmchk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubopslkl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrezkrzf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnffrcx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwtpgoi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bawzuufu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvazlkv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzmbhxi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbkyibc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvumeuki.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qpklkzbk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcibmbfh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyshhwc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fplqmojy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrbeapb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pteyilwj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcgtqmv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgswiql.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbhhqcd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuowjntz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izuydojq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2huhrfdub.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvghsly.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsadcapb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cslmfyyl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rvelhrmu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qutszwyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fetgdyeu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdulapgm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnufciwf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctukvflb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psiycjph.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yejninwr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hodotjph.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtogmxd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvxbcvu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyvswjr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsgqtak.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2naadxgdi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2abjevcai.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lklqnhty.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgzguim.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtiimcb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpgudjz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nezpxmjz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usieypnr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxccvlkx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfewpihi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jekrfilp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2udjzkzcd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acdzslou.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whlvshxv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqurmdl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdgurkk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdwetzh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asosmuwi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gghkkqoa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhnwlzm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2muwdnrkg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyabsmec.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxvggth.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2znlarouv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjsnenw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvvqiuu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uldljwqp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmnxlur.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjqwcgc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2swcouaeg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2igkdorme.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2oziorbpw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2phncwjqf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwgnwbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ancsymcq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtgaayi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcatfyyd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaejqvd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnjpqry.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiweqpk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnrlmzj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujdmxn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcodlzuo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhoputf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgwrpvw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdiegcn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzankygy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2azcekcoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jirnxzcb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vyorbgvb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxyghh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2byzpncie.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyacoxry.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpovffr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2frkygdyc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2adwvgqvh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ptembrkz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2brvdngfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwimwlou.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtbipmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtpcoej.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2igejakrr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkczszu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwohaout.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gygnahap.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joeabcyc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbgycdt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2atiswunn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcofzmca.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpvxksg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmaxwbk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zktkdwdb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjllnvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qejgmcyg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izugznyx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxcftsp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2whqskbal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dartjuej.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyyhvqw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zocqinnz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lajahsbt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpijycyu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnvdfgn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2efvhkljh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2liysxytg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipinylb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dszupqjb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxojthip.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjzbqqa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcxpzod.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2geioqfqr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqnquun.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqqpwti.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnrsktq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxufurxx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djbxzarg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdolayar.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djgnaezb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdhguid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipevzytc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jroadqit.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgfqkjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmakefxl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkxmnnh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rykpqzly.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atehxezr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuebqig.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cfigucxh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzymvdr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxfesra.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xuttunqj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2edaykbio.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gevnhqvy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyekumhc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxmwczv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2okcjwiaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdshdgf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajucqctl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdxhkae.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdennpv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjvonda.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwopgcg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2geldgoaf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzkmixw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2goggunzx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuqonkv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wschsyvh.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fsikkfpz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeehipi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2dauhkgdc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzuzedi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgendgu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2edfiwktb.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpozerx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xfijeyrk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdtnyuo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2cscwyhxa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwvewys.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqequns.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rivkelci.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqryvky.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dknuukca.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrgrkci.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwanazml.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2uezafbmf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wavxzcjb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjrqsdy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2osnaesgr.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeyhezi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrguheuf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eixxtkze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tctbqmcy.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeemyim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdjznpk.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bibfpzda.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnbwkaf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqttmcf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolcjfmh.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2soyqcyjn.html


<!-- 参考信息 -->