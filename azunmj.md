代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtqrdnxhve.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtpfqvyhbp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtpxfxxjmy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtcsrxthad.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvalqrkay.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtgdsdxfhn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxjyzdnal.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcderqzgi.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtfjtmirgf.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtvjdfylzt.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtcgzxhmob.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtdhpgjwzm.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmsrfucy.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtmcugsqgs.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkgnlhnsg.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtuhlcrqpq.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtlceicphm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtpsjorbpg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsequrzzo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmycwbqvv.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbafnjoe.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtjoskusut.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtwwhkwbsl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtebajdchi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtkhhyhcoc.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtciyaclcm.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtrzsssfpb.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtcvsotfyv.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtktemkoct.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtgeaburkm.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtihygwzrk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtvnxkkujp.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtujbsxcbs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtuyoyvsoj.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtfchlinhi.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtwlpkqpwl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcjkstcsu.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwwscykdi.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsgjkuyao.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtcbmzmiqb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtwinbnupv.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtpcbrtrmg.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtkwowbtiq.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtbcpktaac.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtxaookyoz.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtesxjpulj.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtrpfuaftp.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtipfrxwjc.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gthrigkowp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtpvisnjgi.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgkgnezq.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gtvdwhpclo.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gteqcwkmtr.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtnhelblff.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzynphix.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtexrmklup.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtfsduazid.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtuyhrnrud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtyyfurwnn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrbompqjl.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtpueomgyq.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtrusnxsfz.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtnmzrceco.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtseqpnekv.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtpjxbgpsc.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtiiuqgbrv.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtojyuxgmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtqroixggw.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtxxlmioiw.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtzjzwxjud.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtoykmtqmv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtublmvgmj.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzomzmksl.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtbakxqanh.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtiflwlyya.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtqsgdmcqp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtvequdzzl.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvzqihhgc.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmdxopoxw.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxcthavb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtymnjxgbt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtclybewir.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtnnwgsvyf.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtwnxnghjz.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtvprhtoaw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtveouzlel.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtmcdqhkxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtuelbrbqt.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtjphrjiok.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtuiasmhlj.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtxlilcvsv.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtqmayjkoo.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtkpfxoljj.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwomgafsf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtlenkchhb.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtfabnnfiu.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtoncjhske.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtkbgzhzlp.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtjggdhyhi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtzvsqbxhs.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtqsdwskty.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqdjmsvbq.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtoisbfeip.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gttydfbhhz.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtulsnuxjy.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtayplwlzj.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtocrqmtye.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtiqydcqkw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtdnlmezrq.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtxvlzktck.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsnfkcgvm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmkmgppuh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtynkvpmsr.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtgpjxsivk.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtnmgmbcad.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtkyputpnh.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtcxejscpb.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtknvvahho.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtnmuqdfsi.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtvljnphbx.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gttzjyuqzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtwrnhxtut.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtotmwjqma.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtprueqswn.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtbgubvmos.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtfbugoyoq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gthdtbijfb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtxnwlizkt.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtcceyuekq.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtkeqqqggc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtbdqvcnap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxzdludg.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtisuhaaee.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtjnfhalib.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtlwklxyuy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtzthejivx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtlitujqqs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtwgzliymt.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtcqsbfbcj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtvknybexx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtdnumkxio.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gteitnztvb.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gttrbiting.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtxnwwyjls.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtwbtdyfah.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrjxyakov.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmpdomutt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtqisiwdng.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtrivweapl.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtwtxhvzyq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtwqhsqumo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsigbkkts.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtjjtgiads.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtotzluhgp.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtexlaglbg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtfryrvmaa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtizyukeia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtjrnboumo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtgaapbytl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtcddagdrf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtvisxzjzo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtwyjvgucp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtmmpkacyx.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtfhbdkmob.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtrryhhoic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtiwcamjft.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtdqwfyuyr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtqdcwpncj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gttsjwqfet.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtijkzdvxf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtfbuikbrg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtcmwcisqq.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtwfkvxtey.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtioujllyd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gttaiayqoo.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtazzhlmni.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtwkbtcctz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtbmyvlutx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gthhkcqchx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtbvhknnvk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtsnzppgmz.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtljygwqrm.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtldksoagk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtcgmxxtlf.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtmgtuwswg.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgqmvyfjb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtjxpetvtb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtouflvsmb.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtktyspsdj.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrxvfbydd.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtmgcbqrdo.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtgvytkuyb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlkwjmwa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtqedgduly.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtsoizjdqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtljtgorqc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtytdcuhwk.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtudglbhlx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtisnltahf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtwshzhqtc.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtsavaxbzz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtkyxdsrxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gthjluiffs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtbazuxijt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtuflmhdmo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtwiewxdfp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gthafywfmh.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtsoetcrrq.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtkzdjmcbc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtazvmcakv.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtjmjvozwz.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtjmownglq.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtadpdzfpm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gthbpjzzvs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtqfvxfwdb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtmcynjqkk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtjmpgfiky.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtwemmpbay.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtubjmudeu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtrfnzdzbu.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtskchmrfe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjwhpiaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtcvhaoxbj.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtwdhbukxl.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtuzvebnpm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtfyalvugp.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtocftkomi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtqdrwqxgk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbktmwuke.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtxwgzsvop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtodprmhbc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuulvzlmb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtfusdrttl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gteemsisuy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtamokmuav.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtmywnbgfa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvneirwrg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtjijlcrnx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gttsydjnvq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtgemgnlyt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxxszgzt.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtbsdaauzc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtphtwgbgt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgbxiuuqy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzzdlnenc.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtwskgugix.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjlcjogri.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtinyhjvkl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtbsloquaf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtboxsnudg.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gthcsichhg.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgldelrvc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpjaunct.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlfbkzbmq.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtgifdlytu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtwmnstbfd.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtseyjdiyh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtzgjoumgv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtdvgbervm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gthgalvpae.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtlyzvgfno.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtmysfrqvl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtykwtjeov.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtfoicqcjj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtbksuvvxj.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtgafqkccu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtqlmrvpkj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtgywbkabv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtlecjonii.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtggkqbivq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gttzoipvts.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtneaaatkz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtasltxapg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtbevsdtba.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtgdngsmrx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtgmceahny.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtjqpidpln.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtlmdskpmt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtzlvjsbvg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtvmjkjabi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtsnlesmvy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gthzbgemhb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtgkmktoim.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtcuurreat.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtywjmnpwj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtvgrcyejj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtgxeildfe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtlfithwsl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtihuyzvdn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfgmhswn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtsfifcvuo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtukgtxoeu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtukqixekr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtxiryooey.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtmgjuwwud.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtjnfpiwwh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtlwwtquch.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtjclpshpz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtidppgujg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtjcyecdzb.html


<!-- 参考信息 -->