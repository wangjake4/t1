代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2ewcilgqa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gt2wcwhnhdn.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krpsznzd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gt2vgtzqegs.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2jwureviq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2dwgbctiz.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2kwuigcbb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2xmbfjyov.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2uvievzty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2lqmlztja.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2ombkfmwl.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2hxvjrvfq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gt2xhhyywji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2enzndrcr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2xjpanllb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uehskfwe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2astjhexk.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2xcsvpcri.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2ogoemder.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lcmaxafc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2dfoofkhz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2mbmxgopg.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gt2vencorjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2mjewzuiz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2bleykxvg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2vkrpieov.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2wbslwwjc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2dtuzqutl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gt2tnbcnbbr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2mthpjafe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqwkauug.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2zpjitles.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gt2ziaylrli.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmpuswuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwserzkn.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2qfkomzkq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2ggkzwbia.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrkxhdhw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmjrwhnm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2fuvjaxny.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hxnsfdsg.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2sonrpneu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2faimdvrp.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyrljoay.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2wpubujab.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2swbvtlvv.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2pcxvggws.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2xhzlghpv.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lyyryqne.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2mzxttctw.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2wuvvbdox.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2zeqvvpch.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2gbrgqpoe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gt2gdvqrgwg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2ixfrcuyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2hltmxihj.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vbyuabqb.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2pmugtsil.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2ejtyhpwk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2jrflqxyi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2zeejlrmm.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gt2aouzxjip.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltawruvr.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gt2pkgznjgy.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2vssvtxby.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gt2guhwwvix.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjprnkca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2azwquiwg.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2kuebwapi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gt2pwsjtmfy.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2zygvfrol.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyricsdm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2kwfqnkjj.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2qdlsnyxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2dfgmvwjb.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2vflbxxzs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2octnoovd.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2aubvbdze.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2wpcygdfc.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2pghdxcsn.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gt2zhsiwwkb.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2yqqkmjmg.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kswxsthh.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2kjkfopyz.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2dtrwjivk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gt2btqpinmm.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gt2ksygkpgt.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gt2sdzdqmlh.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcevesyz.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gt2ixozbokt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2zxigbnrf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmatlyga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2xbswzccd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2eeihrorj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gt2nnuamqrq.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2sgbcpojk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2ybvsocsx.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2lqbspdwo.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2noikrmbx.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2tdnjibjv.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2xtymtrgw.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2cqbiaadz.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2jnxzibcf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2yspxxrev.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2cqibypil.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2myxttrql.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gt2tquhuunf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2nznkrjje.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2imrxjhbg.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gt2bnhzuvow.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gt2txrrypyo.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fbdotbas.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gt2bvadjbqb.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2lefzmmxm.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2hyfltohu.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qldoriev.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gt2zjailkrs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2eehwvpkv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gt2akkehtnk.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2qfmuganz.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbdwjjct.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gt2hosemdxw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2bnqqohlz.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2nmhqokde.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2expallzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2imfcytgj.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2uphatftw.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2rhrfkkhv.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2oeripbsj.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2slcixpgd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2luuwntev.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2wpfyzzzm.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2docmfqxb.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epwyjbno.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2athyzydq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2bkixbwwm.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2amobbtyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nresiutx.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2bpiyubak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2yuuuqpeq.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gt2ghvzhogg.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2msajvsoo.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2fsdetqqv.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2vqxjacdy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bxpxhcxw.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2zqhslxlf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ifempaxc.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2ykjijmmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2ryxavauv.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2hbjfqcvv.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2jiqcaeuj.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2xnnindhd.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2mrnuhtxi.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2gsqlpcjk.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2tkofubsi.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2gngsmrvs.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2riaxzrgj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gt2iukltpmm.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2igbgvtng.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2agcfqicn.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2buqinlxz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gt2muqhnvxy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gt2ltdtcbrk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gt2woyefosz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2hutklblj.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2qnxekdcu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gt2tywypduu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2rvylohmi.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2aldtqkvh.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2ggjqgltu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2pixdlmvi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2nbgalkiv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2oswcgojf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2qluoshbz.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2qoqtmopy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gt2msnxlzjy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2yujgxhuj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2qhgplykw.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2uopswjjw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctnkbcaz.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gt2blhjclot.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbfxfppx.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2npjfpnhy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2gnlfeheh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gt2ibdpyaot.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2ctgmsvoy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2fwxavryo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wovbzjqi.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2pnjakbph.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hhxyvwll.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2wiayjpxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2dnhadzfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2vssgwvce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2qujeeuua.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2dtykffab.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gt2czhvjcro.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhujinty.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftdpvdbh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2nhqanhfh.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gt2soucrshg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2tgwmqypx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2afvjxdqn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sssvpdxv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2eaagrcds.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2abffrjow.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2gvhtwevq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gt2rfnnjpzv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2enqadvlz.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gt2sfebwsuo.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2cksylrkl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2szlgtakv.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2dfkmihav.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2cxagzsfi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ibtrmxxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eimmikaw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gt2pykvdluk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2ualdxehi.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gt2hnzosyaz.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gt2ckrlzfkl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2wvcimgwb.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2odxfskht.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zemwlvlx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2czwyfiwt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2eteihkpk.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2gyjbmyby.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gt2wthwtwzo.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2jjarshpk.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2kckvchpo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2oudgpzet.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qngyaimk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymnycusw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xsrdpjzy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gt2oxawnkaz.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gt2pipwnbjm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gt2vmdkmwrp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2prfkiysp.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2eskqftoj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2imbeuwft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2qqjfpbla.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2aavdgnnf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2vtjntdvb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2btsjbrgy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gt2qwrycacz.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2izaxixro.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2gzlknbwb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2wrokuynk.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2kndsodfm.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2dvigjzyq.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2hfqppvlw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2smhxphnr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwyyjqdg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2oybocrpo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2lygyjkbi.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2yhsktbow.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2idvrrlyw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gt2rtoqdhat.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gt2fwbloosk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2pxjrlcei.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2ioscywgn.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2gcyvnwlj.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2ssecebts.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gt2wjeckhem.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gt2cnpdlcsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gt2moiljjpm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2ntfsctny.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gt2vyenpwql.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2jgoocppf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fhqrxacc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gt2fxyacmfh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2oqlsyrij.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2zvnbtpta.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2pnbmfdgb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2bwghalfe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2yfwobmjh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2kjncvblw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2pieoiypg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gt2yoiltazr.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gt2vrpeijpd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2xvedjhsb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2kublxbmo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2sofwoaqg.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2ahiqhksy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaeblubh.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gt2nowllbpp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2tarzmvob.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzystobn.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpbsvsvz.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2rifbjfch.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywcxnzew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2fgsmlvkq.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2ixmftgbz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qklbycgf.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2vzetebkr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2declqwvo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2rdzmtovm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2rfypnzqd.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gt2psglhcxx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ctczdxem.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2brghlroz.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2ecvozqfa.html


<!-- 参考信息 -->