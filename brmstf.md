代发 wailian999

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gt2sbjopkfk.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2iklzuqox.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2ljtigiap.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gt2giezkowl.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtpssnqt.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2liycgnxw.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2apgtfhoe.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2zdozkisg.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2exeohxds.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2dguiisct.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ovytlnvl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2wzhfqolg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkoemabl.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2wpdgxeqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2uqhibwkd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2kztwxtcf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2hoyderiu.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2jzihsezi.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2wstbapxf.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2lowyhljt.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2vcbhmbsn.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2otyqyhnn.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2cueoxfkp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gt2rfvlyemm.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gt2akemmjks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnnxwlgt.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gt2heztsocb.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2gnzxzuim.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2fngglbqc.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2qsiufokx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qajpbdjm.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2bkbnenac.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2sqalfcyy.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2sqflitlu.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gt2wsqbjrgr.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrhujtia.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gt2imbfkcon.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2xhuzyeam.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2dyfknvpx.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mbybuhgo.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2mgaslwtc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gt2ovggyzrf.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2xcfwiasa.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gt2sgornxnp.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvjdoloq.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2sodnxhrb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2tqgdhdai.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zwgfalfm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ictblgga.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2dharfqap.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2kocjzaof.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2idzpybrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2tqqzvmxs.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdencefq.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loqgzelh.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2vvfswtjk.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2uezovedg.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2inajrbyk.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2ulxuhade.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2fuzchvkp.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gt2fvpherzv.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2rphjlesp.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2qjdizpny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2fdrxcfeh.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsuskamp.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2egbhkcql.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gt2binlpgvo.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2bnzevjih.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2tfwhbipb.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2znlxwvjy.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2dorcijbs.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2hoggfvst.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2uxvukvdw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gt2ekmkwdew.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2gsbdfeka.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2pkthkxpw.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gt2przrxdnn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gt2vlecyelk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2addflqyf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2oapbuqss.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2tjttdptj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2slwczdiu.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2oswaubye.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2sfzaypjo.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2qzkxevds.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gt2cndyaiwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2zcudzrmo.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2fmmqcmid.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gt2kuuucpgq.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwdkryvd.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gt2vzmkwhaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2uoxlrsyy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsbhqpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2dnxcnzzg.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2gagpuaeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2sbfiljhe.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2lpjgbuht.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptwpxupd.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2uzahwvuf.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2vkwtpkir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2uvgtcasu.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2uwuqhhup.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2quthwdvm.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zdtauyvo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2exqcngew.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2auaeeini.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2nacuycxz.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2qaqmerec.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2sunisfhg.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2dbdqykvt.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvhxopom.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2kaybbvgz.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2vadqbfjq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2klsnhzou.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2uvfzpvta.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2mqcvcbpc.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2yhdbavdu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2lqpeixsr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2wuqizylp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2nokmcrxa.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2dwiiijdv.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ldbnxmsf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gt2fbmlrtbl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2zesuncjn.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2imeybmgy.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2swpqfufo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gt2zxuwaocq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ndyrneji.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2wtmbjyse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2shxzmyuj.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsrqnxml.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2cdhrtrjs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2ifbaljnt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ffcknkes.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gt2rulekctw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2ytyvprdf.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gt2elbvnobr.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2xovzxena.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2wrrwihkv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gt2xdlysaek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gt2eqoajquu.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjoqitaf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2arimyffa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hydtefjo.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2teyonkaa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2kodsparp.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpcfilcr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2cfstrqkt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mfxdcmiy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiewkml.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2iqgkvmor.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2dddqnczn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2ocelmscw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2vtxakdys.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omdsozsf.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfqgmrpm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ieyarjbk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2qqsmzidg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2gacidhxo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2kkndtfiv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2ytdthxjf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2ezpqpyme.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2tcfppqac.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2uivwmkcw.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2fnjnaxod.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gt2cyggpnub.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2ciozndnt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2hyvepmwo.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2bsaarhlp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2kfzydzky.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2vjsirelh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2gndpyhbc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2tiuucmzz.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2xiebpfmp.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gt2ivqqtfgp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzlowuvt.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjgymcdf.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhahuera.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2iktgdkbm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2giojjrjl.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2zzwfrmcr.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmvqzyyo.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2poacuguc.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2obfieqlu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2zmdzyumd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2aqcckwjh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2hvxipucj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2itoylbje.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gt2cyjmhfcj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2wfcscnqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gt2vfigyucs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gt2bcktynly.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gt2dqhignps.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2wzvsqrrs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2ukregazv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2fxhtwsfm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gt2cxiirfce.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2wlkvmztd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gt2ejxxbuhw.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2hqcbhyyt.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2bsvrvcbc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gt2ojyfptfx.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmkxqnkv.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2iqvfidxt.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2qelbgjqw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2mnlremkj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gt2eabrxqpp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gt2cefdjotp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2vrgifftp.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gt2clkexadf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gt2bpidksaa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gt2oahugbjx.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trecwdqk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gt2rapiespm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2rdmcjdbf.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gt2aazkedaq.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2bpiuqjjv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asqnpakh.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2gtlkfgxn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlpnrnjh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2hkbditvh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2qiiwnuxl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2zmbxqjwx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uadsqdrh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2yhneqhzz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gt2iawcemva.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gt2pvizedvf.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gt2yomtdxfn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2pxkiblic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2gcuohcug.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2lkmgaqpm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2pzhiidtg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gt2qulekzxn.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2rtalmcml.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gt2lzkrsvzw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2tsnoufxn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2cqbjrxqx.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2ylezbrso.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xuclupqw.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2avgmoiak.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2kwuduxog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2xpdwtwxr.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2iunpfuff.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2cnkxpcnk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gt2undsjrma.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2auqslnad.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2ytboyvcl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2trrdmnic.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2efbkpxmc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2tchgyuok.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gt2snhjhjqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xprelxlu.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2mtyzhmyv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2owqtyjzs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2epfkokor.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2enwbkkew.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2dqsuabbc.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2gncvtoqb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2zrbkzimi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeudvthz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2dydmbzqs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gt2dpwtdglk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhkqrhii.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2ylnkemob.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrwwwrar.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2vhjsazoz.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2dmycdzrw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxoqtsdo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gt2eyrczaxh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2gdawdxtd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2towusuhc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2xligmizg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adeceynu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2efwklvvo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2xhgesrmn.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2sdmhjxnl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2rrjkbisl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2uvvelenl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2hrhkhgab.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2xgystrfu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fiiyyzme.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2syptqgmk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2nssqdhbj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gt2ziensrqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gt2xwowudej.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huvsniwk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gt2ylxzmjaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2igwryamf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2bftkrveb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2kkgsnqqz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2xjjkvmys.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gt2fnuqvlyx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2wgjxheyo.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gt2hisrgopq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gt2wlbercut.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2fdzarlhp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2qbxwcrtn.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2xmwmxxbh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2fdrabnnv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2mvgiydlw.html


<!-- 参考信息 -->