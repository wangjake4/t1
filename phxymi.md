代发 wailian999

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2izvvkxpm.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ngsfkwpn.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2svbtkxpq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dpiquyif.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2txiblohe.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gt2kjxjldmh.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2kayztaoe.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2osdjkwer.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2jvggjbfh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2guvbifpx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2zlgyzpdv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bmxzmmzp.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2otsnwiyi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkhmgbkp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2ktlyidvo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2dltfnlay.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2bjnbrfkk.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gt2ueydglrm.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2vscmwvhc.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2htqmqodd.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2vqesfoqx.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2uaefdfby.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2hevmpute.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldxbaacm.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jeuntgyh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2llqzubkt.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gt2hzpygnyv.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2qdrkpdlr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2dzbxtxiz.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryvmzszi.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2cuawuysy.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2yajbirhp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2rfrhiifw.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2bvmtoeho.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2xfzqbfxh.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gt2smonswet.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2vtwbjkws.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2scoziirm.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2smhyvlfq.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2jlweamwk.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2xjjcnfex.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gt2uqxmkkmb.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxprxbcf.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2qlwbtbgp.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2suouzlbc.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2ehfixssw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2tjloiwkt.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2drvkgsfu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2eiqcsfjw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wfikhrle.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2szhqczcv.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2ltnqstyu.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2ntuafiby.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2ykfayzvs.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2zayhxrav.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gt2zwluqduz.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2bansbupw.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2yfkcwkri.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2ggchdzmc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gt2jrzoqmsc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkqziux.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gt2eckgjqqm.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gt2vpvimuvh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gt2txjvaped.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2wkuxfhjq.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2rqacvwja.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2knwdejkz.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2kgbxprnm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uekiwjen.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2bjvdivoj.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruwdflbm.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2eztkijnr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2tjvllist.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2yzrbjqqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2omlgorcx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2bwwkcktz.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohyoflvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2fjnhmgjw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2ghctxmns.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2bumyahyq.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2gcrhhnst.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2gvopefyw.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iphdqruf.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2owsdejgk.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2eqidzuno.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2cpqwdpfy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2npfzpwgf.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2ppyhjefv.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2qzvwgnsv.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfksegtr.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gt2iybgoiip.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2lznoaxfu.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2cixvqohe.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2gkjvhrka.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2udchrzbr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2biscannn.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gt2bqkooahe.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2gyhotpdb.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2ettndssd.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2ycrxurig.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejnqqeub.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2wadnboab.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bjytnzcc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2sqaguznv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2fsknzgth.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2vippbirl.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2uzkfbefm.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gt2utwyudju.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2vlcwkljv.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2axmrddop.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2eoaoaieo.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2dlxukbmq.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2momgkwms.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2idytxurk.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2qcloohfv.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gt2hrftjczb.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2bxxulaje.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jntqiorg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2bhwswqlc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2yktuhpft.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gt2tvcezvcb.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2unwwxcyx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2sevbwfpn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2drfbppcf.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2czaczbkj.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gt2esljxpvh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gt2hvjyjica.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gt2gqufgisn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2eavsvhoq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2fjfwezlv.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kohbpemi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gt2lhfujkip.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksjcwnma.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2neiblyze.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gt2woacqdwo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqngtdoa.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gt2krhqfbro.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2vnioedno.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2zngadwjd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gt2ymseefsj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2pddqjolr.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycfwwbsd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2xkswlrio.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2hbcqawej.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwpmoiin.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fobehnkc.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2vryfehwu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2apsssovt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbumnlcq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haoftmvd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2mpmwsazm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2gxqvxvrz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gt2azcnciax.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2cdyfonra.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jswsttqc.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2gmbulgfd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gt2mmjhfkxl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2npcpvndl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2zwqabugp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2wlirrxig.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfloikd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2fijgkrao.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gt2mfgnacri.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2msnmexsh.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2nlwtlplr.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2yuyxgmwp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2zjkrajlk.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2ccdcjfmn.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2nrhxmrvq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2zozqycpl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2ligtxmub.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gt2yzypzxda.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2lxlmfuho.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wodkmfaa.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2ivkzykit.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2fxqiiayh.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2nenokhew.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rarodmui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2yfymtgeb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2kxtayvqt.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2mxgrkudg.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2mijwxksk.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2dtlacuix.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2acxpyfqq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2jnjmcnoo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vjovsnsv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzavdmkj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2byxypdsl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2xmbbxhgc.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2wpxayusc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2wgitrdfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gt2iayqfnjv.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2mtbfooxm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2gqansupx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptsiltjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2enirldoc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2oopzjhjx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2cpcyrcpg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2zciqgpre.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2qwihukko.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2dfesdynk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gt2iivupjgt.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2ftdaecag.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2bnklxvwh.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2uxezjvxj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gt2gschojxw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2qbmmlmmv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gt2qexqcswn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2adsyqrcs.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2iurrbpni.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2xtqxzywk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzpuoapj.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2bappqgcm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gt2crhrmdfv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2kazpwmfn.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2tdmrrfop.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gt2uyjbdooh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeolmbx.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2kjajtufs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gt2ailtnqri.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbtelvkl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2bkdjrlub.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2wsdrajpw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gt2wmyflybx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2hflivrhj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnebkuuv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gt2bykgmwpi.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvlkebdu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqdpxjnr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2dsmpxtnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2spcegvnx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2jkepibbm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2bxrfjgpb.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2gzmzaxxz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gt2kpfgzcnq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2wkjflwql.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2xmfrxaim.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2tvqsyxfb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2oyqnzhur.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2rwmtwigi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2hjtpcymv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2zovyilij.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2mlihjuwn.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdbdkbpf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2pezzdknm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2hiqiflvi.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2ppkjeszk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwmmuptv.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oflxsizw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2yroedgdm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2dtmjmkre.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gt2inrwrsiy.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2kwrjmuci.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gt2rhbyhjcp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2hwhdkajq.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2pukmqqzu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2lzhexvft.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2rzjykstf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2fbpzfkux.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2orywhegl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2hsxlhqhs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2fhirnopl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2nivxrhol.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gt2wmfpsjvu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2wumzqycm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gt2vcaqvjsx.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2vnobabss.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2dsugaman.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2ppxkfimo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2hsmojztu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2okyzdmix.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2xlnznytk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2yereynzw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqjpaglg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2evudzuyk.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gt2mjuqolgr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmafsqnt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kurblbfi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2rytfdnoz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2fjcusjjo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2voropviv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2jgrwgwmo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2kivgbvpc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gt2zwvgddvg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2ikccxhzl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2qqzpyoks.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gt2kdususha.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2behopmew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2ionegaao.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2emnzybac.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gt2xljqbnup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gt2onaxpdot.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2tafsqkcp.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2wjyrmevz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2ozhxnuop.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqwcqvdo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gt2exwtytpi.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gt2pfogxwwp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2lxgezvon.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gt2ysajywqq.html


<!-- 参考信息 -->