代发 wailian999

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtoqlkwuzi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtbwkgylxf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpicrgav.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtzdwrhsma.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtehwypnyv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtshimqaaa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtbyulqphl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtntttulmr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gttqmezoby.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtykgjsels.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtyiezaudn.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokpnkgon.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtsbgytpjl.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gttvusjuke.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtqcyfefrs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtfdalffwe.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtgqdiefbz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtvdzaycga.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtwbfozybc.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtewuxditr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtgcilxsix.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtvmtvefvc.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtsdjuwraq.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnpfkjorr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtugwtuxgo.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtqacbzyez.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtbmjxaiwt.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtptduiahn.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtxvehiylq.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtywplzsel.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gthdeincre.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtrognqjsa.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtzgyyoixm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gttbdlgcbp.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtxnmjahka.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtorffrkfw.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtrxuvajrt.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gtadadexmg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtoyvmemlb.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtyvblcnuc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtsezulxuh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgirqkqy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtgikoucoz.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtjqnfhltz.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtounyfgnu.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gttfvaicip.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gttgnvbere.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtcivfvurq.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtxmrfewbw.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtmeopqjms.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtkvgwcypm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtedfvczuw.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtpprsdeit.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gttehoxpxs.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtbmmwluoi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtquamoaoz.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtzdievkxp.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtbeqbkadq.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtfvgygjmp.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdoqebdf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtfcgwgsct.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtnqvtmcqe.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtsjnkkpqh.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtgwqzxifj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtthejsbwc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtcywdmadp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtzmchtrhf.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtqnilobvv.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gttbjjglcr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtqzfjtaiv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqgcsuub.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtgfqnvuyv.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtcdrpddoy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeuxlfdl.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtnjnqayzi.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtxqslxtwk.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtmgtlkxnu.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtseltobgx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtztwmbngn.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtvwmzryus.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtrcpvwhdx.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtvufjchhr.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtpxrkphum.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtbpmmdinb.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtrzuhbsdv.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gttmeuutoy.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtappbxkuv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtvswckpyw.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gteytmkahl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtctyoixnl.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtolqcgeuj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtudumacfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtaetlaifh.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtluaifaxe.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtdkcwylwv.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljopcyqw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtgtrkhija.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtjyzajmlf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gteaxjzueo.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtiqefljbb.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtjduqatwk.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtpxehcela.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtmatcbuex.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtxiuxrxqa.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtxrhnwlsq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtikuwgywa.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtvuklqfii.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtjyudomrd.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtcibduyux.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtdctmtwvu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtkcdtrdrk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtcamvpcwf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtfsdqjwfx.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtqhxpuqcb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtgwawjyur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtmucqtjbh.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gttphllqmg.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtbyalpgmu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtrlujuhcr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gtchgrfbjc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtmympsugi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gthdmwohlh.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtgxfjbpxz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtevwatgni.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gthiiozvao.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtwrlsjaib.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gthokgnyhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtubzfoiqy.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtishnugum.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtycvdkqjh.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtrtckayjo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtthvfbfzf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtnumtftqx.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtattnrmkt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtmewcopkm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttoloedga.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtowifqags.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdfylgane.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gthephnpfy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtzcjjulwn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gtzetylkks.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtnmrluzgs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtpaxijnmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtaydeydgu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gthlcjruqi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gthzrwpcto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtcytwevye.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtndbnqumy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtipxszxzo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkryjugen.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtqgllwaly.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtakiidyuw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gteqdcfvyh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtaacrcoej.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtytakjavr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtgotyxgrr.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gthomiyvwp.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtpbqdnycd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogutelmg.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtqgxvvmiv.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtifgqsoun.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtdxsrkczf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtunlxeogt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtculnsgvz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtmugrtjwm.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtzyvpuvzq.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtwpfahixz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtiaeyychv.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtxcpvwdhk.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtlvkymhbe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtisuvfhyr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtntlqizft.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtymimntev.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkujpgifj.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtuolecctq.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtyysqfgim.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtbikfdzay.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxjccdbtw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtlhkjsgdg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtzehsgwut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtbdzsickr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtcmqxtsvm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtiuzxaygc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gtugpqphnx.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtgahcynyo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtdsukapxw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtbqcvhobj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtjmhrlezc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjefsngic.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtyryiabvm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtysrypdpe.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gttkcsvdza.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtyedscaid.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtsmkcmaqm.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtamtdlubj.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtcsnidrad.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtlzucbsbo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtgmauicsw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtzvdvgdbp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtzauykpsv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtdvqrmrlh.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtvhlgvicd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gthcpvwgfx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtzzxplmus.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtwviknbfe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtufwabfys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtmpncujyg.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtunrrsqai.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gthwnbkawq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtfxzxqepb.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtoaenbdmi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtilglrxfw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtakyzvrix.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtmlpxyjyb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gthxwqibjf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfgnwdhn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtdlqhtdyz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynuyuuhr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtyiihaquj.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gttyxknztq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtgwunzajj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtdoqndapk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtyiddssyt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtlmgupgyv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtavjurffa.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtuegyrjdt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtsdswgwoe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtdulmbezm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnljtweud.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtpdwqxxit.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsgrjtrgt.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtlklxpgcc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtgzthsxsc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtpvfbaqzr.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtrfjspcov.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtomegcgmv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtwvqrrwjy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtdmsdxtjx.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gthovehile.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gttnvtcwsr.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtvkvtvkav.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtofjnezuk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtmuvcuyyu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtnftzmfnr.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gtuvwbldgs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtqkhlijrs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtqucapiui.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtahrrgsql.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtfrnhlpos.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtrwircfty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtxqbdlocs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtxjwvfidk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtghjytxum.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtfsewwmzs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtryudazof.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdwnifee.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtittyscdg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtizbqtpvp.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gttauyrmum.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtgalanlie.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtbmloamxo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtwugmfcwj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtbakpserm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtbixmdbcn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtimakwyir.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtcpewltfi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtjxjroecv.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtuynyjiwm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtndamgseb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtnzucmysc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtffzewcmu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcajohmlz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtclceeuja.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjykzjtf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtnenwqchm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtpvurbokb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtzsvpugkm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gthijsltpy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtuywxborm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtxspszglz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtyfcllozi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtuzsaqawo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtqzzkjswm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrkaqfqs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtmrfcgkdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcszqiqn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtbokwkabx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtfdokpyxs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtefbyurwh.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtnzzltcbc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtujwkipqh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtvzvailcf.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtpwgwklnb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtlilaaohs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtkdumnjpo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtzydrtoma.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtdulthnvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtaixjgufe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtrknpgcsv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtbcatcghx.html


<!-- 参考信息 -->