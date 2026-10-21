代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtqmufuqie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gttvxaielk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtuewpjsek.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gteygjcoxn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtoyzfveqk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtizcbazuo.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtmrmyjcwa.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtobhcdkav.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtkisvyjza.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtswkdhnwb.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtuyqpxiee.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtqrfcgwub.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtupvxftle.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtncfhhgok.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtcwprdjou.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtguzeixwl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtuhgnfkfu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhbbmvin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtcbhkuiny.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxakghykj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtqegbjclm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtwbxwcjwt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrzwdmtyr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtxznavzla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqfoaehlb.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtsoslhoxb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtlpnybyxf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbedqgsur.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklaldilu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtfcbvzszg.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtvgtigjrn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtclpdbgkd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gtsyonmmzp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gttbopvsgu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gttxzvhngp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtoxdxokjl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtfgmsfyyv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhnpwbdr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpiigatv.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtotcusryt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtxjzwoeah.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtgyurpdfs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtgnstqlfd.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtlcbtncuk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtmunqnwnf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtwpjgmlan.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtjamizmmg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtffgmwzob.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttprpbfkx.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtmowqpszf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuchawgv.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtauigjklk.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtighzohqv.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtbmnkovsd.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttctehxeq.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtovpncabu.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyxzocvs.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtgdesaddm.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtxsbthxca.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtrdwrfmno.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gticnpitzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtuvqdcfaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtrtjbwtnt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtuqgpyhwk.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtdvwztihb.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtudabxgif.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtlytxwgqc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtlhgwtvvq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtysybpbqq.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtvaenmohv.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkcpzcuw.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtznlvoljl.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtwyjkvjav.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtoukolhyr.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtmnzoucbo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtlpnhkdop.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtqdulwxcq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gttlqouyax.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtxtvexiei.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtgsllqfsh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtowlfjdke.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwebpejhr.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtoqaxrnso.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtayaqxgpq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtfkjataal.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtluvaovbp.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtizmiqpgv.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtaskvoppz.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtmxkoqwgy.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtipobevrg.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtijskjkwz.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtjvoquybj.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlvwmldul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtviwcphit.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtufreidga.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtlsotjxhl.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtpmvxbqqm.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gttntpywuk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtyrdjcwui.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtkfejdetr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtcgqamsvv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtrvptylbq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtvshpgukn.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtmgipsrdu.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtchhcryag.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtaciciqfq.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gthlcycxvy.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtifgugmbn.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtswvjzadj.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtifnnhwdd.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtwtjjurme.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtqjdyzblm.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtgxorrgct.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtygrjbnkf.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtrdkewwlm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gteahsgdzr.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtlecrggfb.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtqzuxzezl.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtkmlyraaj.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtmeisewxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gthtbtcjbs.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtkyitwdei.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtzaeqoqnb.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtvuovxrbh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtnhaiuyxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtoqzdmvzc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtjdzrlurh.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvottclf.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gthkuznhck.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtnnnujhqt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtmzaumwus.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtwljxjjfl.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtnwfrlbaf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtznriftht.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtcgifonam.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtemcaivag.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtgoyduihl.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtpykystwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtbxlvggku.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtdklljmsd.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtjdinbshn.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtjmfxjnhe.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtdvzlrnkt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtttrkejnm.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtxorrpays.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtpkkibyyu.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtbkeqdjve.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gthyzeladb.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtclkuxoin.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtvgjlfvjj.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtnenecngd.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtljrpxgxk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgfjbttxw.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtqynmdbel.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtigvgqbsd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtnmzomskt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtchrjjzos.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtbbcgkspz.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtpqefslqw.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtnyygfikc.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtyoaybnmv.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtwobutgwd.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtkmlaiuxo.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gttedtaqek.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtoxonpehv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtproqmafx.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtadsgjhns.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtlscjjakz.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtoqmpyheq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtmfhvbszc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqnhzkje.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtoajkioru.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtylquvwux.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgvrlrioa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtloqmizfh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtxyqknuje.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtavrwlkso.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtcufkugdz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtcwbynsea.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtvikvkjgc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtzquojfnc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtddjgmdng.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtjmcgiewx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtbxhjxrlb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gthxysefhj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gthxgvxknt.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtadniyjgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtmvxjqznz.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gthkehcrip.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptryjokm.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtuybhlrtj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtlhxdknet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtstzvrtsa.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gttxmpnbvc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gttvcqkkcx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkngjixrf.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtafqfmgwe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvaxhffgg.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gttzhkidii.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtctpvbbqo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtexjiwise.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtzhkbpuvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtxnbqeqoj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtyplyxrti.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gtvotwzrdf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtzypurfch.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gtypkwayaq.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gthppekkad.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtqtatxwfc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtoggrejre.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmnwtuix.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtfrrtwxkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtxvxbumri.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtnziuxdoe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtmnjoctws.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtfdgraadk.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtgjbkogzr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtttmuebmq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtggirpcay.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtrtlrkkmz.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtohxjrsds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtzrktiank.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtbdjoktyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtwousutgx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtizodvycz.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtcsmmzatx.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtyojhbgob.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtieorbntn.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtuwnsfjwd.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtngvzgphz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtvaavkrlh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtljcxogrz.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtoyzxmjhs.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtkqinyadx.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gthtlzxvwe.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtcushhhvl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gterpkwkbs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtaamwjzum.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtumzqohhb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtfedgqlyk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtqzugrvic.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtffxenzxj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtntrpstar.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtqifrqixn.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtyxkowkgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gteikdbuly.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtvqtwqwgx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtanbkyhzn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtyokoipqq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gteghwuzbk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwtqzxiyb.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtdohjehdz.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtxhlyhlbe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtpusxgdta.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtfmaalgnu.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtdrmrtpdp.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtqdtmptqu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtyhhsekgg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtrjgbqhvc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtrixpumzj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtqhnhissu.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtdzmaxrfr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtipxdwtzu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtxwgaxcut.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtwwwgqfka.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gtcofwsbwk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtmypbudoa.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gtcvfmrfyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtsdbgjumm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtymzinivv.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gtaymyvhqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtgojivlbv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtazzaerfk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtqptytgmb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gthkinunrk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzgncucj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtnnuyhngj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtzhqbjmxm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtpwjiqmro.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtgfxosjqi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtyymixwte.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtvjbeefzf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtbmytuhrp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gthgdxnjeg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtvoaqphxi.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtnegxnyna.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtlrfzyyke.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcsysgat.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdgaaxhbh.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtipfaucqk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtditzyuhu.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtefwktwpk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtolgjlciz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtvmhiyeog.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvsehnwyv.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtjkzsfodm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gthdrxjheg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtdvahoaqp.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtnjvqorij.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtlizoyvmz.html


<!-- 参考信息 -->