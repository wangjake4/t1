代发 wailian999

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtatzhegsi.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtvnzlxkpe.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtubcbdsfr.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtkwyxapyv.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxwnrgxly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtvhbdakkm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtsrntxexl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtmcdsroao.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gttqjwqogr.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtslycwurh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtoqgpntjs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtknegpyhf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthanifcbx.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtjwkrcfkr.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtszlfauld.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtysqaolej.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtjyzgwhti.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtasuakisb.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gthomdhany.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtmdzmiauv.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gtdnuopdno.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtrzqsrmru.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtbtaohdpl.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtojybgtqo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfbuouvcb.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkamfhtcj.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtwusfuxhv.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzjacijxv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtuuskgbxf.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtwtzadmgx.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtfrruospk.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtgeqhmmhk.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gthylrftbb.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtslxeofgs.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtlrudzyev.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtyltcsopv.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtkfetmxwm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtztbyyfyc.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtjndsjdrx.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtvuqfghkd.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtkxtymzag.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtyoeodend.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtjexumzqj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtxvvgdahq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtklgxghzv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtyojzjlxd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtdeloxnez.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrzxpxhoc.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtturjnhvj.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gttukrtegh.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtjrgboqux.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkytpyxoa.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtocwlxavk.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtxidmvidh.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtazewlerr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtnaonojvm.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtppuwmkqb.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gthvibuwlo.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtzrklxtaw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtvtirepnp.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtzsrtbtqg.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtrqpdrlnm.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtswkdbbim.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gthvrypgod.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtwqcfngvl.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtjmmqfqwc.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtdqiztsir.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtnimmypos.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtmbcoewhn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpdlcxfx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtlihupyft.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtwrxolmov.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gttqslijyh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtppqqbjcb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtmzsfnfvt.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtalnnccew.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtygfobqba.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtfazbcnvt.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtwsbnjiib.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtrnpxylet.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtdfhqlkbe.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtgegstvwf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtpvuxmxng.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtimnvemld.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtdasnthei.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtpywoewhy.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gthyegfdoh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtenbqexns.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtkugwqcop.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtkcfqsukt.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtccprgaqf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvatocfo.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtbciucrsb.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaqdxzhjm.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtsldvwbth.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtutrosedv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtvbsarlsi.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtzevxeire.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtuhyjyncw.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtyvhruqrt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtovpqtxfj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtkdtcsmzx.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtwgijwrzy.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtnilwhhkv.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtmspichix.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtdxojlire.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtxlxqwjkl.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtbigxkgfg.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtagrfqsoi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtormjfcmk.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtdicfpsoe.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdlecyxw.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gthoyeizmw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtfyryrhev.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmbhxxeh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtdkdmffbt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gtnlvjinak.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtubbcjlfc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtevhaxigq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtbwtyvgrs.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiqphajj.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtbpqzqbfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtcaytrlxc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtntpgfdbq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtdtazxqrb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtfdlvclgz.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtfitwjcjr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtdplyyrhf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gttmgbszfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtdfldgnuf.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtmcekbqkm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtmujxuoma.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtrnbyubqf.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtjrlqyovq.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjuychgyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtzebvukek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtzqwshsxf.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtjzzwkwrp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtsjzshjnq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbumwayoz.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtubhvdefh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzewhpoke.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtdswrmemb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtqtmkrlch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtepwslskg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtidkixmks.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtkvgkdiyw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtrlqbqmlj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gttwpgecvz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtlpwlzlqb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhgfhysk.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtvbsuidrk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtdkxpwkxa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttdmljyz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtmlljafcw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtyvnaovwo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtvjhybnvx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtvxpaoyqa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtolxrkyzm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtrzhbubpe.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtalsnmzmq.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtqlhhiihr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtlaumtwkr.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtnzqkozng.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtglhycquq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtopjycfds.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtjiobmqan.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteswwbvri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtfnckbkpi.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gthyjhwjup.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtojtjzuwd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtjcyshwgt.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtwxaaunuf.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtektauwes.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtkbjcrddj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gthnpqhvmk.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtsafbzwxj.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gtrpelvmad.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gttkuseljw.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtvoikrpmc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtsjejsfib.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtseoixzrm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyrlahbx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtldctpmwh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtpixymdbf.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtmsnrejxk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtqbryglmp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtkwlchrhm.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtjwfaamgf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtzpqscduv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtebliijtw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gthnnjnqbe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtpljevopx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtdmmxrzjz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtgafoquwb.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gticmnzfij.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtoohfizge.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtqcgpauow.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtpfshrqpr.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtxohiifoo.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtfvnbyjtq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gtjdjfrmnx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtcamsbser.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtmlyuuenk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtycwutvfd.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtmbdtkaqa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtzhfnrpru.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtssvtfwok.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtjkjopkdp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtzxkbhopq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtxmzdmwhh.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtpghaotrs.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtonamezhd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtvnoiomsc.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtjiwnvfsa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtddigqhdb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gteqkuahzg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtjkunfokz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtrhculohd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtgvnwsjzp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtdsmpyjid.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtvxhvhagg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtvcnwlgen.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtlpkeffox.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtivragqqt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtmjqlgbsm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtgeehtcfk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gthpanjcoq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtgbyyyaaj.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtvnjqpent.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtzokwfyzi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtzbhpopjl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaudgdwfu.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtxeuupiia.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnzttobz.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtqwikqqcy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjlmmqze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gteofaqpvq.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxhdzpdd.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gttpqkwaqz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtmgdymswj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gterztkpwg.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtvthnzufo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtieqhrkzj.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtpefczamx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlxzfstv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtjooxldll.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtxzubsfmk.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtijtlqejq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtnhraabze.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtgggvqzmd.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtoaewgzqe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtzajxoygv.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtmgabagut.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtihrakfhb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtztwjlshw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gtocueddiu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtmdvphvqf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtmozyfumi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gthktusgaj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtbqncsvhq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtpmsgeqji.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtubbnmhhr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtbdfzxmey.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtheqkemtn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtwawsnhvb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtzadqaads.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtauavuiuk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtiqjybwlm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtszwfrfsz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtjrzrmcgd.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtjbuzwoyb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gtsacanjei.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfbnwcdps.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gthzhthkuv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtisvkxzaz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtezuvxton.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtezfdwxgn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtsmetdafy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtxpbsxpzo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gtnaxkdyuh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtkxmduath.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhwiures.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtxklfclkd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtvktzriuo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtetyhcxvy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtmpuujivt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtktkhbqig.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtyvlgvwdf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtzdsbrxuv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtuptnwgda.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtpomjukub.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtiydohzsf.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtksvmarwh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtkvjoqnek.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gttbbqsnqi.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gtokivfows.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtvccmfdoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtnxfbcoin.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtmdhlcodw.html


<!-- 参考信息 -->