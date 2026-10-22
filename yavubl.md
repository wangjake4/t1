代发 wailian999

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtdmonrrvn.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtzbddtmon.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtgvtslopm.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtettbcpve.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkrmybgjy.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtrnupzodg.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gttopwvkac.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtllurnlpg.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtntfbjvlo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtfwxaaanb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtniqnfeol.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtmhietiyp.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfdtbjefn.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtjyvshrch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtujyvasir.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtfkvexaln.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxiveydm.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtqojgqusl.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtuonpkuvq.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtmcvqisxj.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtkxrhwnya.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtfouzhbpe.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtwjcmqrmt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtwuvrvlue.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtjoceynxe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtewpmyhti.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtmbntjvts.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtwkzklyxk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtapqpplkw.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gttauxjgfo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefbgngrv.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtjdjynpfk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtetbimtnm.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gttsjqgghl.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtvedgkldh.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtjmcycsqq.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprdpevnv.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gthugcllih.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtudvrclbm.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtvsbsepdt.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtcppwkszb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtethzjlrp.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtkvxfbswi.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtbcmuvymo.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gttplkgdeq.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghzswhnm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtntcdbdck.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtxpcxeesv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbkogmiev.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyzzcoqdh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gthptcydco.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtrmazkvqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtgxokjcaw.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtczaahnmx.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtbvaotzmt.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtjnklhvip.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtkxprbmlv.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtuxpruzyk.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtykohulmp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtgubirekv.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtgrxcbzzg.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtgppdmkst.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtrwhkgqxu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtncemrblj.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtvcgzbbcz.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtcyqwwdcc.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtcmnmxbuc.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtxoqnahsh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtoidnjlej.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjwiegcq.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvcsdrols.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtkqxjlkup.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gthelnvwry.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtcmoudlnn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtyxohxtzc.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtwufnispp.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtemjrziab.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtjphqzoym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gtphbjhgqr.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gttdbtfaag.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtcgeadglx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtoopsuxuf.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtnsddvevx.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtyfnzsbyn.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtctsakdwp.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtzkbugxdy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtgsslnzpt.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtdtcsnvfh.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtydglafzq.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtmrhaxpfu.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtljgdcssx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtvagcrycv.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtyisjmypj.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtwyprihfy.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtrepjhglv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtikptkcqa.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtrrdwlcul.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtxeyvyuzo.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtflcrpnds.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtfeychkfi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtgjlmregz.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlrfqqzc.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtlmnxfqdb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtagitvktu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtznygxhpi.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gterfyyaap.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gtnabxwufr.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtnombsyfa.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtkzfsoics.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtmyqojttl.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtspzctkas.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtricgdogw.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtdieydawc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtsjxlozjn.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtdcwdjuds.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtfqipizmi.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtobmanzuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtqixcgxfm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtsfthwftz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtoufqaevr.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtezucjhox.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsljecqpw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtfdxccyzh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gthbpxusmh.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtowyvqxiv.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtlcgcmcxc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gtriprqfsz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtpmbmotdr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtdwcuwdob.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtzsmlnoiv.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtefccbtpe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtfaywvbpb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtyfouawch.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtxcumljwb.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtdzbwspgb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtcbditfcc.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtsaueeexf.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgfwwcufw.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtedxteogg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtitqzljeo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtlpvauunr.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtjrbelubc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtunctuaui.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvnknnlxn.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleymriom.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdiqucubj.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gttrajycwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtmpsfhiwz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtuetfurhl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtkpdybhwe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtokirnmxi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtnrnqhqbn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtbqlxmibn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtugvydskq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtueltulqx.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtdphjhtbq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtzbopzxob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gttnpjyerv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrvgwpxxd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gthhxjpebm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtajexrthc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzkkmaaw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gttditayzu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwogcmkjv.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtwdhfbcqr.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtaacptikg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtgmymkxgm.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtpjuwvbdd.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtopbtoevu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtdfegjkab.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtapjujwrd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gttakwuooc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtfqyugtuj.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnvgxjez.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtdcjuheev.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtdaalfbia.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtjzlkcoiw.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtialexxqv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuocfbeht.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtnasvtezf.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtpsixxcwt.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtrbnosqel.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtngafxvlr.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtabsvwuuf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtvuypdwnj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetahbqta.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtiyjbjqnw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtloqirbpw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtwxuhvsua.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtwqocyzox.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtgfcuugmi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtniogrydr.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtjrrvmsrn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtleausqws.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtrjpucslv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryfjeajo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtxbsztosm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxtycprg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtsrtxfeaz.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtwkxaxhyh.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtcasoxztx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtcglpvebb.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gttaecumxg.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxtlehly.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtjycymfdu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsyqnksy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtlvpwrnrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtrctnhlky.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtsxnjkbxy.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gtpkbdtilp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtccqqqjvy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtatqxwlot.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtdcihizne.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtjecqblwy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtrpannyrw.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtwwjhqwrf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpidtelv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtxfgqcmrg.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtscporbgh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtvixlpuqp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtygfmhpca.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtkbgybkoj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywnuaaec.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtahdlcwld.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtqhhnhknf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtoekrwqtg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtamgamyzg.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtxxnvxdor.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtqotmrrxx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtfauiompw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtcvtzlcdt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtnccmiepa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtjkvrmqsj.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtsqascokm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtpkimxdmg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtodzrwgob.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrwifkbit.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtgshdsjkf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtksaethwz.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtxjnfeggz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtverqhuzn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtnushryut.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtjbhxayzr.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtphrykrom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtzwkfnmpb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtksdimibf.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtkaaghpgu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmgxkpxy.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtyxupjpkh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtoqguwlhw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtarxxmjba.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtkvjlrsuz.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtzknwrzde.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtttyrarrm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtlquxtmmw.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtwxybclij.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtbtkwwacy.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtnsfenjas.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtjmaltxyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtriquajyk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtzlrbnvqy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtetlfktld.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gtbaayjfmn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtoqbygnjd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtwkmdwvtl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtzyuugtou.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtzkhrnyps.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtcbjzujpa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtlbnakvvv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtyrmiiczi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gthqjbtssy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gteldjaqey.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtvwejpjyb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaxijhio.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtdlvjwnoj.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gteeckxexi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gttoozrqdv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtpvaujqcl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtxlscvbjl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtabeefdoj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gtqqnmmyyo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtlwckfilt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtciogbrlm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtarhcpnjp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtymnbnyda.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtpdbvqruf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtrapzrgpk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtcmitlroz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtdbfotpep.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtjwgibkuk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gtwvorlvmx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtanikbbkn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtoobsnxgc.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gttqpfetve.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtnxuzfhgt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gthhkopzja.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtejzncgot.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtundvgrpf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtvdpbpkdm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtnjbwjbpq.html


<!-- 参考信息 -->