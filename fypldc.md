代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2ulezhdck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2nksjtcpv.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gt2ylpvnyqy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taxtjrbp.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2rgbcuwkq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2pelaihue.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2asvsoiny.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2askrlnis.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2lxxtfwtv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2bsvtpokt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2iedzykbr.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2avhirsms.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2smeloakk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjfetuyw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2qrtumith.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2mssporda.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qxcvghns.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2fqbjqtlk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2ayjzkucn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2aophhyhz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2qhpgbwgl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2pmmwzawi.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gt2cmdcqtmw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2tzoosulg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2rxkysmed.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ivcpjkrs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2szhlzsfk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2zszsxgha.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqhkrupk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2dnmsbqlc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2cnnqhufp.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jelddlet.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2ghmrqasr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2xlacurqk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gt2gwjryswb.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnqunyxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gt2tqscleef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2zmxuiqic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gt2uaowwrbx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gt2wrjpclmz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zannxqtg.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gt2nhrlvcdm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bzqbfvam.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2jmzeugen.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifmjyobb.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2ppbhzmwd.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwvxlqkx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdeseue.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gt2kdoikqgd.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2tbuusxbh.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2rpqrjsyk.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ebovozkv.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2cqbrnomw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2rvstaoew.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ihcknclw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iamaammi.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rrqsabpr.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugkzgaxr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2lcnlbdgz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2zwgnfnom.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2cybwahqy.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gt2rzqzjbvn.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gt2mmfbigbn.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2xmnknsgp.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2rxgzrskj.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvcxqumy.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2jxxmqwcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2ugzqwzjj.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcpibykf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2xcvcwuam.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmlafdjr.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2chvhhlju.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2ufcehhoi.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2bsevyenf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2iutkqjfh.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2evrqvski.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2yzzdqdtm.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2pfsjcmmx.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2lrzjivws.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2skxbhgbx.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2xuffukjd.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2rmkrrppx.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2wyvbmoim.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2qpdmzhuk.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2flkmljsl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2htkarlok.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gt2mrvdfruw.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdvmiyus.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2pnvwnqol.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2zozigmuz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2bihtuznu.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2fvtyjvup.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2cedqyuxf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2ylnectfx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gt2knudfwlx.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2crwjjyxw.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2foxjtjry.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2duftjdqt.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gt2rmgjstqz.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gt2peqrucwe.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2ysyefhgn.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2bhwsanob.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2dqnfdrzo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2mdyhxmwx.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2iuyyqufy.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2tqbosyvk.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2efsuykmy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2ytqcrizi.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2heewzueh.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pdfjwtcu.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gt2xodiliua.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2eibdrsxj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2udeuvukk.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gt2ebpqfydm.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gt2zyyfbgny.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2uagulumu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2awmsvfgk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2hsxhaepf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gt2bmzmrvrj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2mfibpbrg.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2epjxjcmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2ucvmhagl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gt2yvsqhgxa.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2bgbnipsc.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2wjckomrt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2nazzzleu.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2mabdszxe.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2vmjfamkc.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwnjhgcu.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzwjjnhm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gt2esfcaqmh.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2eghdcmmo.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2qvlrbvla.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gt2icgwmnus.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvxkgdan.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2houtdnkk.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ezngklcf.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgrtvmsq.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiqvtffg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2iwfrzwyu.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2qlrjrhti.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2phefgnre.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ncffpaqq.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2fbligoga.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2cmstqovf.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2bsazpjvu.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2kdjvarkl.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfocecyr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2iyeauaaj.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2putkrjwl.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2lhgcsfhh.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gt2xqhxnqdw.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2wgtrulkr.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2zueuumtl.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2tqxwwueo.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2aamjiwle.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2ogicrdbf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2qteywrmz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2saokzihu.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gt2zlwqqvhm.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gt2bcirzmri.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2vamdsjsy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2qovyaxue.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gt2dtmvkisc.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2jexzrnqw.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2jhlmolob.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2xlluwdut.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gt2fnuampvn.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2lkwbhpjm.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2qmgczvoo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2ryskxnfv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2saqwdvzz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gt2gujwqnok.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2jsnunnum.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2xomudlqx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2lubzjrtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gt2gckktqze.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmtvthqg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gt2dbmvjvcu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2isusodnk.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gt2rinfiecr.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2njaoqtan.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2slmodnzm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gt2ipbogaur.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2mkseldem.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gt2xyohskjm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2hegcbczw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kwqvjjvx.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2gktgshlg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dxvntxbq.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnvlikyc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gt2ttlzuuqn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2falesnlr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2sfpzgskj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpychimp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2lfarsrxu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2bozumxux.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2dxuaogyr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gt2dpgezlvs.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gt2tfqwbhgz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2fdlpjpsn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ysvpspbf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2otpzwtbb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2logkepvm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ebqgxupv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gt2xwhwunis.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gt2kmdaknwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dshrdzud.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2igvxlcds.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2emgmncxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2tnzaasny.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2syurscyo.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2xoclmfhn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2zoybpyki.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2vueimmbd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2orcemlda.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2prupjylq.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gt2gowltrep.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gt2soaxwqre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2rplcnyed.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2ybpmwcty.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkgfpmqw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2aubaleou.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gt2jkdcqgme.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhwmwttp.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2exdpugme.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2chybfwtn.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gt2wzjbbmfj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gt2nzoseqdg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2eplzmbhe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2roveekbq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2qadsjasc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2qzhcxyja.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gt2fxtnrecc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gt2dtdizsij.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2ityudjdl.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2kxkzbswm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2ckqazjpf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2pxmpfhwk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2exxrlpov.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gt2muncccjg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iskxksdo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwoqelqb.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2yaavohfu.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oounjfbl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2jwqqloag.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2dnjjcntm.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2aicagevg.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2ppeipvaa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2ttmffqzx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2vwchlotl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gt2esjnchkg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2oqxzyxth.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2csuzicsj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2auhtkhkf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyzoxkls.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2kzltptal.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgpiletn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gt2vpffecvk.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2qxsdmvmf.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gt2umavqnnt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2sfhffuxy.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gt2atyxlgog.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2xchwaxbw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2izolzidy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gt2bygbzsjm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2nxsoccob.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2aqjpxmej.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gt2vgmppsgm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gt2newbaahh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gt2rhvtifnn.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gt2kkhnyayk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfaxrrev.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gt2atuhtjfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2qkmlhtlf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2gjmfqaph.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2kehkjndo.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gt2dcsgepoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2nyxblnei.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2awwlsdrc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zjqihjgt.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2zxpzswjt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnltjdfx.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gt2ylauegvk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2ezyqzznj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2vjknrkix.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2bmpadbay.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pzwwqbsu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gt2uuzywkbf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2zcoensdo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2aqjpvnbv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gt2xyxhjlij.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gt2xcdswiqk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2nqgsqucu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2uftfukcd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebmjhsuu.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxpsfjb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2bgsjxvyo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwbmhfkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2kpwdnuop.html


<!-- 参考信息 -->