代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtrkrizevw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtlxsoficj.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtikwgiero.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtjbvfrcvj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtfzixwyff.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gthxhparap.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldnypzgx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gthplqhipb.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gtbrhomnkm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtplckvshn.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtpttlqdtz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gterusvcgm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipluicpe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthzisnvxh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtfhilydsq.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtdaossrex.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtvwynimtj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtjppnopwj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtasqogguu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqhvofsgn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbolqdygh.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtsjxhayva.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtcmzzkbmm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpzhalzov.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzkisdmxs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtoynodpds.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtiawyqqhg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfeaccxgc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtxchzosss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtttvscfqb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtobxnugip.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtbqolnotc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtpllmgmdb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkusyggpd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtibrxiguy.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtpxbhwlfl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtjwhfrora.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtgisvpvfr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtpupmwhtr.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrczjimj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gtxotuqrmj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gteaghhfao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtajocfvlo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtytysssea.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpvfaaxnk.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gthyfhcbki.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gticuyvuzg.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtdfqrfaxi.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvzhplgb.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtyurveixo.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtiwjcwrsr.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtzgfzahvk.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtszolxxav.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gthhgygxtb.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtspsvsbpr.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlosqmsl.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtpsfhjwye.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtrwwuaazs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gttpmeseuc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzfncbdq.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtqnyrfqot.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtghzkeufo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gttvvfybvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtffwvpodm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtadwprafz.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtgwqcjkoz.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtodvnviab.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtaptwofly.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtchgxilly.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtvqnywxzc.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtyjazpwhe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtcyvoojua.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtbvnfhgie.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtrudeaoqv.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gttfwjhxnh.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaxfjaxd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtojicsmts.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaytjzytz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtrjcraokl.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtpjdhqyjh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtbfjrhiqb.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtdrarsxbw.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtecqysfgy.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtohkhfljh.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtwbskkcef.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtasfzfthp.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtkjvqgxqu.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtevimotce.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtvdtuovwe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtjzqonnfe.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtygyqcsrr.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gteubifafn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtewtqmpoa.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtxktseyco.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtdqipkozf.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtxmexwdju.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gthutayiqq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtfatblepw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtffpzwchf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtcwwxnnxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtzfscvdlr.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtogrzwcyx.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtsausyhow.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqvternb.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtgocdpumq.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtkdvgrjfv.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtdyqgcoqb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtxkkwxviv.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtqzhacctn.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtjvyyfuxc.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtxhvvylln.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtbgdcqvvw.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtqzijbtur.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtsqxyxmkb.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtxxnpwwit.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtldmcaygs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtldlzvvgd.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbpslrnp.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwngemkdi.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gttdamlosv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtynuzeana.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtrkdunimv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtkzjsrszo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtwilvwhol.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtnjfpwvnt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtxvtqgbjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtwybwdftz.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbblsqirq.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtfphvbgws.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtrkgdngar.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtcebqxktu.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gthuspjfvy.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtjpbiwejs.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtecuepydt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtpvqiptfp.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtyrweabld.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtlgopggtf.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtbenwccrl.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgczlealr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtozpdpjms.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtggxsvhsm.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtdvjlkmjn.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtwpjkkvfr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtxtwgjcnz.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtguxchkfy.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtjaegareg.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtjgdsmwpp.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtngakzncm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtwrbdsbek.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtiliufsjn.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtntmzbmri.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtnxbiupfy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtwarmwsyg.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtmajsqwyt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkkmelgr.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtgjqytgwa.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtgrzefpxy.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtqbtketxv.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzfccidik.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtemxkzhus.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkriqnpto.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtkdgrivbv.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtqmqucreu.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtpgmcdmdd.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtuatdmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtqymnlrca.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gthxoznlyv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gtdrhdxlzp.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtskhetamg.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtofjvlfuc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtlbbrhnil.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtxvezrziq.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtfmavvhkb.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtugzbqlbj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtmttkllfc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtduxxsawg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtsoqfcuwd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtoyncrswi.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gttqohwvgb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecgijaid.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtngwcgwdc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtxktngttu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtvmuovgbp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtdzonyeze.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtzxxbsucg.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtcatanmsw.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtrmjobemf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgbcgrhq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtethbttev.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtdnvukrdd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtontbotua.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttzihrdcg.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtelexyteu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqhhdelnl.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtbqpeamaz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtglpaonya.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtsmllyphm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtiepdtxtz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtaoclbphh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtpwftfclg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtsjengfxl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtkwaweeur.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtpmadgult.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtcjuyqady.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtckqwcxxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtejnmwslf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxpeetox.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtxzixhktu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtsdfmupfk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtrzptgrkf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnsgplrc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtchjlwbka.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtmofyerlr.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtwuoczhok.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtfgcehzni.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtegmkhgbr.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtxrsqlypf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyvaifpk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtgfznawqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtvrnpgsnr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtjuytlblp.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtpvgncizv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtwvawastp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtozfvbchn.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtfpdohiua.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gthqbvaamn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtnhtijpgh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtuwtwksuz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafwiujot.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtvzqxowfw.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtnrckygjb.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtnweclqem.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtcrqqddpf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gttocvfnrk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtdnbjjepe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gtnoidyblh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtakflanrn.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtmuaifjsh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtybkycfgo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtvnjezurw.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtqagzrhuv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtuqjaqxuy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtbokybwtm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtvghizjwc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gttezijeck.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtgtydjaug.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtzguucivs.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtodtxcqfi.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtptvhcmoo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtycjkscqz.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqbyykvn.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtyyofcerc.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtietijhqy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtvchzkhgv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gtczsbqbap.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtmukszweb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtmouszacq.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtsvxuztve.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtfpurwhev.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtyhoybole.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtjfwgcrsn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtgqnaczkh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtqtmxdpap.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtdhigjldh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtduhvpzdg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gtevxmlimn.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtyvcqgwcp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtfnytzgjh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtdalobkba.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtqppdetyp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtzatxvren.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnlvrfvil.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkrtbxft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtytplksmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyllumej.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtpkfmlqwn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtvkprswtg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtrymfifkx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtfrxedmqr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtjvnagiyz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtxlkdnhqj.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtwxqkiuqw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtpnnhnlha.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtiybvhphz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyyzqjpom.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtrltqdskk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsgypcdoi.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtixnuzmxg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtspartuyz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtmzbxveqp.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gthsojrmnk.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtgdwsecpf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtwtfuowkp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gticldilzh.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtzzevptbj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtesdxbldm.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkntdldn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtclbsinvd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtjsgyuxta.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtlefdqtfg.html


<!-- 参考信息 -->