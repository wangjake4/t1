代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtodsvyhem.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtzzmclyrm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtlvgtsnpf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtikwudjsl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtkseqmifp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtbkqkftaz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtcbaapngh.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtxwrrwovm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtijxggree.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtxwdkihuw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtauflovbt.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtvnfvpfxg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtcsruumif.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtgajqnatm.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtrnsolajj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtibxfufnn.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtzymgyljq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkkgxvolj.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtmkmpwmyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gttopmczjj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtfudxyfmc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtiqwrojke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtooibjhaf.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gteggpcttt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtypvncusz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtkuhfnmmu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbjzxvsco.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtnqqrkzfq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtrixsxiev.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtndjwuyzg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtxmjubdty.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwdpuixnk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtakruyhag.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttktgcrwf.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtgpztqfkh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtibepfjyr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtsxzkabjl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtikdozryt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtcppydfit.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtsezzxpie.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtiejgaqfm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtncwtaino.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtvcxgfcfq.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvjrwzxl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gttsexiiem.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtpblwmhiu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtwdpafiuz.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtzzuqjxfv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gttsbxmhyq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtmyxvcqkv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtauxrqvfu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gttvoxrrct.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrsnbkkxc.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtdhwlzhka.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmvusdbxs.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswdortmt.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtyxwdefgi.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtzcdtxcbw.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtfdulnasl.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtjjudbhnj.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtitedkptz.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtykiagles.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrtynynrq.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtpxmhdgai.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtxupocrht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtdorntndn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtpypdlynl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtfvpwbjra.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtntannrpn.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gthlrxojhb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtwjbljjbm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtfyteswck.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtccfotwjm.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtjccujtbw.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtllbjsbke.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtfbwzpzds.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtoetjfqwb.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtphpospte.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtigwvrbvv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtyoervcyw.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtefayxolu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtyxqicdvn.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtttpirmle.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtskddhzpc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtenwoesqf.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtxrlvxixl.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gthlksrajt.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtnauyapyy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtakxivpnl.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtfouuanuf.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtgxnmonvu.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtvtmeghwd.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtmfusixpu.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxnlqbfk.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtbksmqyar.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtksqwdecr.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtvpjkjscz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtxtcojjpv.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtgmzpjhqp.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtrvmfokwy.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtftgdqhck.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtkjzwwnzw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtnoydibqv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtajkazh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmructkbc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmrlcxptm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtzfrbtjlb.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtwycszyae.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtgxfdegwp.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtsjqgtomq.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtqxbkivva.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtfppmlqqd.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtbraokscw.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtpoqwukjl.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtkiqysota.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtvruqdzdo.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtfphignik.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtevfyqwls.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtfpzcezec.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtenhszcdi.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtmfjnwvpe.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtqqgilvyd.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtcprakgfq.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtmfbfuilj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtncevfwlt.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtrlvpmcyr.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gttthlctzm.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtwyeqxcrk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtoibhjhqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtkffhrskn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtdtqkrbju.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtayncbqyi.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtgpnabpbp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtmtcbyhpx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtdkzxahcm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtqythnhow.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtzppyzqau.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtgjcwhfui.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtnuajscbl.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtscvlbmnj.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtmtliszsa.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtofuyzqpx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtkvkcfmmq.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtlbbvovjz.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtazkrcncx.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtrsiwxlns.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtnjyxtnqa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtldnyzjwy.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gttlecqpfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvhutbxoe.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtdzafbasy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gthcsbtjst.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtcbjyvuky.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtnvpqzyvv.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtgpdyolsa.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtppqarvye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gthvemjjpu.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtevavmfdy.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtgsuevilr.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtevsfsgjw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtlvqgctax.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtwfrkpevz.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtbaogimvh.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtodkgwdig.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtzdzapthu.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnigwrcqd.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtyzrpmdgy.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtkrkbbwbi.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtydwpxwqm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gteejnmoqe.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtqtvafvaz.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtazqmmmjc.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtbhotnkpz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtqiwllbge.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtfqtjstqy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtfxtnqham.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtbqqgutmi.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtreqpueny.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtukngxhur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtfstdlznn.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtnimwwgwp.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtxtpompaq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtsyjqtclt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtwmksyuvm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtukwxsvrg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtyuzimagc.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtckmddjff.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtwpiswlek.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtfyovddsc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtjxjehada.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtljjviqnn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtlskcorxr.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtbmuemfmm.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtsdvfieas.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtuyhjiilq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtepepulub.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtyalwjfcv.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtayidvpsp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtqthbbnuq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvdxlfhdm.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtebpfvsxw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtokmtzmlb.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtiknkkqgh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtcwmujesm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtxqhcxyuh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtvfwuvmra.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtjoqvthoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gttdahcnbq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtprydovhn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjusgwpc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtwszviulf.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtlldogucr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtosqltyqy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtxhjglacf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtvyquybvt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtwpgdyrjd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgimarnek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtshaovueu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhybjffy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gteqzizqqb.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtppmmopmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtbonvoeln.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtcrgzxlyp.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtyqcovohc.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtrtrpgeek.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtnwqsmpon.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtdjecqmct.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtmcidviar.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtiomwhkwq.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gthuzppcfz.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gttktxruag.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtbyzihfgy.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtllgjvuce.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtnlbxpgwp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtzbxfdktj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtpblknwfx.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtadfultqi.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtdshilxoa.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtivnnlapo.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtlibhjupx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtltqdzllr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtrqxkjkqf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavrriqgj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkmnfljby.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtbawymlfv.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtxxxgkekx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtqbihqkyo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtbkiupruw.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtxwrgqqax.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtvbzcxqvf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtdtbjwzsb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtfupuguvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtwxwfrpqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtivqmonko.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtscatwmpm.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtwoxtwojh.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gteqfdfpxi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtudqmnwik.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtfhypwdsm.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtsaizhyfo.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtlurjfwju.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gtphjdbrud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtvzoqiroh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtyqqzvrfq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkefojgqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gthkqbjgvo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtwcmgommx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtykqmpbnq.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtpmfdkgwq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtsdfcddqr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtpefcsltm.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtmtredjjp.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtirjhsqvc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtcopxpjxz.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gteqtndpth.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtuhkawurz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtqdewngfw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtrlmqxdsy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtjtjjsazv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtvqcktdwi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtvdhojkom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtriiwruhg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtcsfvlfah.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtrfknnczz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyytxamx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtwujietes.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtheajcphf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtbdjjevkh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaeausdd.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyzivret.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrtovodg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtwmpalmun.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnhrvetcz.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtlxegpxcz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuruzpty.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtzhcytpyo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtojmlkoby.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtplcfclrj.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtatqkhiho.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtzegphdos.html


<!-- 参考信息 -->