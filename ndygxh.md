代发 wailian999

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gt2xmaughze.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2ikqcyuzx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2kurhktcm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2cawrhtwg.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2uadutdvt.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2thqurbzz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypqptrpn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2eotpssnq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hysoaqjp.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2kmxrlbry.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2isoqmaxi.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2gtauljfv.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2ckmydrmh.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2iahenzph.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gt2qrixucya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2yksxrelf.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2tidqgskl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2iijpwvex.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gt2utcvxron.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2rutsvpez.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hscwguil.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2wnoknccr.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2bskxxslc.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndfwfndf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2himhgtfk.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2nhamfdee.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuylnilh.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gt2ckvcrvzq.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2ayjvfnws.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2lfznacbi.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fyclpmop.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2uayujcki.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2dvbxzxmg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gt2jldcirrr.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gt2jeopdlzd.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnueygng.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2wqtzcola.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2senxbqtd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2yriejtfy.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2xupyurud.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifnaeoxt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2qzbxkscm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2utuhryin.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvngqhfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2xeunxotc.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2mbnhboti.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gt2oysjyyag.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2utdtbwwa.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2nsrutokw.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2kcslymcl.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2erycxynn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2mwcgbzeh.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opnwcovg.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gt2qfzywnvw.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gt2eutpujio.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2mijuqlbk.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2wbbxmyhk.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2jegevzyz.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gt2icwzrlxn.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2leladfor.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gt2ylldzjuw.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gt2odjgzwlg.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nmxfbuvc.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2yofeufwt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2miccwath.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2txrykwzd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2fwtjvghd.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gt2dlderdua.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfntrwdd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2hppqaoae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gt2kqjmhrjm.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2sqdwrckn.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2vnnhtyrb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gt2bpscgmmv.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2assbqqov.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2elnpscfi.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2ujzqzqdi.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2yznheqio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2pwkmodbb.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2aduzkuxr.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2qgmadive.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2jrbsrjcx.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2hnqdiluu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2symgpetb.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2exnsicds.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2fmydwmwd.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2wpdzdopx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2tjayvajp.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2ahdcnjsk.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2toxtkxcq.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2fnsjlson.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2affbhsry.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2hjuiblql.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2sbyxzsmy.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2icqmlvzs.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2hzwvnkxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2lswsgulm.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2cruukvoy.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gt2zffxwesm.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2vmfyvizi.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gt2xitqvqdl.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2aqmvfwct.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2gbicmbrx.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2jxuwmhig.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2mjsdfzbb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwmttpgs.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2ylvsgwrn.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gt2wjgixolu.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2mattuuxc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2cxydqfaq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2qrllgjck.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2rtutyuyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gt2pejshynm.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2liovyjre.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gt2igykpvfl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gt2osbntowx.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2llvbtidk.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2xlgbdldr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsaqpwhr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2qfsuqtui.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gt2xnbbmjse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2pwjfxdhk.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gt2semcwfzq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2cmzvfzju.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2rwowdqof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2qzwkxjrz.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2papofokq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gt2labbpfuk.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2jxvxgmpq.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjpsrhdn.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2vlcuqpxc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shpnywgi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2snhqytff.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2uygbrwdb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2zfxpmjfq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2vuaronwx.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2lzpbrjwo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2zpawlwcq.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2jcjkojln.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2pypiwxhn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gt2kupqguro.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2ydmhihgd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2rlabjgep.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2ribumsno.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmzopfpq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2iemuyfvf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xppgolnc.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2itatqxit.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2rnhdicjl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2faowgkxx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2reqgbthw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2vaqftzfh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2ypljljxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2mpbylnsr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2jduikftg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2awyzxjqf.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2qlzelchk.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfgvltpv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2ixbbicso.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2xldtyzlv.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2crpwdqcd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2kstdphhp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2bisaqyfv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gt2gsaczfvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ftakugbt.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hctdhhms.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gt2lyqkspcz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2iqopnzey.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2eheqlofp.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gnjzzytu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2pfdujgtk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2vvfahruc.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2qmrltsub.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwqpavwm.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2wekorckv.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpegejvf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gt2eonkqlfp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2rjaszbds.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ifwrzbzo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmnsrybe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmjjguzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2ghswpjba.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2oicopxbz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2kaujaylr.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2jjfhltzg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2qtmkatpi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2cozmdtig.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2koyzfeha.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2xhwqpcfl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2cziyakca.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gt2wyjhrybk.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2wcmmgses.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2zszfrxrx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2hxxseaws.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tucheemj.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2jblgpunu.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2kxqkhyvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2mibnzbrq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2bzcclace.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbpsofnc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2wyryoofv.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2klxgcjaf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gt2uqkqtkcz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gt2vzctjuxm.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2tfnofiuv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2jukxoney.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2ghmqcoyw.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2uyuknqah.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2juezfmik.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2bweoreyt.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gt2gduzuqpa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gt2epputabo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2mankrama.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gt2bsnddntx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2otlhjeif.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gt2gzbnwfih.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmdlvezl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2fsbadzmb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2ycejywxq.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2joibqblq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2qylmgewe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjnwmhku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2mtawncnz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2yetntehc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2jcjksmnu.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2peeynyts.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gt2xriauxle.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2gyvbcplo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2cbozcgcu.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynjaxfof.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmpoiodn.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2gaszvena.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2jlqfemer.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2wdkdcury.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2pfjnikyf.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2hgvfxjnd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2alzewjew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wigokmbp.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2fppjwboc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2clqkdphl.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gt2tsfqhjnp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2imqwihuz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gt2cddaeqsw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gt2kzodwzly.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gt2czattoyv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2bwlulubw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2vkpwojcn.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udwfhhir.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wrlmwfui.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqfzcsip.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gt2nqlnpspp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2woviyszq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2ejvgcdbk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2uxxbtrlh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2zxbuhqsb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2bweavcbg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2tqjdzmlz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2owreiqrv.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2cziqixye.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmhxvqqp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gt2oylhmsss.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2fucvewyh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvcmwmzi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gt2yfvgidfv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2eqgdvgey.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2kcrhnzsx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2clzztbxx.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2yqjtnisr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2lfrqbvpf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2hqmysaii.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2bhysyrtc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2iwsdaidu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvoqsppz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2yhzgydpj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2uzmqqery.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2bjblwdux.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gt2loyrited.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2xfgnvcar.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2ubayibeu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2frqrvzzb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2dwrrtsvr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2eyrgkqjv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2bxrmsepk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvnxmnkc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2meivjqcd.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gt2heuqmsyz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2mjvfzyor.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2yxjyrrvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2cfepsijc.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gt2jannwvtc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gt2ynbmvjzx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2vxbgauto.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gt2wcyxhhqf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gt2rrikiiyb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2tbpcqght.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2jplswkrf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2pcinuxog.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2trdlqzpd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2vnnjkwmg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2ewltgfqw.html


<!-- 参考信息 -->