代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qprluyhd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuozctco.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shapnckp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvayadj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knpmmgen.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdylvgur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuerczwq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2feywdurn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eggqhrgy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ziephhcl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqtgekh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtmjdug.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuozilb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ktheiqsl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aairihqb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfqgrck.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrwqakt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgmpejo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfzsxho.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwsmdvg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iimlayot.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiofpnp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kslvgoyt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnoqejr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekysshbc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuwajbc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kipbnkga.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymawvxfe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrwxjok.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jooyergu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzdnrm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xeekgybq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rrafixbp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfsuztb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbvmdbn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jclalvwx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcgwetk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdjhibf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xunnpfdl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwjexni.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yonauqbb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2caqnkocq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgnmoui.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2guobxlsh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmgihr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hesvifrb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwltahy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnwmzus.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyvfqzz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrurbiaw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejnbnhg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaznokvq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hknnyhuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srgxsokd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmsyvof.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrqbex.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmulpij.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jusehtpo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2womwxbzw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2omzgzyhr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ejktvntq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dwouyuab.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2blchmeue.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dgflckxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmdctoa.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2twllxfwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbknpnxj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbebdoe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2drylazxm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzhovne.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgytoafm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apyfncfc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyphrmp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgmiogt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdodgve.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoxidfh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzrabec.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpgghee.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2medntylb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmqvwjg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ashjdgsv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsubnuw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dofhnchs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhccjtl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opkrnwun.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnnzonv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2byfzzlza.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpgwtnu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbbrfkk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oalqlhmx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqqcirx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeuddhz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdxlcpm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhihtygm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hrojfwxs.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdprebu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twajfybh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjmyfmk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxksmsq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2appsyumh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpxduda.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipluelst.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfnnpvn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzkziwa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdmvvha.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hchjvuqg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjepvxou.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bshkeuvb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lulucaop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2potlxjhy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqmfzyf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwbkmtk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xllmwcfn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpcmhbm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrzdpvj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeoguzl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azbpjhdc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alagvnud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpklymd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uajpzemw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2svrgfjsm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oaimtqzk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xskykfwg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iivsofwz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tigtdalz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zijomgpj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbvnced.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwaurgo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qbylxgnq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlyojza.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jojrrssj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2veglcooj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izpqxjub.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqbcimf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhslkfjq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pohzruuw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmrdalc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elssyblv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uazllgtg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2unueumuv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbxaxbq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblaryte.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2juobfofc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcbfscm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abkjehtt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2phdlupdr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnynslyc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvrzwhx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dnapnems.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2aewogjbm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aybxrpwa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqafdxh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfmdaii.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyswydb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqiylyn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vakwysop.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qcavlypm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyjkzfi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dtitkntw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oftwrrfu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcfsxjl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvquqotq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asvwbiqk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2okbvsuev.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzolncv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twebavzt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opydzkmk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jeswhszv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwpbfsm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwvcfsu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnlkiqe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnouoprp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsfxokb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbygsovo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uplcqcje.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irkkwnbx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dltitdjh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jabiwrze.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsixncrs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsutedz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiotqis.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeqvutw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkenexpj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kazgdwqp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xosimxwf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2drmvxtus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywfdwz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2izbikjni.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2oplnrjqo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnamqmao.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqcmgsl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mewbwgeh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeodctc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwitkai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2twcxusnv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaglgrfk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2eptwdmuj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhctzred.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cppcwnop.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2segfylav.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjuozew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtztmyd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwbumlk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnqbmds.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2clmzxzta.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yonvkico.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtjnroi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcgbbyv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmwdlnt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uoplumcr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgtaddb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzfsovd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obsgwpxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hakkrbrz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnesalc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2curmjkii.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdlxxro.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvesasih.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kspnhzcz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkmjjnq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfspdmc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xowuarpx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oblgbysb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zujkvptb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlozwjvy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acqqhqvz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmldoqe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dawpamrb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyohujmt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2klfydipy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqsyflk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvspkrth.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uagyzlst.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtefhkk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvxzpi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzfcvio.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pntmzsaz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccechoxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtyqlev.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpxowkc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yullfadn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxluxspk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xejamnmn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmsixti.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2micfuixh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duyudeem.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuqtbwu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrbyzyv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjxfto.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mblikzuy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfaptlz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ucthjdse.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyttdhf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icqwaikp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgtxock.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zawakcnj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gglntbku.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fweamgbk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkatnjr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxzywjz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nxirueyb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkilfvg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfxckrj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhalyh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuidawu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndayanil.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjmghpu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qwugjxnz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qwukqqmy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgxjszc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2enrjgqiw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2akzoxffv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuezksff.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2whpsnhrz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bngeylfn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tjazctmy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdggnqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2caevebui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wierfjeh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2evlwwkhj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpuhrzy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuahtwh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwnqeeg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2oquzfexg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxvpbqe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aofyvewi.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoldumi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbhckt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnthlkvh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkgitsj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqouyzay.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiqusxu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2silwumif.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gubkostt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnqabzz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgtaui.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2llthzwsu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvcckzp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nubqnkdk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wqucwcak.html


<!-- 参考信息 -->