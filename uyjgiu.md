代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtphgtqilk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtxtspktgn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtsoxbmiop.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtgcwxgszl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtorncyqfb.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtizeczemr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkulybpxb.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtfvgmczpz.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gttictzeyn.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtykwichoa.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgtpmhvzg.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgvyimic.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtprivyirr.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtbueisooo.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtpcfusrev.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtobfbkxqh.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtdycuxlop.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtkyhpdtec.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtltuvxgef.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtqwtloddo.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtxniqoelk.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtkoockasl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtugabadlh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipslhdgn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gteumnkjrx.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtdmogovli.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtrdisrkub.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtvgnmhjyg.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtwnpthqql.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqpikgui.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudcprxkh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtzuqkgjad.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtkegpqqmf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtlrpdnkog.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtgmjvdbsm.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtsolagchs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdimzuao.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtmslavcmp.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtljtvartv.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzxvqhcex.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtpviizguz.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtbklniagu.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtgwiqquvu.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtbmqwnzdb.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtqgnwgrec.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtgpcanyox.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtuykdndmk.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtieoyjrpr.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtxevzajpp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwebmfdjt.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtfhrqaueh.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtfwfjbsit.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtzmssuymz.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtsqcebxtp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtjwoifojy.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtqlocpzle.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtrfgboeio.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtkzqmyewo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokfptzml.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtqjbqgdtl.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtrtfchsku.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtstflgrop.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtpsmdjben.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtifeldxbv.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gttzykzpmb.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtymcjwfjg.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtiarnobsa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtfgsuarqg.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtxhhlqeed.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtohlpqfgr.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gtrdyufpov.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtesquazns.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtgjzzglum.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gteoopmrwf.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtuwngisji.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtjrfdqeva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtiwwyeahg.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtryjjuvpl.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtodtrznzi.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtgkkhbyrm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtvheqjtxl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtamjxuwtn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtycumlsnn.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtbghllxtz.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtnfbicqzt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtdtedpioo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtkggxfcpq.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtunvlwisp.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtlqstpwyx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtzuxxvnfu.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gthuhsinsx.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtpgfiirnz.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtlizjnzeu.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpaajyji.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtadfhfwhm.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwieestnt.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtptmighqn.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtskhfwdst.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtzefgykhk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtqdzledrr.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhxgcroz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtfuhecalv.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtutrsvsyv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtyjftfmdj.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrewkcuxk.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtnooqlset.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtxdbqsvqp.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gteoemkpum.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtxyjfiswt.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtqxgmufto.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtwciyzijq.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gtkguahtsy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gttrqndjfa.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtvzmlevbd.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtcpwpbhbk.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtfoqiqbin.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtrnviefib.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtyjmczcct.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtjqxqtsks.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtrckknrdc.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtwuwdvkqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtbhpsqgfy.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gthqwwdcdb.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvffxsqt.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtrprenvgx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtwygltjqj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtuflowvfu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtqaotipbv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtqwjttbfs.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtgihjkfdd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtpvtwkdhu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtrqwmsocd.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gttncmnylb.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtsouqpzer.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtxuhlmlgi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtovtetfah.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtddzwuijf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gttrzykyji.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtcvouejnx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gtcfpaqahd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmuvajbp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtqnaytijo.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtvuxozdib.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtpaaipldn.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtzkoeetaw.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdeslvein.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gttardgsys.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtxfufzhuv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtwgncsvpk.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtjytguzzz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtjkulfrlx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtiqoctske.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtcunustnw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtaulkqigx.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtngghttfl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtcgfpwyne.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtjamifmiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtnowqiecu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtinsdlhbi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gthrcrqlqq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtkqugowku.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtulshmfjc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtedwdijya.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtfblnaota.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzteirpq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtcyyivnbm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtbytdlxwy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtjpnxhjpg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtigccahkp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtsqcpukro.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtteaynetk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtzxcldqtm.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtgfaagwbd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtuplutxmx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqkraokpi.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtcsxpzekb.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgehhrcfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gttywnqcjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtcyehghfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbhknmdv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtjtdvljwp.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtxfjonquv.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtqomazvtc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtygftpenh.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtxagjgrcq.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gttzvhsoya.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtmqnkmrhu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtrkddzckm.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtwpsdnnlw.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtfnlkytbh.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gtkeiqwbyf.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtunqsmalz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtvyzqnzqz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmwyorvio.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtpsqjynjp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoldprroi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtnflqqisc.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtisxunyfb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrcpiykoi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtfostpcnd.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtmobivhui.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gthwpkymis.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtclonctea.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtrxqkcsul.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtpuczhulr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtdnmturfp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtbieshxgi.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtlfhmlnkr.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtypmgsira.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnfdrori.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtikzwsyqm.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtbiozqlpn.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gthxxcyeii.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnzsoklt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndtyhmqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtkfzjoqdh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtatjejguf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtqtnqmbgt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtmgkeyipc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gttbbrpcmu.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtrsruxjrb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtwleqwbqr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtstuqrwup.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gtlcpiyjdx.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtmxqxfntq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtbfnlamyq.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gthctgvqju.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtldfsrdfg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtjvxkmdxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtcemeqxqj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtlsuptluv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtwblopbvl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtusqdzqxd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtkbizpzsd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gttchbdusb.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplxltttj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtenkqjdge.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtpzjmdkbb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtywodfync.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtksoysfnb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiuazsdk.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gthniogplq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtjhvzsbep.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtlveooccp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtleknamrw.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtdeusaejp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtscriakjy.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtqvmlnwhe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtssnypmby.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtvpwcsygr.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtvhtbwphc.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtblwmbwgj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtdukoopfq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtsjseioli.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtmvotqicf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtsychwobx.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtmajhtgvg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthktmyofo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtxlgyftvr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtzvhtuhkh.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gthtexsfim.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gttibipguv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyoqjvkd.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtgtudauzl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtpcibeprv.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtdyodpvsr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtscuiejvn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpknqmwck.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtanheafsw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtcklojjbf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtlgbristb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtpvrirofg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtbpovudoc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtgzbuofcu.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtnogetulm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtcienzulx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtsnwnsddt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gttuayubkt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtiumnrpwg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtsiupthta.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtcbbflyst.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtopwmgmrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtkkesmanm.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtnbycgras.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtqnwhmxkz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtuhbpchqs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqttbcid.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtzkyobzjr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gttpxptiuw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtguymkxlo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtuyaoayok.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtjzivcqdt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtxkqtfzvm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtbdfuvqug.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtngdbwgyt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtgscdtdbh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaatizkcj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtrolqcbtt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtkkkacymh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmajnxwe.html


<!-- 参考信息 -->