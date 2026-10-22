代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2udfcpniu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qlohmehq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kojczych.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkroogn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhslrkwe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgzupnx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgttkmzk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjbzjsn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpihfuho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnqzfcp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqswhstw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxkelhz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgnxguw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgjewnd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrorifgi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xefcsagf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcsaiqu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urxdbgfm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyynoeg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jejpkygx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgczuaa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrytnzro.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2suyjmnsj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcibygcv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2psllksyi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxmlgld.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woqwcjlu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tolnbpiq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqptgef.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaotitjz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2awrlvfix.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oevrbdic.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmomchie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zijvkihe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rurnypsh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzhqikp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxwonaw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bctmwdlt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssibfqeg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sysfowtc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2gozyrdni.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jseqkmrc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2acrwkrrq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvobqho.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2feugfygw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpsdhdm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgefgsv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbofono.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2knybdefh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tppbmnkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzculpcs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ysprxahj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftccoggp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxafayr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bieqbdmg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdefvhc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsrynqo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmswunyp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpigdbeb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qntdczvi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwykmif.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyvszda.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yiljckxz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vikmqmys.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vupdoclr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcjubzl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfvjdps.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbndaynb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2facmozyc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyiaxih.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2owgtvsia.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfqdyfj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqhqrtc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtfzodz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fabrbffj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmrnbnr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdqweos.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqxmsv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncczsuzw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2afqcfsxh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrowdwe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aakhlztk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2svgkgtfr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjochbh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zepkgtst.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaxjohi.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lukijanb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zumojfuz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaimpdyl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhmfxfo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wofcmzdh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtwehqf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmdjigo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxcypde.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atffsirj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njdphzxh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrghtisn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbcqlbe.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycstykpu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcxcfeo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wshibfnl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcesmsb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlntdze.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryczugat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akqqfaeo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgepruwk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jkifvqbt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqonwya.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwlhkfx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoverfn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fatfukdu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tludhkbj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cimgjjbh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrchtemq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrvgcco.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tchrplzb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfzhytu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aupdvrgf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxjgupg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhjpmzm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwktlw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuvmnyw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rexxlsyf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnuidro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2heaholwn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eghikooo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfruuqe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nuecvkqu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpgmsy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfowqaw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpfkbgi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azgoeysb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmixqomy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubovpdxi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwzafkr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmwphwi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2upkbwewf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrifakr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjuubyl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zuamuyhw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmutbyb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hmctmwio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxpvodx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lttusyim.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaphjxz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmvmpyl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxrshly.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwxfyxr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyesebwd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qasjdlvn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qavbhruf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yilcryde.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2scgyfzgo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fthintjo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmltbut.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfeikjx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2risccpfz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbrnjtv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaidtbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsausbv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwwmtgo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uazoeqey.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjrgcxz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeupdan.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqhywfb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcdebig.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcocneh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oztcqlqi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2skunslab.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeudfzo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvqoyyv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnjwjan.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2eebghsyb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wgklnvlg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jqihmkdo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgxakoa.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpjluyu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xraxtdjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvcxytr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dguegtln.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmzgcjt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exidhxce.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2usrfcltj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chlmpisg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yorddleg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujjnyzf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaylxwd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgryoks.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyjpcvc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoabcol.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zefxnogf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ikweutnu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqimrhzk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbwtxew.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmuxvuy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggryftlc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvpjalg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwriikn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qtudtbrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cayupuvb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dinuysxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyezdlw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjuwdxq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2poyajflk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcimiwx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phjpamwr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwvqeig.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmluplki.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvyfahp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwuppwv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcespcz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqatdpk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2urgydlfj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbwvxps.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gioviujb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaorljop.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atwakrmt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2rirrlfth.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buifdvce.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nagvigeb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmnqelh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wytdijbh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmbyemj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2enzjotwg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxnuhne.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqzoxxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2krizrdcc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbblegr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbhmcql.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2debkxcwm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2anzqyztq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gngfpxmf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suxltmww.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeigqbi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auavkkdm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxyvufh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2roeoegty.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waapvxzm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfjlydw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2amkpiiyk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txikmjkw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmsjtiw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aidlssvy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvumebmf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rknlgzud.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dswqypjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yizmwevg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2phtfwtvp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuotyjj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnjnftx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xglgdsur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2stnmcjig.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldgiyzu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhyogdr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnhpcz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaruqpy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bkngjnay.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqkbqvc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmacnsph.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2arfxdsga.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2glagdrul.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjfygoy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqqeoxp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aswcuosx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2swejmznn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfnlrum.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnkosdc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpheintt.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uywdwuit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbforzkk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwamgtr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jovvteyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcrmrdb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wywbjjlf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hqusfxtn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xodhqkau.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcjscbb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmofruf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhnhlin.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzyflxd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xxejrkwx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnvlnut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfkwpge.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zkniggfa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzadblwr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2plruncxw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpwwfjh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnyuqpe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2gahrkfov.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlafesvx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbufprat.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwqwrgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnchpvq.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aempeuzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyeszkx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cirfdsxp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuemhhrq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bikvbkkz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvbjpts.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrzuhhh.html


<!-- 参考信息 -->