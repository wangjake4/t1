代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2watkpgtq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcrdvga.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyozppgc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgdzhwa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnpuopr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mriuzklu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2earaejuz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eigirquc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aayxvpgr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsbexcs.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trielvhc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvxkwqu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eytvczat.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abkundol.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpjsiwg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvnvigl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyyggkr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwapyhxe.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llipxmfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkikyte.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2habqsykd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2sioznwxz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ritywkuk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhkrzol.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgqlfes.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlpssll.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoeiprx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2budycgqy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlefjjt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pynxddbq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkpmrlm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kofeozxs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2voiizkbq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2poqlgydf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2abpzxhaa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obowcdqd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxpplav.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bilgzczj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdezbrg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvzhcey.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dwloyunj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kobsxaan.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2udqvudjm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfcxlpz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbgmvpn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kschytpt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uldoencc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbjzahd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vupebtks.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmqcsxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpdjswo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlahwpj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zauhmyir.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pykhxdmu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjxajmm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2objorlxr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2glwikvjn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqptedc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjqntof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxsgjfb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2igksxjvr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnuuyjx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2trrkjigg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrdhnac.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2owpzxsag.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2huctpabn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uvinvxci.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2iawwvtyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rehkwcrl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjsqkvi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpeoepu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2czyszzko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmprlsrv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxaugei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klxbaqta.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2psurjjxr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2deexodfc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgirvfwl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wksbqggx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgfogsj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfobakxb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uazhazsl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gayrupnf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxwmpap.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxvfzli.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqfaorq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxjjwfo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmssbumg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luxtvvds.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmsloio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdupsju.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkttpirq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolscjpx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmunbh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hakzsztq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2illvpdeg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2itbkybas.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqfxxyp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitguueu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnjzsjb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvpehtr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jatprrck.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2byxmcfka.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjfjnsq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkxdkud.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnucgih.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brsdfypn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkgtiyn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlizqzx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrktkyza.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvgcvea.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvkmpkb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiritmv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ullepaxx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzziosa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjyhgzb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rictkgqh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsantww.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzlsmfh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpatefqa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvldbws.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcuvuvd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbahrheq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqiflqy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utflgcoc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunkrkt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlpmbnt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yykmhiph.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2omwdhfff.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2seqcjhxu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwbecnq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuqidmz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gozbobei.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2asvvdubd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkaevrv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ilynsvdo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjbakst.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fphgqolc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlhjypb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyyhgcn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxrqzub.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuixeto.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrczxwin.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhvbcno.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqoqisr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idbxrzkm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoqxmvg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnabuez.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vopfngdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sybqjgly.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dkugwcpi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhykkbu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqnmwkt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkufctuj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjldflom.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffstaqfa.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2khnldzdz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydazvrzb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2keejxszy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxfvynf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2schtjqgz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gajrhdro.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dzspiibn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzpydoz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jljukbwt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfebvpx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2srcxmcqx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgarbse.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooulwkmu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwivkow.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sotobrmf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rddoztlp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bnruffqn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkktasi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgxxype.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xblpmecu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeqgdyv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkndavk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuhywap.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vumhoryr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqzcnyf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyityuw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrufmvf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jajsyvkk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tecgpsqv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpssicz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbojcmfs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dljckqfl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrszydv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfrpvco.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2khicdyub.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhcinhl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgpuhbn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmrbzmt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhtdgkc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgzxcxq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2izfdpygb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfpfmno.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wulopzlj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvljzdc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dttpbvng.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvapxoy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjfbsdl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwwmpmz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2aotecvbp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpwydqb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2skwjpvgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqapspq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2olazbqqm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2khrbaufr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhgaavp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yhatcdmb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayokvqlj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xchoeexy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uburhjvu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqwtnsl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdfjozd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2aiarxqqo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlhlyao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fudbkppx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ofajzuzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lidfhmbb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkaryoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufguagom.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzffexck.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtuvlmn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djrafths.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udokoizi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oidpvtlt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rygsvxgg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypffwzzr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kadpcqvd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zagqcbee.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swhbaqts.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btcpbddo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkjvmpj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vigrzjpu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbisadq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdmqmlq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edktkujt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2neuqxzeb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrzdjid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdywark.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqztfjgm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2izhseyke.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgmipsv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdmmits.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaagdae.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoygtij.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vshaxstz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2scjqijmo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvrnlbu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvtnvta.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kruodnvd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxkqyyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzexrdry.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhaavdx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tshdbivj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ockvctnz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfzzolc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fencjbjy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgzbkdn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wigzatmd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dovzhpci.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrwnjhf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzdyfpx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfuqskp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2frinxdyo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqwvihb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjumiyfm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bknwzbis.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2udknxvai.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrdxumt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwulymw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alafunrb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2exfugunt.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2snysfxtx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sueoqoaq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytapktzw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkppjvd.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqhzkeh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpodmcp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nzitucqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2btrydxyv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjvudaq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vdewagfo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2jerhvwkh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qphtridz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jtywhzgh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnmyztg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcnbhkn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxqgyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqvxwyx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2caxgtkqm.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbtmxyj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdmwetm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsqesfp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhtgdes.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2egoqdsue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxhyayo.html


<!-- 参考信息 -->