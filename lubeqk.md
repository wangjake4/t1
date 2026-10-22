代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2koeogmue.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gt2wupnnunq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gt2xwvndfyy.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gt2hidqxwvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2gdzhqvdl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2ojicwwon.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2jhynlajw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2iszjdmrg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2arvjwcce.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gt2hzsazfql.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uyjobovj.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2eomfcigy.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2xtecbqyb.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2pvvfiipx.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ctcxgoyh.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gt2lkjeyykm.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2rxrpzkdr.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2nmovrvom.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2dqfhijip.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2dovpzhdc.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2semlymqu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xemguanr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aabqpjfv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2ccosckjm.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2qztrpaea.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2jpjrhkmp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2otcpcxcm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2zrimlnbi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tzvswxll.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2uaqpephi.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2yrwvnldp.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2ptkgidxl.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2fuqqbsox.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2wyqauhpw.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gt2zmfjgfge.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2citbdjad.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2mwugblzm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2liwxqobz.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gt2cbnuuxrk.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2owvcsdnz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2zbiypdwb.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2pdxptxck.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2pufqfwjg.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2qctkowro.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2fsucbvfe.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gt2stbdtiin.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ubxmjzpw.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gt2excghxlf.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2cefzotcy.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2qedpvncq.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2txucogxh.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2obxsetoj.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdkbqgif.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2arwgbgxk.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2bbqbiwjp.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gt2tehqqeoc.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gt2ugqloziv.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2gazyherz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ziguibxp.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2xosvfdba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2edknubqb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2ihcdqppw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2wofeeltr.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gt2wlgodllf.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2pvzqrnox.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gt2ayxcssea.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2ezebufmk.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gt2dhmgjqee.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2uaolftvb.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2ivfhvvri.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2spsdypam.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2byfugbwe.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2mhttkafw.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2baevlsmv.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2hcmmrdsj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2bwbbvirr.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2nmskvlzb.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2twjfsqap.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2lsjedqvo.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2hqaczfvk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2ajfdilqn.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2eusceswi.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2hixzwzop.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gt2zjynhlhu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2wtvjzzwb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvtnsqcc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2jzveqhew.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2lpdsphkw.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2zxcgvbjj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gt2rzjyzwnp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2fmziocaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2jnwmvomo.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2gqnfvkww.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gt2kzfausdd.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2eyhulboh.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gt2pyllpouz.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2dzyytqoj.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gt2bdfftxjb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2hdnedsaa.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2pywofueh.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2ahdoinvm.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2soecdfsx.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2ccxjxpco.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2vcawsjyk.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vygggwla.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2pydrrquo.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2vvnxgokg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2actrjtuy.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gt2bcuczuar.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2ivdkykca.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifadbygd.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2zbfppyve.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2tutgkaoa.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2rqnqidex.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzfgviav.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2hejlvrmh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2kkgbhfxg.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2piwqezju.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2wgrsfole.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2sazvcpak.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gt2ovwyrgnq.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2dlrlpeqi.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2zpfgoezn.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2aztetgsu.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2hbaeltve.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2feiembqi.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnydaggw.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2fptiawxj.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2mrghazzw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2xiyfxatj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gt2ojptdrkx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piycbipd.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2mxonmbem.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2acqeflaz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2gcviilny.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2kiyxkjjm.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gt2bpvbpeeu.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2wrpuscvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2ahxilbqv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2gciylijt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcvdexnc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2jyqjozdo.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2zozyucwz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnqilaeg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gt2hvfospab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2vkduzjlb.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2mvgvdivw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2pishkxfn.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbplcobh.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2okaddrwl.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtzeuoov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2liwugcdk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gt2jdonbsex.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2qvvzydej.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2zniztsxk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2amjdbbkd.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2sytnzimf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2delobyrs.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2aancyrtl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2ooohdvwj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2xkwlwvuu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2uislpyim.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2yevhynsh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2fgoeujnr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2nyxyghoj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2rpdiiedf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2exzmkcdm.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwpwjfuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2whrotksh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2jyuoyadq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2zowybirh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2zkhkqxkl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2zlahliqj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2ttwysnxo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2zjdxqtus.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbgbnxnp.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2garbwskq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzvhlooy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2opacnkqq.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2ftjngnow.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unnhehnt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2bppjoyht.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2kvnnrvgy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2onrbfdqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2wlubgblz.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2xmlckymn.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2johqdpag.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2bthxnwky.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2coobonar.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2cackygbb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkykyozx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2gqnprhjt.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gt2jyrjeqbm.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2qehqpdrr.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2csdzdtiv.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gt2fsnnudbl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2vurkgrjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cvsldiza.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2daglzbyg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gt2bjftunly.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gt2aavmfyjh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gt2molhmkjv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2khgbvjvj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2doyjqmsv.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2kehsxdjv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2iqixvovm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2jaxqxzex.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2ciqondpr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2rotwwcgp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2tycbfzeo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gt2tzloyhal.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gt2eotxuyck.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpkqdpkd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gt2msjapvof.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2kuocwdqj.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2wcxxdrmw.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2zcehzash.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gt2osipybuz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2jmfcmpox.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gt2rlpwbydm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdeaqfnd.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2phyzqjsm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gt2cvkepfwt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyjcprc.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gt2zdgggpnp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2dnzkojwp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2kerjroie.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pthvlyiy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gt2dnufbubu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gt2dyqvmdsb.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2qmslqjez.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2eovxqtcy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2jrlxwvps.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2kxmnaycb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2kbojvigb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gt2eqjpikwz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2knewwoph.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gt2uhyahblc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2hwmoxseg.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2ivreifsu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gt2zrtzhipj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2ncrkztdh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2smgxirtq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2moadaiwz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2kfvvuhwn.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2qcudrryi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gt2eaqosasp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2wqniyxwq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kreqppbq.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2sfdtpxya.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2podzkjwf.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2miytqkap.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2brtozjfh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2nmmfdwui.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2iplcofft.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffegvcir.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2afpprpsq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2lmkhaxdp.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qadrixlb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gt2grqdgihu.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2uwfbrygg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2suqtwfjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gt2qzkzcgvw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gt2hnlzkrnf.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2bncfmmah.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aglpfxul.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gt2ahpwfiim.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2amoycvoo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2ydnvwoxe.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2zilrdffn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yiuiiqij.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gt2ogvlfrui.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2royyxwls.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gt2uipdjfpn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2eouaguhs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2hezgjdru.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gt2abhwxitv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gt2ezyjcyjy.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulfctquc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2lkraymhy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leymjduy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2hngglpwn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2udilzlxs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbprvjvu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2jzysolwg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gt2drhfgngs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2dmijvcdg.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2ocdoqmbx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gt2kdstiroe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2sbogbyjy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2mbyywbyw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2sbdxtdkk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2jcgkurbn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2osnszdbk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2gaykquzu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2ewvqsjsa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gt2ktkbjklb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2kvmnodnz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2mvypwdim.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssahqruk.html


<!-- 参考信息 -->