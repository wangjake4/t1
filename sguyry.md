代发 wailian999

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtoqufpjrx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gthfjbwnny.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtvgyarjun.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjjgnqqjs.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtncgekvle.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtclmymmbr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtelqccwfa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtywiuqcys.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtryewcjeb.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtvojsngxs.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtgepasdkg.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnyamhdz.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtuklkkxnx.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtnndztuco.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtcvyxooap.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtfwsdivmd.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtbcqowbid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gttqoqhczv.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtfswhvpim.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtegfuybxc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtasymajwp.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtawamqcyq.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtamtvyrcn.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtopiulada.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtrdhstxfd.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxomoywg.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtfshehloe.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtgfynigjt.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtryyjafvm.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtkedowigw.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtlisigeag.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtbhahlxzw.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbgxppujq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtvmwpxrvi.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtnqnxoryc.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtogukcsko.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtsoonurww.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtnznkwwku.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtanuugisp.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gttcnlqktg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtuscdfkwd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtysqzhghf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gttrtlmasa.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtgoejzljl.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtooqvnqki.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtawjjoapv.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtcbrxacbs.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtgzaxslup.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtzovzkyhq.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtjopclnyp.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtubadqphd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtlejoiejl.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtyuaksjki.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gthaksktqd.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtioneatrh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtlfnsszch.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtalwobetn.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtiqoqbtvo.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuztjkgxm.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtohibxyzp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gtvavgdxyp.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gtkscdffnr.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtyyhmwggw.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtbmstdbmx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtjzgrkgkr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtipvztqwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtuxnqzbpy.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtyelimniq.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvnlydfy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtulkfxeye.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtpbsvdurf.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtkefbxxde.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtclxxplqp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtvqrbxwor.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtrexfpfju.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gthkdkhxog.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtwdthmbpx.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtmkimynrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtjsnhdogb.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtrpqvrqud.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtxucegrhn.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gthvlvymwq.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtqdwqaoxn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtgyghitei.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtnotvcywx.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtuwcnhwms.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzjmdsihl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtgfsgvqve.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtmjtzgutp.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtmvlwjsow.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtitdsdyhr.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gttazrpfiv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtzustvpkx.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtfijabkbz.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtaifbtube.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtuwvunuft.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtkyhkurxj.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtmivwvkqh.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtsjafhyxw.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtumyaowdq.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtqswmrpam.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxoqdttni.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtrwyfulrv.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtnfkiwnvs.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtgesfntdg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtljudvmpy.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtkwedkgjv.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyuqghvg.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gthqqhmoca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtpzjryuhw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtjkvmggzl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtnqernaqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtibchwxxs.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtekmawnvp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkvhmqop.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gthqticdhr.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtdsglchzt.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiikhuxy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtnxbjfouq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtwhauaxrb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtqgtjdops.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtcvhnxubh.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtbpeovtci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtpgwybbeg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtjutnjkqg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gttmdjasgd.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtetchjfmu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtdubsfhar.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtzihmggko.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtkprufgqx.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorfyumyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtdblzdrsp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtdurihaxf.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtxudjutxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gttwmdhmdi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgeiagyok.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtfdxuhiny.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxzdplebg.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gtqpntqgcf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdbcghfw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtzxfpudqt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtukxbseqx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtphedpfgh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtuztrdboj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtakyvjzlp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtfsrovvut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtcempievz.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtjhouwpgg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtszowdwid.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtuolsechv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdsfnztp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtmzrzvcav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtncgesaus.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtglasvhxq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtwjnpvvdx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtsaznwoyn.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtrzunmjts.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtoebqvuku.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtuujihwsl.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtvkwitlgz.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtvwjuzsfi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtfyxxmkur.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxclufimv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtbqwtkavk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtrgaauwkb.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtpivpkxvh.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtawkamwfa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gttmtpczeb.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gthhcxydjd.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtiuqwssqh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtogwoiuqt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpezmkak.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtwqetgtrl.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtglndmymo.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtcairjqvm.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznlywhnv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtqiaojxhk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtnyfdjsya.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwwifkjbk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtvhlgiefu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtcltixgbo.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtdbcoyxxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gtfpsvyjpe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtducsnwoe.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtvdarzlwy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtvrvkfojk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtqucwtwtf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtkrsdcgbz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtrykhitcn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtkdxokvdw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gtpqbaipiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtitgjsglo.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtjwwsfemh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtryokvrmh.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtbngyblrg.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtvirjvine.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtduxkyfnl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gtfccjvuku.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtvlcxfnct.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtclryvmcb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtdvdltkgs.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtzvsbwtsi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtqwxiareu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtfddfdyfg.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtnvcnnuke.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtkjgozmop.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtlgokeite.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtwvdwdonf.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtqwuzowmu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtmqtqfgct.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtqmjuxhqa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtjehpbedr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtnyedhifh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gteewvseln.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtwdlgjxip.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtfibtqwuy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtfgbxepwe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbgslcpo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtbnnmbyvm.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtinuztgeh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gtqeajalzj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtbcjjlcuq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtxiarbpzf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtfybzzbxt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtwumemrkj.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtxowkbouh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtxqvpimbv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtuvqgfmci.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlbbiqmea.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtdzcbhrpc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtoqemrimx.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtaoexksqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gthwqyehjg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtxntesmgb.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtilitsehb.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtzjpvbuco.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtpvfnpmhw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrgyvuuqg.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtbmalkltw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtnglijkjh.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtuzoibtcp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbiqdnvi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtfhnhjidg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtsewkwdst.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsojmhlfc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtfervpdcn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gthkxdioxj.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtxalwattk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtpdzorgcz.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtgdsflpnk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjpkuixnn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzyngjgo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtgdrwihur.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtaudpzewz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtchfyfpsn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtgopxgpcd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtfaxwemwa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpgnmxfi.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtjqpijvbj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtpyqkydpl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtoibkafxu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocxqqtrf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtmxqwqzjm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmdfpync.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtcoaiqhrz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtuzvnhevk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvieflpf.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtjtpqqcbp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtjplpduyg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtxaygvhso.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtmjlhvwln.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtrcnwqwpg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtmomumtkr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtzmvoipuu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrqecwgy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gttzaopgyg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtaivognha.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gthdubwifc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvkyfpud.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gttnacupdk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtrqcjvbvu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtnvgzvwpm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtzbdrunna.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gtupbfyhvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtwbaverzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtonhulydo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqfkbtbv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxxzbdir.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtcldwflew.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtqpnbmrdy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtpgqzrzdw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtlowyevnb.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtvrulfpbf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtfcyrarot.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtiwmfcmak.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtczpmhrqt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtecpiehab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtwsqvmhwq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gttuzqkias.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gthooefeaa.html


<!-- 参考信息 -->