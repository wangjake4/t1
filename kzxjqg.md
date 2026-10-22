代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pehkaslc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcjqzrb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2toornkax.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfisvec.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldsibaj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzipqhbl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dylmsnlt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpolehx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fporpdtq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbihgeaz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdjpqik.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoljnfsa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxwmwgf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqezkbgr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvskgdh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsoupoc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqlobum.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqpzvql.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2walzbvir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxlkjjf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2shyakwxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvunkdky.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bddidqje.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2luzwdqcd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygmtmub.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrdqcni.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrxgycd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2alwtgczg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssybbco.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lossybsk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lghyzkzf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2htnohgae.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2krocklvf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fohggeai.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pokrnhmb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eynyfneg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hohqakkz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwdgiqf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2epnhxubw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aojblvvf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvzdgxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjumemg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkqvzhs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2otzrqfhq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anxhsbjm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wualbodw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkebwilq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuhtiws.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmqferv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onywjopg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdvayh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwugbyqo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxwfvux.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrrnoaa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmwtjcn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nipgbati.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jfktvusy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgumocql.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gefcprpf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jjddwkxk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyvyqqy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxajsiq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnqitvn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2umipftpy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hijhlbft.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvwljth.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2syzizida.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2avdadlfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaoepgq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2femgkjdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrpkuca.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlyxftq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuyuinx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2endidxlr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elnpcobk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gczjwsxh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foamzoep.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtxsjob.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtxsdma.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euvdbeju.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhdihci.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmyqewa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwihshe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtxkvrx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyeaqxk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eicrdscv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbooiepk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqspix.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjozeony.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yuujllpp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsrioge.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kerjmydo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2admfivit.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhxqxin.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2msqdyfxk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdtznvp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfgvydr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hujdwfbj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaiqhae.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvknjly.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejnhlta.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gffmygev.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuvaaqp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unznjeek.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2esmadoew.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puhewfsd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrypvwha.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2biggjulo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqzabts.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhylqxt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frgmhueh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iaykxgxk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rexdwegf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsdsotw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pctvrlrw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cghaqbgy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2djbnlfxp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcrqxf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsacxeo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjvzrs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stzwbogx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgalsd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ngydfwnp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqititct.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2edbbxiws.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhnfkum.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpskwft.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pemftlpd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2irnhfist.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uahgdtts.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eryqtqnx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcemyvj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bdexctjn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2agawpftf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nfytdptb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwpotll.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fenbapjk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxunwss.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaidolc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vypsavvq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zanfhury.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acortwbx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcjpkkd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbrtfen.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjalrbr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzroxhrs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2igofyuzn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uenwlyhu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bepxlqlr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiathxcj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfovqnz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjtkjbg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2umgqmofi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzyewct.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xopwwzzp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jembqybk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpzchdp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2odmccvnq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeoaepo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsyacec.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaazaux.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ikitoest.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2smugvmdv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cawfmqsl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvovdvq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erswrxvd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfluqnac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjqzeum.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtmmirk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqwlwhi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsudgqh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtnrkkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrugvvqh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oacqskub.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aziyhghh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdhmwqn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzokohg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xemeyhzq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqgncoc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbwjalu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncslywhv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyxgudj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hkafymdb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kzttivyp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdfvjxa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wwifwzzx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqizdlct.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldragz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rubmntla.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxofjc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ogewuwlj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaazggq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfglfgkn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2innujkxx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mncjwuem.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnirxgk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2axaswvfh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2viyqewob.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kixuzzua.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chwgdjnp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2anqqincr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iujodcci.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqojvut.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdnarty.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2gekqebpm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpbnccc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgqttkn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xprozlmj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovbitcz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcoppfq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmshcxzt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpifmzf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqjfdko.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uulbjdbk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2clhkeyez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkptkeb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eeogbcft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtayzyd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2digwtpvm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhtsemn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sluuxpan.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2horndcys.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izcosydr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpidfja.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtcdccq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyanzqvs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fknzicek.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2viccmhrs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2imoftgpn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czobergp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcxutmj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yahfrxsw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjklrdm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmvvwpt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mowhcktg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmsthcx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqnudow.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2utaywves.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lielrpgy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvqjpdb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnowxeht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdnpfbs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnonighq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdypgwsa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlkdwat.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwpwpg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lqncxsmu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwrwtmr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xinfqdhs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjotdvo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uorzjnpa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qquxtepd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxvzjap.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecssxfkc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avrplhvb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfcggbw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xombrsqh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neflujel.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxnqjec.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdoajew.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzlakxw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtgtodk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgcvwaw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2idtqezcf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkfdfxm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvafquu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mksjiubq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zztismxr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2naabkine.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyyxjgs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2udirvtwp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xgciqvqc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nnykkaxu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2plvpovdg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dphffztf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2heilbffe.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oagqfnfz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kifiaunl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqigamg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2njsachlg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwoskcl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sugnxnvk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzvidsp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmjpzsa.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwtqqcm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlvmehn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdknbzi.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuftqrhx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfkmucn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeushbq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cthmzsfm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvdsdge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2avelnrbj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2spmowpaw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bemgnqfm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpgdwuc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hrspaxha.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyezalsb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mpklehsy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfjqyvv.html


<!-- 参考信息 -->