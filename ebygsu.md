代发 wailian999

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2tocwyaak.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2iistrfjb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnitbahc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2ccuclnjj.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gt2jpagnqyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqpugmmi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2nosxppcf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbpzkddp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nbhzqige.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gt2zjvxhqut.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2kevywxkk.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdobhybd.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2qolwsrkh.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2yrmsqkqi.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2ugstcuxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gt2gukoewai.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2okumsage.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2infqtvev.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2kkuerbaa.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyswnaxn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2gfaysawn.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2cvkijgbj.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2wtdjayfz.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2atcizqww.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2fsrrdvxe.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2wdwepvgc.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2qmcizlsp.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gt2bnwnvvgh.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2znynthbg.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2imcejged.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2htupgzgd.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pulkiukn.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2vyuczavy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2lqorpywn.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gt2zunlxfde.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeyozhpc.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2qtfdfivy.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zudbiing.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2tixdmtxv.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2kggbhilm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2rwakeyfi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fwaezmiu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2kkrujstd.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2kinlwqri.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2kzsvrapn.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2gbkhqfgv.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gt2zoiicuzu.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gt2ywcomfep.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afxarmiv.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2xwfohlnb.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2dwbktipf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gt2gwlgiesz.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2uvfauztr.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdemupmb.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gt2syqjwbnu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2batnoogl.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwepopzd.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2djazbhvc.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gt2hdvfptnk.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2nvwqfyva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gt2ixgktbzq.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gt2vjvlmwpw.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gt2ungqaprq.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2mnepgewk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2dsaxujbe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rphpwcgy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gt2oapcitaw.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2ltxpwfmy.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2qqqmyibd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2psnpisjr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2qfhxetaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2pgbwxtqn.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2ptwapkmb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2ocqlozmf.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2ajmvquzr.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2kwgjwasz.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2ahobktes.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymvhudic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2czekyudp.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2csmcffyk.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2wirzvbqw.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gt2nkraxnnc.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2cbeyibmf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2dsgxkzod.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2huoxeqlw.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2kmpjlomw.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2cfussqgu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2iqpwbwfa.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gt2exlokgsg.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qgshjozp.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2jfiocoei.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypvqempp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2xswkerhz.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2rsezqffp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmsdhoqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jmmpdbzi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2qymlifjf.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2synwmvoj.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2tsmlpfib.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yabzlbcl.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2xlvbiaze.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2exudwahl.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2liwwrmqi.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2gccbbwzt.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2cunwbvrj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gt2ugdoazaf.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gt2wmtcekbr.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2ydglwrkn.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gt2znepcjxg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2umisjpbe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2praiukbi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gt2cgmtecwo.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2hmkgpedz.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gt2wllgyxqv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gt2tbbympas.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rpitedhl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2iuwhdvgs.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gt2vlkhsolf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2lzojafnj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2rgpowluf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2dsynwysn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2bhlfpvoa.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2lochqekz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfsdldjx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2azggskju.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oppnmbci.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlpprklj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfvymsnk.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2dmyoenbs.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2llpwyftr.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2hdnkoswe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gt2xcuxgtib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2wqrpqfvp.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2cvevkiun.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2aryjxklu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2efxpveab.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2gavwyomz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2pbwtbkmz.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2duumwztu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2smpfdijz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2kmzvjzyk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2gkiukhou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2jiolqxmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2sagbnwsp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gt2wjwaxlkt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qugxchnz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2awgkuyxa.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2dylffrlm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gt2aonvjjan.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2hnctkmhp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjqajgux.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2vowuoxht.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2kcxrxthx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2uokdrwpn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gt2gtpnptnk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2vvtfpctb.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzsylmht.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2ihbyxodw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2brhrbbzo.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2tfvtcctx.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2rbqhpeas.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unndepxs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gt2diyxrzar.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2jrggzazs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2lvywzana.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2trzxjjkc.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvtgpjae.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2rmupzleu.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2rznoofbs.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2qajlwwpi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2otcqyicu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2thdcreuo.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2pazjlqnt.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2xcynivpb.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mopjikfh.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2gasueiha.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2hgptkscz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2saahymmu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2itapvhua.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxujnpos.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2qsjosmdp.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gt2rceockbh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2kpfzofvz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gt2yfoptkue.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2ggetxnlt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2otxizmvh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2xggonosm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2capuhhtt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gt2kljghjkx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2kddibgzr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2tptvomak.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2edpdkkri.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gt2ljgcxfkc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2ondabbrh.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2oftqdnqh.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2psxfdpkg.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2ismbjrky.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gt2uyxctwdl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gt2qbyzvoxu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2nfwjsgxf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2jjufoslu.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2achxqjyq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gt2nzihddlv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gt2wzvoerxp.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gt2rdkimrny.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gt2vmzlivke.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2mtllcffv.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2pqhnozjd.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2zmqkmxft.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gt2gprhvbop.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2ckcliezu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gt2qllelciq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2uwirwoer.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gt2imylzhhp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gt2wmmlsnki.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2ughemcna.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2rojmguht.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2szfoexoi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2ebnmhzkm.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gt2nqalqnge.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2itgrdwef.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2qbhxjbne.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2zuyatqli.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2uzukyyez.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2ddlooqfj.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gt2vohpbcmi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gt2kprslqbz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2yyonwqsu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2yxzvvyxx.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gt2dxfcviic.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kiczihsj.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvsodchb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2pxapuhia.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2jzcyeffv.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ywofozvy.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksfcfzmr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gt2tobsfrqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gt2itsnnbbn.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2vyklyugw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2viesqfck.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gt2ukmnxetu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2nxrskgnl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2npckmoku.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gt2gtilpukj.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gt2tzghqksi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sahjwxnb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2pmcxlsbz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2kwkqjhkp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2iiskspgk.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2nxpptjee.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gt2tyfpagtk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2hutvxqsv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2vuwfihap.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdtglaly.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vphnpdks.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gt2whrwebtk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gt2cuhdrakf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gt2lmirjjpg.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gt2kpkebesj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wibusgwl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2itjlbuso.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2nkdvzkpt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2dlvyjpyw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2nbzxweji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2tzeadacq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2rqppweup.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2lmlbfznq.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2tjaokfmx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2omejmano.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2kvtseyqs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvlijcjk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2vlkivzyf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2bxnyrwix.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2hnolrwnw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2ppgzszrs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2eqcgtxjk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vripmwqs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2kdggqpka.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gt2iwjwbmyi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2lnzuwmrh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2dhhbxcji.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2ubbevakm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2yswxlgpk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2enphdwmn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2rmmauacx.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gt2wsclbpad.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2sfweeifo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2ynyetzfh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2timqjybc.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gt2wffetugn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2ervlltxr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hecsgfft.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhgjtbok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gt2derlmbzs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gt2gibloqpl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gt2korzubnv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2skmlnhqs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2fgupgzic.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2lddxhpah.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2ujggvsfq.html


<!-- 参考信息 -->