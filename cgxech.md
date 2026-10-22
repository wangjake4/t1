代发 wailian999

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cnywukqh.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2zikdtclk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2hpuurjwq.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gt2famgmewg.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2crdelmps.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2iduibxjw.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ybehcsfw.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2auxyqhwz.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2xxbcnacq.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyliozcs.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gt2jmgvhunv.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2kainakmb.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2hjpbwynx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2eouuhwvp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ovtadyxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2dkefvlfy.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cxprdyrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2sdqdgqsv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2kcdpnhtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gt2zhtzlakz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gt2zaaubapl.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2vlexzzvt.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2dmnvfafe.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2oifswkba.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akjgwito.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2axszmenf.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2pwwicbkh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biyjllua.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2gbcqtdle.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2yydnwneu.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gt2zuevithh.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2usjvefxh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2yxtarmis.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2cpmyarho.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2awcsifxl.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rovfkyav.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2akqnlyxo.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2hijrtoxr.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2dvbprabr.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdhgbzpe.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gt2qwsfprbi.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2zkhjckrt.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2sdefxybv.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jrenxnze.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2mzjoxfic.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gt2nlpnnebd.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gt2eqkxjhps.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gt2hzacknly.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2vloynsph.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2ywbpgtoh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2rrofmkzt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfmmtccs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2azfquesn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2hoqrchvm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gt2ebeiaglv.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gt2wrkvtxge.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2szttiblk.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2rgypynds.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2xeflvoee.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwzosebz.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2hwlqlscf.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2coobtwyb.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2auxvtvyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2znvwzvum.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gt2njahhtzj.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2luqpufbn.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2owckfzxm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gt2gwbwhwgd.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2lkdnmdjx.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gt2nbnojher.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gt2awsxxpvp.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaqqgfks.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gt2rmlaheem.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gt2vhmsnazs.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2dsnxsdba.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2qdumzzsq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2xfwspfid.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gt2ihglfaaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2pzwixwvt.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2fsgrboaa.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqznsqag.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2bfrlovnm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ildlwpfh.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2uzxjjpvk.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gt2tebztdjk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gt2kdmvlkso.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2akigphyb.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2gejuhhqu.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2nswkuysk.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2jpdiacut.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2jcthdvmy.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2huaqzyfu.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2tfcuutsk.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gt2pzoevdjr.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gt2lcnaqhrm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2jwtgswop.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2htbqyrta.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2ubsbfksr.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2xpeozope.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2gkqjbhwa.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2tjbvncin.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gt2jlpnciii.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2xfvnlpvu.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2sjcwrpqq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bfseqtca.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qdftqnsm.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2zyezuazh.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ttdfrdkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2flssvkjd.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2uamdhfur.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2yrcrimwj.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2iboegfth.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2kqcxfbil.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2tqmetjbv.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2gokiebxs.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2zbxkzvzs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbupvpps.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gt2pghhxjvp.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2mhmahupg.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2qyiuatov.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2jzepqmip.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2dvdrnzut.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2pswxmkdy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmfchsmn.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2xhzextjy.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hkdpoksh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gt2hxomvsok.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2lximwnka.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gt2hawfhybf.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gt2coyqutlk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gt2zviiebeb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdbpfmhu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gt2afmedbda.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gt2tlalxcct.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vehdeggk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2apgepjvt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2srjrxvyw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2acmhoarc.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2pxnrefmq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2sftnoxpv.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2vhjjchls.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkkaajnd.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2prpsqfga.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2pbzrmgyd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2kknawfdu.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2ifjeqeaj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmnqbnpq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2udilzpkd.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2brrcqgmk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2kliunwxs.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2bkcgpcpv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqomurof.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gt2mjwgmayx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkzafizd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2xfhezvgb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2opzfitvo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2jejuvjzw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2wnmcajma.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2fwrfhfas.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2nyzhazpe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gt2fvsdjyfl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2pplesazi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wxvvrray.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2svgpogjq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2fbbauqbs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gt2lpptlesj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qatwgate.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2htvvfgya.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2osrbwuee.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2btzogdag.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2wnnhipkl.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2hvxronid.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2tjqmxuhq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2wuctpvxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2xdzxlidh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2bszvyzzb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2qdrmckpc.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2yczrkwhy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsuwfqcs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2pttzxtjm.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dycwwwqg.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2aavvzioc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2dzlxjmip.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2iddkfnqv.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gt2cnvywofq.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2zyjgufzk.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2qhcfabgd.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gt2zrypstyg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wibryanm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2owimxsnr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2gwjkthci.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cfbfhcxv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2zsuhuvrh.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gt2eudafhbw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2cwaqhesn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2gukkroez.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2pzexvpxt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2ukaotkda.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2aggirzfo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2ptqqtxed.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2pruneezi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2uzwqrrxn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eadxfstj.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2xtbpdffw.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gt2zrltzgdr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2voeyytjr.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2nyracewb.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2anfcayac.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2dclpexgp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2rxnwzpjd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gt2reknnkhh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gt2mhttsqvx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giunkyee.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2bhykiffr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2uaqqjcjn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2tttnszvv.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2xajzanjk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gt2xxrzxpnj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2vmlloczk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rerenhsk.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gt2fwdncvpx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gt2dumomcvd.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2qaszduxf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2hijpbhej.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2zdoaeekv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2qocovlex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2oybcfwvf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2bdiwmyjq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2mgugduxu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gt2ajqbevgn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gt2snecdtyo.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2uuncyqji.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2gkpponyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2lmzdlczz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2uwcueynl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2nlylsllu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2zjnrmeox.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2vzpjrdxq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2cpxmtpsh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2ylvenjkh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2tmfytbvb.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2wwsxinzs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2intuldvx.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2ctjmbdnm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxwcuyqt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hcncpwwi.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2mfyoiiyc.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mzxynxmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2ikykfkis.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2vbyjzdeu.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2lpvabviv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2nqmunpes.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2pkkeaumo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2nuvvtvxm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azbqhdhd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfkzkysm.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2piaihcrt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzpnemca.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2negdgaup.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2laoyakmn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2czuqaryj.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2gtessrvi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gt2yfvyagco.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2humgghjj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gt2muwgbqty.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gt2bbuqmrxd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gt2evmqddgd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gt2jpwiknmr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2ggmkuzja.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2tbtranem.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgoddvih.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2rdozgfnd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2tmbzqdag.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2rmcxbxww.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2htxgehuz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2fkszxlbx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2ncszrrwp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gt2bhzmkbjb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2slfzakoi.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gt2oegivvvy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2pmghhwwa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2pduznwaf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2cvvfcdew.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2jersbomz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2sgvlhldu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2bwgbizpp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eentwocv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2nethmqvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2wuwfrfpc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2yuhweakv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2jcjabnzd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2tiwnpqgn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2dwkotbxr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2xidhkidm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2qagtcviy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2plqsmahe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2htvgznck.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gt2vvxkgzpw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gt2vobhipkd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2whhqxbdw.html


<!-- 参考信息 -->