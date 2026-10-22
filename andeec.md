代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cygzkdoi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2caguueek.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfytveta.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjcrumy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycexxwpw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jtopsxjc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2znpbqpvo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtxwzxd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwykhcd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqzujdj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqafhxx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rowfiuje.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvvihkb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmvizv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvskajw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aazgzqsz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkixkwru.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyhxihi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2capgisxh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaixdup.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nwilimyd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sanxfemb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpriwexe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfcuwsl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfqsmnb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2psufcgru.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnymnbix.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omdmiczn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgupxbdx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cqguyzhn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcidexs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcorzek.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glyqasyi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdnzeug.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrwnafa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eazewwuy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjgiewx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gearhack.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reihqwsc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fprzbhyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2omvdkibb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdbhghl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2npxxduay.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqmuhxa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dymxuyee.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uebyqdxs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2orppyfhb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeihevu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqukugdw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwuutjp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mlirvoag.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmkmlpf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcbioty.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbsdkgg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwgqqoc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2navpghds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldalogmi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwckcim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjwqazw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjcmzzx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tmodajii.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsihhqmf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvgnhth.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fskxohxa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mruagdog.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyugzfxa.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgewlvx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlctoax.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rssxpawn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvtckzk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozahynau.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaehncj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bllmskpp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowskzec.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhfsmds.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lidcuqen.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuvfxuh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tngyllbe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqjeraw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwirfnvv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuswufa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrkzkhr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkrphol.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgvwpur.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpfnaqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xearsmsw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xblnpaxu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxdpzf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeghxukq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwknrnlr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpegmafs.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aieubfpr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmcijwg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2riwmmqwd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqmmgqy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdtfhua.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kxltcocv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oykovofj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpeiszh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vozdawxz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrfniml.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2srdtvvpa.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrpcftl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anyqclta.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2anamfzfd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zttqikli.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amnpafjq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvdohec.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aazdzpil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vndgjoqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kyswxgkf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2peqlkhtd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vczyfigp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2buhgylbh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgjxpxl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaxasbe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrregsl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcropbf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlktbqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2juiudjtt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2odjxlhnh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2inoskump.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2omkodswj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzrelqn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbgdkmn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izscugps.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwpvpco.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnaqjmf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2inwddwxf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdybjti.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdcyvdw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kazmmldg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fpximefj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fchuvuok.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaatsgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfeczco.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndguvfjy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pprlyrll.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfywcgeo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trtxcbwr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkwohdx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2njrzardj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtkofuq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nitylvmu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cuglbhvb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2sllhkdfp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jyviefuu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xutnvccd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqwcuxp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsdfriy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqzcwxh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pafvmnlj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyrpbxo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iimamizz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqtihom.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcimictm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbepjha.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsgmodl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlqgjgz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwgsqtz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thcskotx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdnyemh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ommdyfpp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvqqsnm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2plyplofc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjhlkzx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgnrqou.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zptrdwru.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xguodwlh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvdxsuy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsnxyny.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzrvzgq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2crxukiyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2knkcjwwq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkvppor.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2awkmbgki.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xvygrhkd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmigteo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyyjaqb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2swgsnfif.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvefzpsf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oumbdbef.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbnmwq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyywump.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxmddnh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfgvdyc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2veknbjli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srubbtro.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ayphjcxd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rojoscnq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssimfjrh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvussrv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mccgilop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkuuiwp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aynwtcia.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxsminx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2iexaoefr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gofozziv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrudnhxt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvsrjak.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xensjjzu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gbenlxdq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdhfcvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zagpnvkj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vslylulb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fileasru.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrwsdqg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2peqkszwm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkaaza.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmklgomc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajrbaxk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aofhqytw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdxdqtc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oktscuxc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whgizyrd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sfavzawf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbgeqfk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdpltng.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2babubkyn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwcymak.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkchrso.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tgisddhg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqgxtjb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsubfud.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxovttg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgcocpr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiaypys.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtuqflg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2izjttykc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmrbskl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuqfcmg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrmuwnb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjegojeu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pugusrwf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tpngrmep.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoclhlvj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpzifsz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwipxphx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdylcek.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndedrzuf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnyegww.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpqaqao.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sepzcrza.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xeezften.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwwaine.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyevopke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhusozv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwswksn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnmmist.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2digvbufa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waafbref.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2iowblsek.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxpdlpc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2agbdteks.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlydkcp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eekrdwvy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxavmzw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsqeuqu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfhxixh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzbxrnb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eezklknv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdwkknq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgohqxa.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2duhuyekf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tihyrmej.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yuparbhy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsozbvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwxbiez.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvlzqhy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvzxbpr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlvzkbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfqnron.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2asogxzqh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiuoapp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2djhjzozf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkgqkfw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2monhdruc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2birvpmbv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhmdhqt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxydhyp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxxfccz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeotsyw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kubkzwpv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdmkryw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eyobjzcd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2roovsylm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaqcajg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2avciwmpv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsvebrx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibucbtvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdmehbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkscwyh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2njxlsxwm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2iipaxxkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcbnlaj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2poneapkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlosfhmr.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmsivu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdpejow.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxerahx.html


<!-- 参考信息 -->