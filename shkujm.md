代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2diwhvbgr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmfhmma.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrznzdeq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuucyfmi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoaovcb.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqatkzeu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhswxmdp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zifomlql.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqgqgc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adhfikpy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmpalkm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vclfynkq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrgtsi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwsnvps.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vawksvxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrivvysm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurpusss.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tswccqlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgdifqd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khibdztk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpklnece.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjlmset.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iozqtkoz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmoevjl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyhzfbz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzizuifn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgnmjif.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nitshjwh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2brabwtks.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2elglgnbr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzvwowi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnuryyn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxodpja.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fztaqfco.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvrptjt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrmnwnq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjmmvtm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwuzcah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2woxegcoy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkverfje.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jnchmpws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2smmvauag.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krszgfjo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvmimdt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trwhjcfr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfaebmp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xywrjvjk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnyxgkl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuarqkm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khfgocwb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opnrntay.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkkoiah.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbsxdxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wznqyosa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2psdagank.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeruqka.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2eymlxzpm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbdedhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrnfdps.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ocofngrv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2iycjfzfn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxiokq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sntxhdbh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdfqysa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fbptfznm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cchqctis.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kleegfrz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hglfptll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrajqooh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ryowstdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnsiuio.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2sdujiryo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ymipcvgn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuadikqs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbxfdzj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtiuplc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnbtvzj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsplkfi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyhimzn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrsfabi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvypuwtc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkyhnsu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chqojaeu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnooagmo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhrrnvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkoqwrm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqlkghg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urgrcqkt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdflvxvg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvpvhyi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdybjmtw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gefocuby.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgsglvo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfqwbby.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qswmxter.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lecpfnld.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnolaym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvvustm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2huhxxdur.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jcssylis.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwlfkuo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxqkalq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsamkts.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyyuflm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhjtehm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gkurgsfq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2prpmyivi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mehjsguf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2shororej.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akaheqfo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heoialqy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiqzcam.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqypqgz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkjbmnb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpmffhv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbybnnoe.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwnhdwd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzlaabj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iucbbgvr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exelrtbn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbimwrwn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdzqdkn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nklcrnzx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqcbxij.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuxuvyz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rixjwxnk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2juxbrjkn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wswaufgf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrenjlo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cefyjyqc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdjjyca.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgmhxyq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzxkafv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwndsxft.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmxyszn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2erpjodat.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcgkovf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrvsqix.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbyurhs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfivowo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kifytlvw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgwoesc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcngafsy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2prwgdbdv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmztvcw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baylthzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2khbnzovi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cggxribr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjluvlzj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2faalnqzy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kapbadmh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqoqltw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2semnyzdf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpavpeu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbqymir.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2camufaie.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpzubic.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmoijcx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kckgzqtg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiqyleq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjpvsvd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yssetkbm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2saasnloy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frypjdls.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyydrvj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lratducn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbukuwwa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2duwdbhqn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jfidvpzc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiomtwy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vayasiea.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2knqdwwap.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuutbzsp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jadnhvam.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtjhsio.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meqlhzav.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nutkzzoq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irgktyxu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2klukejgh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbkanqw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzsynqn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eenuuvcp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wrahtgjo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2itxfqtqc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2phmxhweo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkamabb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wscxmiwy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aqupmpjm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zzddwrrs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2khmuyoav.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xxorybyf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzxdkbi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2enwefump.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwgozvd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcstlhm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpypmmi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkihlvaf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvtpggn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdoibju.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmeskcq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjqaoxq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwwzaew.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckesrebz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyciosjn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbdvtnd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuaoaho.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrbucgw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vouedfbo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsitele.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjujoav.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrihwcp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2neciokcq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kifzifzj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxtjubr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbhvwyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoaqwmm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpcorpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iehcjzrq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tjimdamc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnhehzg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txsenmcy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrmchxn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oybahwfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkubwow.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvoegdy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krkylstw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpesnnxy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpsfhrl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2emwcaous.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyczfen.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqjjaik.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqfesab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhggibsk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gperaksu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjwvnzx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxeioyt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsbcsdi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwczqch.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjsapud.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2atnwvrry.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2knodaaks.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzezcky.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gacasadq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2oevncgjl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdckfez.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rggvnuwl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsewthh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiubbzjl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vayitnri.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaeyvsi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwccjlx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfckucyx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chftgxoi.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mywzdfle.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjytnrb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2osrskikj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htmybpfd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiwqiav.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htklgcqi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqljyow.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqhlsbq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zuccatkw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knzxlgjl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvlooxk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkmbmhy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2irklfxab.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zwptiqnx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfpvpdf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdsgptu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfocsrzw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waimsbpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvkefps.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bawutspm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2niwaumpk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkwzkla.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2funkmcql.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sohjljgl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vasjmlgg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmjvckd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2svfotmsp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdhemss.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgramjb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrjdwdr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2eghmzwsm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqvuldr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hucszhxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2prxugqky.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hplsasqx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dlafmvqr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2asgwillj.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcxhjmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2uqehzowq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnctzxyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzhhrmv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiajnok.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnbgggl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zorpmekw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2phscttqm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2swtnuups.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuykuva.html


<!-- 参考信息 -->