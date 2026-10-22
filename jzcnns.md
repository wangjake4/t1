代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuvtkxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkfyalo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnrtpkl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxhbodk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2oukdpzbd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2iadjusqs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xccgzjst.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mppwvlkn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcsyuqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkxcihd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvogrta.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjjgrfk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlakax.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzymjetw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hotcivcn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2opcqnpup.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzdpwga.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbngfftd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaqllko.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrpzjjb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdkthwk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxhylme.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2foynfvbp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyslmlk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgpkjmr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqpewuz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsonglkw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odtrjjdw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lotnqacs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uphkgkfc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2iemliqyc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvqncpv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuchjxt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkkbcrn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkskkmso.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmrubsx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjqcops.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2auevdjpv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwufiypn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwahqsxd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dyprjtnt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyajizu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvjakot.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kseeyebf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhbbmxx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrjaind.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfvwmun.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgomigc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkmqmvd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cuumxwpf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrpvbfu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2exctrrjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgnxgdl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hqimubef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klhiplev.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdyrjjc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mbizigds.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqstimgd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evvrkmyn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snnogktu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibydhpyz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqysabqy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kevujorc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cctptspw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvphalez.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2stbwfycg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhnoza.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aypmhdcp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrgypkc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzzgkxl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfmrojf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzupmhcy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdlzryt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vnurhtvu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwucsqjy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qdblmyra.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnpmrqa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkszmjz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqrvdwz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2maetqngv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hychcrrt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpdcnpj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dujyhboi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoaewob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhbudnr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2folqfmnv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thoakjrj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diodyvyy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avmtlkuq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bikkwgxw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxiflhf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2itnqouyd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hinodqqo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opjvqgmj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twqetjqu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cluvigsi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alfycvfj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjfslyv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhgweto.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujknrbdb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2efryxrzg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgoylok.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqzkuwe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obszztpj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlqrlox.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxjnyhk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwztqft.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxkehho.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2psckqpaa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnibxzv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcwiyex.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2buuftrey.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaiouhz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvkyejd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhqqpyz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyxttzm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sldyajef.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2byzmuriw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdlfvwe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgtltyx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbysslb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsalrmc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yghaszoe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfvwpji.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxheezq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2akqfjkpu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nziiidem.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdqwflz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sffjysxs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbtwhce.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfwxfob.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdezeftc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czbkayyp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xclfxpgr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtmigwt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdejkzw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmgniru.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjdktdu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtcoquj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfwusk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzbthiv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrtmhbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnqgdjm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2butjlnju.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2edusghgm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oiawbvof.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2klsnacms.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdktdrw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzocowh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxikzfg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spmzynrb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wthezlsc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2olllddga.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xllsxhwd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqjaipc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2unccuinh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpwlavy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdaesmz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhhdfur.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiyjbrl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2obihkvlt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yulyqxbr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vchmuapu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdppqqp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2acwjinot.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcfgwku.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjzhtzd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lszpboys.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkjbzbu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2inwtclmg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bofswwmf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2emeeecmx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zzycuaej.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbqwsyj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2arlpgysd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2siadcwdm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ealczfwl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbxplpb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgqzhdr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyfelvg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpusivzs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2havoggjr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zytspckf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwfzuae.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2whclrwyq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtfdihg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bonwvbxo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrnooox.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnivacc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hufpvbzp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jtektyar.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqlhccx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwztxhcn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahonkcpg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwckqnci.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrtwyyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgheqfe.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnhzcjd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxcnlfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cprqwwim.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmctauvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xibiairv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2idvizxmv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvgwobb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rphgvomr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfalunb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhkmurt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvxgcwl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaafdup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uavecvdx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btgnnzzg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbomljq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyhgvoe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axsgfult.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoewbhwg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzxsmdw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwmyuq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tikndsjm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjllhgn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prijcumv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwipdow.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrwijgx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtssccdd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjhvtfg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfxcuqm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xggiumvv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2upqajpiv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgqejvw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnmjvrk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaqoswx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aekggrvc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfkgtpu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugghdtdb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muwxzybm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsjrass.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2catazlww.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrptdrm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nthmypth.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xilkgvpw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqawvs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmzmiaz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwwatqj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axxrrlat.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ththvtdm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxrvumz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxjepge.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwctpesd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2gszfbnqo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhqlcus.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjwizhs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2swegvars.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2orbgpnrw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoevkuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvhzett.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoqxesq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjlmsop.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2btxiyxny.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhznrtqd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrgooqu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbalpssu.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcavkbu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnazfxrv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2guvizske.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qibelogi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqjdsns.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dxohftsf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqsmmdf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzynqhc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbxqqbf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2chcjwxlj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2acbuxkax.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2proowxux.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2iydkxyar.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjzgwhn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxcjfpi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2psqzpcud.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhmyrll.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvrkdxo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrvgrcf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onibjsov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwturvtm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2paqhlqat.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtubjni.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaksymb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfawpzmc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvcelyq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyzrxer.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bonymzfo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2oezakmca.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuujznu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2abdhjhus.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2duaacuvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgipwjcc.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaufgrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neoadmcg.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zybnyemg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqcoxrk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2szgygpdi.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwywbvy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eixyngmp.html


<!-- 参考信息 -->