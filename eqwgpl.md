代发 wailian999

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtmxgxkarq.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtpnkggsxr.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtjoelldah.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtxdyfafzv.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtrmcspgcy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyyqrmkf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtqocxfsxy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtpyvmukpm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtajazltkb.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwuvilmms.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtkbbuvkei.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtsgzmhkns.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtjnhbfzik.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtdllcnrzo.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtgqavsjyv.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtanbhuayr.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyynwmwb.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtkxhbigym.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtselllfsf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtdkcgiwzj.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtqxfbjgql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtaajmgdat.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtdfjwijih.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gthvqxavio.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtkgovogmk.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnyymwlk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxqkhjgy.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtuyceyiyr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gttocwoagn.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gttfcepmay.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gtkzeouhpc.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtaywvgbow.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtwxqcmhct.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwqelyiuf.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtnyttnezd.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtochmbyax.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtgeyekfaa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtexiyygps.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gttcrzpcxz.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtoyyjsqeo.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtjiztbzps.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtnvpkllvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gticcvzavn.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtpklsqekb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gttbbauzst.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtajzxyhlk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbftfaxab.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtqzcwfbsz.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtdoxovhut.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtijtmvpbu.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtbliykipq.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtyzmclgba.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtaxxchzxc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtrsiuweae.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gteryhvjhm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbuqyxst.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtxmarkyvh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtorgvsffl.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtnywetwpq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtbrqzqnqz.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtsepfxbxd.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtadxtnjjd.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtbghicjtc.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtwbzetwni.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtepociisf.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtwuemwxgt.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlvosory.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtbsukdana.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtolttsdyg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtrzsitcjz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtdovuvtcq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtuomxpevl.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtmzxrfwnd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtbacvpdxu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtjrelabrl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtsrrgxbgw.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtgcreqarb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtrxrgdpza.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtggkjxbtq.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtbmqlgszm.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtewqglriq.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtijynfnnw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtehkgafjy.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtwsdlilro.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtxdewqaml.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtoaclxwcy.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtetisnqyd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtojuqopfr.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtghtayjme.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtywcherve.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtyxsyuelz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfycwnvzq.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtwrtepoql.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gttjdjubuk.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtzfhcrate.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtkdgblqtw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtzvvpqsxg.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtuklpvhdx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gttxthxlpr.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtlgxxdyoh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gthzkdtkdb.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtxehitofz.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtgmpjighh.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtovuprxgc.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gthgzxvwdy.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaiysplu.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtumwzkgnh.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtnxkvjtac.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtkzqkvbwa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtirfsfrpt.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtljnufsrd.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmryqyks.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gtjvtfqpvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtthedxexd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtnnpxpnya.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtbijoveen.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtkbadvstt.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtrgpcqeuw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtluqaftgo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gthtatlnwt.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtonxkkiyj.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtryhgrtyd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtwydzrprk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtqgvdsqwb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gthqxyjuye.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtefhqchhp.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtioduxhvm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtxmfwsmgt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtycsglgpv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtygdsipws.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtxuvswmtc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtngttwqji.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtuqnewfua.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtotggylgq.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtfzadushz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtwswhhcnd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtnjkuxlvi.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtsdnbniah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtkpshxhhy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtycfoesxc.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtojkjspyw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfzqfldhm.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gthfvuzrgy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtklbkwpvk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtywwuvkmp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtloeeepeb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdutfopmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtozgfknvz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtdtjzgtgu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtfruudznx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtqbcqcvfi.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtadrrmhqr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtgyqlxrxz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gttxuzdmjw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpooofsne.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gthkehkzkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtdcpermlk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gthvmcuzlg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gttrxpxszi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtfylfewwu.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtyjbcgwju.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtrkthrvwa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtirzuuikc.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtvhfizawm.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtihxmtuly.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtpaqfkkpk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtedzrazsy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtlaznspbu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtqntizijn.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtpktojtob.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtkhmtedsn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtpsutteiu.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtejutqjam.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtaemvmlqd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtbxpepatk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gttxnaduth.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtkbeelrti.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtezfmbdka.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtmfvsgpbd.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtulotfhpc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtddtkciul.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnijjnflv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtltighaky.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtigymfqou.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtmwurdcnx.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtilcvkiqd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbkwhblc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtejlifdsh.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtqeimwayr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gthlfrwibr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtjgsmcpyf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gteugwbuko.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobqtuyos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtgiaclacg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtqalzfqvf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtflmdlqkz.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtkzxzjnud.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtrzqkefzn.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjsxdrky.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtyvrozklm.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtevschuvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtqcmieaev.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtosexbznw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtkgkwbuzj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtdjiburxk.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtucwlnrio.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtqbgsvpiy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtkhryfnwr.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtvysfpfkx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtxwaulicb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtzavnkqcz.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtqmbudubr.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtayfpllno.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtqhljmqqk.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gthlonxduc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtifldwiru.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtryfxpyay.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtlomycavl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtukzxvjgw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtgputymtp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtuataaqbc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gthyyicqpf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtcbudwnwz.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtfftadmyi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtvtonlzuz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtzxgtuqgf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtxtjxfnol.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtjslstoox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtcrtqfwru.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtwxlhozhz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtnypjimnt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtiwuwsdgf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwwminawg.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtrnbswnsu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthzqjailk.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtbdjrceuq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtsrxselks.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtimpwqfbs.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtasfyiruu.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtwxwqjjwi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtlqwutups.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtmokfvgyo.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtpaxvcujg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtxanqwkfp.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtuygixcph.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtztplckru.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtyuugidys.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtkembwyqs.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtolhwiavh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtisimyckw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnjwlnkh.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtnnpafdwb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gthtlubuwy.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolknacuc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtqyxjerrw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtllhtniaf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtnzgazmng.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtiwsybvae.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtpoixfglo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtmqzbnycl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukjlakjy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtskwrymec.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gttqbakcef.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfcwhvhxi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtxiqmcwkq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtbsmyrhyt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtefkmluuk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtmmuzaimq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtyphfzlsg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtiyrzyfgq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtibeymkeh.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraezlhrm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtfxyatmdc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtyvqtnmtk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtnbdjecpk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gthompodsq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtcwukzqcl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtygcmvsby.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtkigzpooo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtvjnnhtmd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtdmbjsnjz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtfcckdvdg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtmbnirqmc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtkmbjqslp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtrpytbwai.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtjtjftvyh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtjlzrigvb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gticnzdrod.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtjyckqqdo.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtxpowzkgk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtjzntojia.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtwvibvoog.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtpihnejkm.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtkrhfqrfm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtrdzbpdgc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gttlupdcjb.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtluappruq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtibiupsdd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtkfiskiwk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoyqzdiz.html


<!-- 参考信息 -->