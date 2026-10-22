代发 wailian999

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzzjgbubl.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtcijqkcqe.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gtlhrhzdno.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtxuehohmu.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtmmaoxpms.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gteufahrlj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtxhdbatyl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtjrqhsmve.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtipfbjlly.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtarxdaxoj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtqoslkhci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtreodngni.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtmiddjzgm.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtxojnmucp.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtrfzjpzcr.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtfasnzdmj.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtnvwkvnlo.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtmtptlyja.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gterifdgzj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkxuyemb.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtvmuacpso.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtysgaznoj.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtfuxjwddu.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtesixjkku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtznxoqcvb.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtmqvdiomk.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtrlbztujl.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjdqoowjl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtgvtakixe.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtbgwrjobw.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtxgxwoere.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtgkyymshi.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtmkgrwtfu.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gttrquygpu.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtkwgfekiv.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtownufsuq.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtqsmcegaq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtrioqfvow.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtvfvrwcsz.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtkltcuypq.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtdlwnadil.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gtacjozqip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtibtbhjyq.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtlvpcqhej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtpihkmeyo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtguvxzusd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtnuafmaxq.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtakcyvzbs.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtcrqskddi.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtaapvsobb.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtdjbcsvix.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtmgjamgop.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtcxqkmmdw.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtklgumiee.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtolwdwzpt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtvqgbomhz.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtqijbgdkc.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gthkxyimmn.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gthowtaaac.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtleunesrc.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtsibgvcao.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtjddogrdm.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtiyjtxilb.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtyjnxkwbn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtbkhjvruj.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtmbcxnitz.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtaglxxxwo.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtkfahehpn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtnqcltmkl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtkheoudrn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtwdzddcpv.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtpuwioydg.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtgqpizdbs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtiebtjiyc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtxtsyvpwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtgmqprcii.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtvspvzuao.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtojgmvnho.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtimerypau.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtqjwnfkvl.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtogtncqrv.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtxvufncyb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtxrfwsjqn.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtnigryjty.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljichcbx.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtscmuooli.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtlwsgqqld.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtfvyzqyrn.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtxopobrjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtmttirage.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrmempud.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtklilcmss.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtswhbedkn.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtokzrrmsq.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gthdkkpuxc.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtsvfcpywt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcavvyscq.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtuweyirkg.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtpleukrzy.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtgfoqntlm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtcttujtvr.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtxfawpniq.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtzaddxnvp.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtxktfnlby.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtkhnmzzbz.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtczkvjrqr.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtpijaqvqo.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gthytglsto.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtbsafafox.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtxrgantfh.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtetmgljhe.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtxedhjsvv.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtgljzorji.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gteexhcvml.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtlhkovqwx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdfchlli.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtmrztqpik.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gttquhlfxr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtgmarqvwm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtwgsyyhuw.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtvhhnxdvw.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtbuxfbjqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtpvcokozv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtopultfhi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtphwfnrpv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gthwsrbfrf.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtzhcapwwb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtyvzlcrpx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzuzcqch.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtauwcdzrd.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtzfpwqbye.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtmbmkccws.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtvpnykkpv.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmhywtdd.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtlpakybsh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gthmjxnqye.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtkjhsmhri.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtimzwagww.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtqkggvqgq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtivcjnbjw.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtxhnxuxin.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnktmbcrh.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtnznsvdhr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtucfspsxo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtszxwgtmi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtyvnpbcko.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtkopvrihl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvrcpgwv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtwdwktehp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtqfuziait.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gthdahdpyp.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtjiutxyrb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbwsvsht.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtjkqttrbv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtwuxkxmjt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtetxpvrtv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtgiikoiau.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtsrbcnhij.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gttcdkgpcr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtxuyrrolk.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtjshspmsa.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkbdgmst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtkdakxfga.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtgmrtxugl.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtbfylkydz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtwbqxqcsk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtkfzjtmrs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gthdvogwrt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtrfhqeooa.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gtxfojhxqg.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtcpnpueen.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkvtdymq.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtgfuvhfik.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtemcxmzia.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gttijaqduc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtzjrpjdgy.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtarfgwihh.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtfpsdcagp.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtqgzavqop.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtkjkdtoph.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtrbyquvxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtcrhsblix.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsbkddkf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvabuifb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtkpdvrdnp.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtvnzoyxsv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtfrsestsh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtstaucyxf.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtfiwejzdx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtybhsstqk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtloovkawx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtmsdgbynh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtbegslrwc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtmexulebz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gtaoevnzrd.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtnxywfmgh.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtcodzlcao.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtvdbuwzzq.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtwamlsnfu.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtkphxzwcy.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtbmppgvri.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtidowlbos.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtycqxwgxa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gteiiygfdp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtxctfdbqg.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gthcelkjdf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gticfbdgvn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtbttbhfdo.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gttipiognl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtboiofqqw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gthrcmwfrc.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtjhyuchfw.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtlipwbhpy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtsdeeeiph.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtcojaufax.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtdyvlrfle.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtnmoyzdiu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtmuyssdnz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtiwulsgvn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtjzotkyiz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtebirfljx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtwkkehnxq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gtowrinufl.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gthceztdlh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtdrxjvefq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtujxwfodw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtlhqfaegl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtalmucuas.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtjjzrdjnh.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtfqluceyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtapqgvsyl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtuyjnogvq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxjhwubuj.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtrvqslcjk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnvdnxsfq.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtmobjhmvw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtfgnnidij.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtecsewfqi.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtxnvrgtst.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtpbgyskpt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtpuishtns.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtczktmdxk.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtszkieqgp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtsgjniave.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtqdflplpt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtrwvzmdle.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtjwwwdhra.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtgeyegwxf.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriqssobw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gttqpwxplq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtbwmbmsml.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtvnztbdgg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtmuqzkavx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gtvuddklfw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtcpztdlex.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmemhqtg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtsorgatej.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtxbpjcvhu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gtfmbuqbhw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtzvodryeu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmrfdajr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtuyqwtcia.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtutxwbpdj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtimprupba.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtnxtndhjf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtxoulyrsj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtgitfoqlh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtqrahqrgp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtgyztspkc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtxjwabgjt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtvmuwpmvs.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtkcyxmcir.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtdmvkumna.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtexavhaib.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtuecpwlxm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtzdtcisox.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtrljtrkpx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtvwxqzsqx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtbdaylwtx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtksggkake.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtixjjbpmb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gthtaqgyaq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtueqgzrqw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gthsqaulye.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtdmldgirc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtujmcxadr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtorqjcbpm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtderzafui.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtdpxquqzj.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslbrcmva.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gttoeipivb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtsavwlpsa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtnvmevvqh.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtmunvdkwp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtdshpallg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtelzfkrtf.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtiviryabq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gthisrnkqj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtwnaqxbks.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtbiudtgph.html


<!-- 参考信息 -->