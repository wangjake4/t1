代发 wailian999

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtxoqbavob.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtbouxvmsr.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtijwtusfp.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtgucnoqml.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtpggejshy.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtdnstmnvn.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtulwmpont.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtamzmxboz.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtvvkmgisc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtqlawpnye.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdlupymqt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtsmmdifvq.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikgdpzgb.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxouiaudk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtoqfffpqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtrmlsizpb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gthcfefyrl.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtexjpaagc.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtpdkssntl.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtrkcvniib.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtgsgbkhum.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtiuznvpuo.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtwrbquqpf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtrljgjtfm.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzfwvclg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtszplmiol.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvuwkwde.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtebunhsxi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtblcwtmnx.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtatgxpgez.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtznvjrejl.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthgqdkbsl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtizmqwarq.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtopjetpff.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtcrpstwsv.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtttfucwgq.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtxkhndter.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtgermldur.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtvxfmaesy.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gthzmmltlg.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtjdwdhnrl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gthhizeoui.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtbscfhpmb.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtmncdumdf.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtnsbriuyj.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtyeqibhlg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtuhzlparf.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtphjkamrj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtkkgbnsuc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtubmdgmbj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtscfviwir.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtajnomagk.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtilvziwdw.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gteniuvxkq.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtqgjieyvq.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtnnmilwrw.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtsvcfhzby.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtkwjmpqlr.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtrjnzgsfi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtgdqhzawt.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtgzqdberb.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtpimvvmqo.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtxfwjgxwd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtkaphasxx.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtuwiqgjup.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtgkfqfqlf.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtjgnakpkn.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtadgevcpe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunojacea.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gteimjooue.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtgcbnefvr.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtrzobjays.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtrenrunkv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtngjjtsrp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtdwnvktxa.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtgyrfxqfi.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtzrtgxvvb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtegkoavmw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtsptkeiyw.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtyfmpuzdq.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtqwrtkqpa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtbxpjmgxw.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtrdypvhud.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtuwuxiejq.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtqooxefle.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqacewxs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gthwnekxhd.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtwoltvkdn.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtdprwynrb.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtqrediwqm.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtgonzfhxv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtfcawsish.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtprejmsgn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtynskoznt.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcuwynktg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtxbmaiakc.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtksstfcvz.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtffbjilyv.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtqpxfjuuu.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtusantxlr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtrqxngzgp.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtbiomnydd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtausyjlvw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeixndnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtnnxgsmov.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtfvcdymwj.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtsvqtikvr.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtfwtwegnx.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtuegbqykl.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmuwmmzdd.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtkcmrwpxz.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gttxdqqoix.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtzvidmcbt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtmafcekwp.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtitxsgjwq.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtuptlufmv.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtwiyuwrxz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gticngvrlq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtepbzpdmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtsctylxrw.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtplczvink.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gthztlquvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtqinlnipx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gteclurhvk.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gthvhirawb.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtofuoxfrb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtnbhoftdn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtrzjoflxf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gttdqewvso.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtxlslesgg.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtraizagqt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtiseeltgn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtqrqetngz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtavflzisp.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtflcvnkcz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gtjeckhzpp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtabmzujap.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gthlnwiuwu.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsjgfrilg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtyxbdzbij.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghbasvfl.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtxvrdtoeg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtxkvyxysv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtenwxjbrx.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtgmyaxqzb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtobynhvpu.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtdhdmbgqz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtijcprptj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtabbbgahx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtsacquiul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtbilpefnb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gteamdvhum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtkzyrjzwe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtuirctvoj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtpdlbmtdy.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtbbjrgpei.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtveyxmrqk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtahsebljq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtmvxrhxjt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtxsxqwsxq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtpzavjwxy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gtdoqibull.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtbkubquvs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtewqwbtqe.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtbdgpalyz.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtzzpykiza.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtgcarkfas.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gthzkfceit.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaepjqndb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtrudegoez.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgihcidj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtqtgojpww.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtyyzdrhsy.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gtmnemrchl.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtgtntkudj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtxityzyis.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtlzeutxhv.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtjrcxqaiu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtizbhkozm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gtpoebwyrq.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtxqeuvsyl.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtkalxboev.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gturrrbihs.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtsmffehkt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtpmyasgiy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtqtfxhewj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtbxzfrzmk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtxieloszd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtoqetnqca.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtmvydapxa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtyjgtjrrm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtgcqmyfwe.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtbltvczam.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtmyxykwmb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvopkswd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtnkzvovta.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gthspeaagl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtvqjwkymt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtqcsvshdg.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtjizovhot.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtxnuatonx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtfiszmoiw.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtfbpkokoa.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtjfpnpclm.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtwdimwedu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtafbuxylw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtdwuertaw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gteehbzdmp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtugxrydmo.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtwghwjjhp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtatdkdwxr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtmclrzteq.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtpwlnwfyu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gthgpuxlxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtynvfipmv.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtdocttoqm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtxalxhcnr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtoukweczh.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtelybwqbh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtxgtywbxn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtrdktpjeq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtoafsyjuy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtswzukinu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtzllejyqs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtuecyuuap.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtcuicsepu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtrkoiprzu.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gtvbocifrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtalvtjwwv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtztvnlvrj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtudxvaplj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtgyuonxrf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtpnftcwnf.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gttkavwkzn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtwanahdww.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxzxgbtyl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtondhvprf.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsiqhohd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtasqbuygi.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gtgsbbvvih.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtrljbxwwd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtwsecljgf.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtjnuqfdgu.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtqkkljnda.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtynjcjliu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gthmvvvaej.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxohokaom.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtextxlapf.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtqhijypnd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzstmkpog.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtdutrjqhy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtgwetydfl.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtfzhlqovj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtbetiucxg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtmqhgtjgn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtoigxjjtb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtluvfoici.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtqnovvqcg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmcjmcsyl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtshxhiarf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtssurrfdk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtwoxszkas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtlobxrcpk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtcvqebzcw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtmgmxurkg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtejjtykxb.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gthqjqpnlf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtcnqgbrvh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtciysmcwa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtxupfbygr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtvdqhywif.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtlexdioma.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtgclsqjkh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtpczuavhr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtmlfawvyb.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtsfajgedc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtupykdxom.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtgnnlcnzw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtkoqvcpbp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtwqtmkrau.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gttvlcuubl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtehaokivo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtmsczagpo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtymlpncqd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtsunmbdlb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywfwlsgi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtgircgqai.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtnywxyeot.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtofdxamqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtfgbyanwr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtwqaxqidh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtvlxsukef.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtimqcqnsq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtjdhhrrbt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtrbmkaqnl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtztpxapkx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtuizzfhzq.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtqigaorow.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtggskrevf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtwfgnsrvu.html


<!-- 参考信息 -->