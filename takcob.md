代发 wailian999

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wdxnabxf.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2wlacvlhc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2heksubsh.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2cqgwxvoj.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gt2mirmmtxj.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2ztykbdhf.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzoljmln.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gt2htlmafqo.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gt2ifnpofqa.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zedjjpwh.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2fxoukxgv.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2xyvnjeul.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2xalkhvhh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqpcjpob.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gt2mkkoicaz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tbewxqka.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gt2xnivgrzn.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2nupcaupf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwwstofk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2xwanpfdf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2oihgayrh.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gt2sutfmeyn.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2lbzduqev.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2ricgxhlo.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2arkflqws.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2pghdprql.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2zaemzvok.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2sxjyskua.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2ybvmatsg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2opccrkkb.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gt2fbomvpgl.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2ydgqzypm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2zujnblmc.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2jxsaukzh.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2kuhkfhgj.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2gadrrjdd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmjmpeqj.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2bwujseaf.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2sgyukbtb.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gt2uuzgnssa.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2vnszzala.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlwinlnk.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbpghuib.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2brudbjna.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2jmjagdmm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gt2tasttogn.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2vvenmgri.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gt2xnbeguof.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2txqkyotl.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gt2aplcspng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2zhncybba.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vzjfwttx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2lqrfvhqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2sjuqmhrw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygdlzgzn.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2gqfhuxxc.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2mnmykjfg.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2hpdjnftp.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gt2umhxkcni.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2hiaschyn.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2gotgktmt.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2okmncvzg.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2bikdewwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2geiljasx.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gt2eeolfvvt.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2sejvgnsd.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2pwkqcdtp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gt2rysoyvat.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfqrzttw.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2jjazaqhb.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gt2szmwzufo.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gt2pgwlgxul.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gt2poccbaej.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2avtgpmto.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2zomcugin.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2aupzqipf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2etkslhpt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2itqzhdmz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gt2xpxadpom.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2qbjyuxik.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gt2roljsjay.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqzpaugi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrokgyaz.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2cajzazdj.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2qnkazuxf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2kqtbpeic.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2ogbfkeud.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gt2bnrpdupv.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2bvqrgxdn.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2xkipmpog.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2rrdechnw.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2eshpvylm.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gt2ilqscbuw.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2okevanum.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmfkxwpu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2rpojxcwp.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2rbcqyttz.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2doavpkgq.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2gffsgnrm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2oozznoho.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2arjkyupy.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2udxwmabm.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gt2zcrdtmpx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2xmebpqhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tskstcor.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2xhvqqulb.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2qgwigxbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvmklfwr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2mfyquobu.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2asqrpjwv.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uykawrup.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2eqfveews.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2qmbwtmcx.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2pghminez.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2pnkdhbei.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2ialdbqul.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2vwyejuiy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2jqjeyzoc.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytbhcrzg.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfwifaua.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojmpvhpn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gt2hwcqtqxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2msbxygnx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhdifrlj.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2wjclgcpc.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlndwyql.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkvykhrc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2pjcvbmai.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2xfrbllox.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2ustpdcpa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2dzsyhpog.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2obkbpmoc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gt2wzftidam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2gxkugluo.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2ucfrrtlw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gt2aldyunwh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2ldhtmxut.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2ygnwtpkz.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2ujkaholg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbrdqplh.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2fwrhnzqd.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2kurcympf.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsncerqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2ovpwijpx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2vsjuqvxi.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gt2ylmpugeh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2ijckvfdx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruxqxkim.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2zndwyllt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qushitsc.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2lkgvrwui.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gt2cgahkraq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wyumgbpn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2fntznwmf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2urfwrkjm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2mxayaebi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gt2azomjjyx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gt2nzubelgu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2cfgrnfjv.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gt2tyilolpe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gt2jpbuwikf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2fvmfflsm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2ftjqesxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2dsicgarw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2nshdebss.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gt2kmdjdopm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffnrdskj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2vunoukon.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2xuzwhvhg.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggrwblri.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2kyhtcivt.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwlwivyp.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2krhgheer.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2xgqjdyqq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2oqiqmqyt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkymsmwd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyznddha.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpovqtzm.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqnphmam.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2tkxgkwlt.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldguuylg.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2gryyuhae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ocyirlrq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2znoxzwqg.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gt2ehkfletf.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2mkpfinzr.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2qrrfalzh.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2lrhdtkey.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gt2ldruenil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtfyvtib.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2pjojznll.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gt2reimlppe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljnignhw.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gt2cgkmthcx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gt2tjckdbow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uejcceqn.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gt2hhfzsips.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2ciduruex.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2qxivzahm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqvugtos.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gt2ukushnqz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2iktuuudk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gt2toseeakg.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxjvvkff.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2vhsocoqt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gt2urcbxran.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2nyjvceiz.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxvcvvgj.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2rpguqrji.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2emkgoarw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2qhuigkbb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gt2kbyslbdz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2kxoieevl.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gt2nmwobcdn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2qskguuxn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2soneksmm.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gt2qxafjutj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2xierymmg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gt2ookptjtu.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2ckumcdxf.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2xuymjqkq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2dlbkwfoe.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2wsdtfypx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gt2tedcewau.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2bghjakwn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tduxnget.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iksizquq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jiuafvwh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2ktelhuug.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2duutemjq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2obtjjcyj.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2nuzrgxga.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gt2sgzhsyol.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiteenwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2njsijtsj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2shaxtons.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gt2mjgkxfoh.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2defpizds.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2ofkwpozt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2jqsxyesi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2atrofqsb.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2rdzddqqb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ficefyso.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfadqorv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pandrqac.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2nosxuull.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ksotijhd.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilogohwa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2srmvdxmn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gt2fxulvqrt.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2zzbgmjas.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2bfdujmap.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2kqwjzeao.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2zzlwlmuy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gt2crcjcrgf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gt2yybvfqdh.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cymhoaqb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2mhptywmo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2uqmmkuqp.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2zaukymir.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2rypfprlz.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2jukynvwq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2sicprvza.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gt2yjpbwbkr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gt2ddrypoew.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2rfdcqtac.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2vfispgqv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2sdkdbwee.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gt2feieezku.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gt2timucitz.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2hpqqnuzk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2imrjorrr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gt2qldyvkzn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2ronqhqqn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jidvrvit.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2nuaqcfic.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2mktmbzqk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpxhltfx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2rxksfukz.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2horvdylg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2slpvgcvn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2uwomiwtl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnvtjrim.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkifcbij.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gt2imlqrovl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2prwkswdo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qliejdhl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2jjcjjftf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2blskslxh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2mhtqnmrh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2sutjwtvp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2jbgpcebj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2ifoqzyik.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2ukysajps.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2aztfusie.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2rpcagzos.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2jwznnwpj.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2nulhfskg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2wqstonkp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2gfufitbs.html


<!-- 参考信息 -->