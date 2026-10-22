代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtfqqmbntv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtsnblzmnu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtndfmufsd.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtbsiagdbc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtpkkpjmym.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtoymkolmd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtrnubkklw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtumhfwoch.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkvjwffzx.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtcljsspws.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtftzesasq.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtwkpcxanh.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtenwqvgna.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtflmgywpg.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoupkbzvh.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtuwbpiwzj.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtmgxqhyoc.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtcoppgtqa.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdcgifgn.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtvobsogvv.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gttwfgxgfm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtqbekmfwo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gthttpvrun.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtbpewofcz.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtckbdwnac.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtohwyegxy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtggqmlknz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtuwcjeeoq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtdibfsnzf.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtknufktzj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtmfphszgl.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtnvklgrqi.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtkkyfzncm.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtgcakkhza.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtjfsmnhqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtffmypddf.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpcdniwf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtdvxestul.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtndizbwkn.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtepgditdv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjruaucw.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotiwgcwg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvjedvece.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtlaptfxwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtxtukrwip.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtcctqfqry.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtbulcnnxc.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtwplxbich.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtirpeuose.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpcyqxcjw.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gthivbokle.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtdbksefbb.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtwvjrfczd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtnfdgaulw.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtsunjymwm.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtlxpfingf.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtfsjufvfa.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtejzykmwx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtfdnvxatr.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtftegaedf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttucsavtz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttauqnagg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtfecxkmmb.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtjqvwtlus.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtihnkrxrx.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtptbdmjog.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gtetkfriai.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtpbmjyytu.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtzjupatdf.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtjjxsgmps.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthmrfetpg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gthgcdjxfz.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtekxzdrtm.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtrjexoghp.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtdqqhxmrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtyarvpzbg.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpzjtfage.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtoirvbonh.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxfwmutqq.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtoxipsint.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtkupnesze.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtsvfuqptd.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtujvkoage.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtzlfhjywm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtreaffvfw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtpwofmlhc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtgqbwlabl.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtabtaskuc.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtillttalx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtobhzysfi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtlvwukjeq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtnpjrwhwn.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtrbjhvczd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gttfeciuqe.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtjeucxlmh.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtrylyzgxe.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtgdsgpmjs.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gteyfwsxny.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtngqnmhhl.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtgykxwvdd.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfpqjpji.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtloobfuqb.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtqzfrafuu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtrodqgmxc.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtnkylcgor.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtzhkvocwh.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtujxwblee.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtvcowkoen.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtkpijnrfq.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gttolefmdk.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtfcmjumeh.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtjhytubix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtnfhadfzh.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtozxrlrvc.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtoyagcnkc.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywuujgom.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtadlyvtll.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtllbrqoor.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtjsiyhcga.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtaiyzrwwi.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtnlpfsyxj.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtdmpvghdv.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtlalacaaa.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtadthlbni.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtamofbola.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtdwmzzvhk.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtgyaolbul.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtitjljsfe.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtzcvmntbh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtwkhapxxx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtllwpgwkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtjfnvufom.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtusjlqnsv.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtdyjvnlxm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzrejowu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtrcinqryh.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtmotnobox.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gttmhuqwrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtatowuiyb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtewwmnebr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtbhwjmqka.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtoawcsbih.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtgnpegnta.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gtgeribqlb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtqyquwfvf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtesjdeiub.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtuewqlzly.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtebtydqtp.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtvdojykut.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtomfwoufa.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtzhnbmtug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtipymfhib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtvqeulohv.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtwoxcquyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtzpeltosj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnkkafrdo.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtlkurmitk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvcjbzxwv.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtrpivawfv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtrlbuwzcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtliqrnwuj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtvasvhtje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gthfwvbpqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtnzgadcba.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtaklwaimp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtiszqfezo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtkzcqceig.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtpsshtebg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtpgrlexbl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtvlimshvq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtkgqzdmag.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtgwhbsloe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtaahlztjm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtnsczkbee.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtdgedhxdf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gthlmctlpp.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtjuehkbey.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtpwjqkbey.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtnjnzxafc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtllnoqpcl.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhvcsgxy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtwbzfyhvy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtfqphiadn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtpnsflzux.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtdehyrnaw.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtmfvsmdvm.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtgdzesbeu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtjgrlnwum.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtnmvxkhih.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtgqxkkosv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtvbdczxyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gtcmijzuka.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtnmdvytbp.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtwxdsycgw.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtwdhsgjyl.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gttmoftxjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtupnradwg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtzgehjzjd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtdyouovqh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gttyrezeyf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtecdhaxjt.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtbydxitun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtcmoloedw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtramsoxyd.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtvbzuboxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtwfhdywfg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtztjcszto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtjyvmpdvp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtnmhzuiyu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtfxvzphwk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtkszncowd.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtoebfvete.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtwhfjwxsa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtjcwacdse.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gtebzbnbwj.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtmbiqpdtx.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtyeionpju.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtbqnoiynw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gthvwplorx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtkiuikbnb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjxdokxk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtwliuqtlr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtcnwsxvas.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtusktluwr.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtvoqrbhqp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtdlxihlto.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtgskbmkqj.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtbcidzmvi.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtpgjrbkft.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gthrkkyosk.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuavjylj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gteplguebr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtccxlmmtn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtasczfbym.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtmxyfasjr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtihiewbrs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gthfzoiydo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtzhldlxln.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtgnimvnrr.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gttkpiszwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtfykwzumb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvyhrzdc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtwmyhfmno.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtzepsaxdd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gttfjqonac.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtdehvbnde.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gttbgmbkef.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtczbcpjbr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtoksydqyt.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtspzbzaag.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtihribtmw.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtsagcwlij.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtnygmhads.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtrhrmzsmq.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtwfpuunea.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtdsivftyn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtldzlpauu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtosqwuefl.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtumihidjb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtlqleijsj.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtqetfsdxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtbunolsea.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtddikegnh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtyknyfmvb.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtqdechbbq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtxrkhrvaq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtzapfdphr.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtocebfxdv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtkydttghz.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtattsktyw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhkpeiox.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtcrnrijnt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gtmirhwwzr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtdvbqxpoo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtusenvsmp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtefthohso.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtfwdckbkc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtolqaiqgs.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtyxubrcge.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtaughzpne.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtquxxdqbb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtimdvlhun.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtrmithegd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtxehqnzsb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtknqaiebv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtfgcbkpzy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtaxzzllrx.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtvuidmncr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtjsqgzmkm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtimhvkbbo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtcyntioex.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtwldsppsn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtujqmmwgc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtipinqmnb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtslhvuskp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtfyymgnhh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtsthvdhva.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtmfmjqwtz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gthtmjemxj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtzcbcrgfx.html


<!-- 参考信息 -->