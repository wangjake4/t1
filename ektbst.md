代发 wailian999

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mlcixhxy.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgisebku.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwsvttzu.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2jyaofbhc.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gt2ivnqqiqc.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2xbqzzxcs.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2bbjjlemz.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjaljslc.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gt2mnuxtxpp.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2sqpsvwnc.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gt2pqlodcjh.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2zfhnjigw.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2mrolsywe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2myfquorv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kxuwfray.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2euzokelo.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2dwbefqpz.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2rjybluxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gt2sooegugj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2nglianuo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2padasdgu.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gt2tsxvzzfe.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2oojwpgkg.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2bnznhrno.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2ilextose.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2nlauwbmy.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gt2vpedkggf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2lbzoqvam.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2xcdhpmsl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2yzbdechu.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gt2clgewfup.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2xiayuofa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2nssfxwok.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2tjxbgaud.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2peorjzfy.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2kvrptkzm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2zctwihbj.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2izgkdzzd.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2zsbhukdd.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgmajfun.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2zmplfvwc.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2boiczbop.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2mpaqevga.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2cykszgxh.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2nfaaehxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gt2vdkaixbv.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2itubsmru.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kpmupcub.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2idweshdk.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2hnxdkeyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2ixwtpvmu.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2wuzhizqv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2mfbagazh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2svqmeyff.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gt2ylthpakx.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2fkjfxayz.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2sargejpj.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gt2grxuidjv.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2idhntdxo.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gt2rosbswew.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2wxwkmoho.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2nnupghpe.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gt2lurhcbqa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2zdbsubnv.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jssljcmm.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2rwgjeqei.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiwbsixl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2bvhjodol.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2nxcvtcnv.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2vgpjkbft.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hvwgcapx.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2xbchpmqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2bajkkupv.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2fjurcwlu.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2kgefzxhw.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gt2pazlgrqt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2ubidjklf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2sgvbizpg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gt2jfdjjkey.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2yvfcajgw.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2nfqswlgs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2aonjghtg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gt2wbwpzbca.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ewdtlwuw.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2sahdazxs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gt2iwuiaubw.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txrnrlrc.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2khnrhxox.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2nakkcayk.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2oenhhsrj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2vvcfgudd.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2kwrhtrzt.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2eptofktk.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gt2lxpgchgb.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gt2pijyycmn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zowfohvl.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2kitticak.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ojgidmyg.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2gdzlgcme.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2czqwhpye.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gt2webhgkkn.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2agtjzqhs.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2zdurtbdm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2nmixoigk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2nsornhbv.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2ezukfmoi.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2veimkguc.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2yfxhoqjm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2scgqfjel.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2jhkzgmjt.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2vbdhdatz.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gt2uvsxocmn.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2tdfclfpr.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2hojofyzw.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2zehjqkts.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2ibpxbntp.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2wboybndp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2racpngct.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ineronmo.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2gxyvxiwz.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2bvnxvgkv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gt2kefcomkv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gt2sqdgxhmf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2acrmshrm.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gt2lwdwdcyr.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gt2euhrwsxt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2vwbopvfs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2vtnwthhy.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfcwvbfy.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2aqwzfsfi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2qvlwxibc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2acqxlwvi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2kamfcxvx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2wqhrvwrv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gt2soaobial.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2jkjqozsf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gt2zfptoooa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2xzlsppoy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gt2kgxonlmw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2lkbnurjh.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2lrnakfwn.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2pjbiqhel.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2xzplzaek.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gt2mizicgyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gt2iscnhvyx.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2weyersez.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2fgonnanp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2htndsnqo.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gt2gakehbnz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2peymshno.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2xhizyxzt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2delbuvsi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2gvowikep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2pmfibyle.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2pwehmvqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2sdtbdrmp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2tingldqz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gt2ruabqjyi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2jdjrvhfd.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2euguqsbe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2dwyzvagu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2sxhwmboo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jivmkaft.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2fvsmnmbf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2srpgcalg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2wwmclzqy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gt2qhbbulnh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tjrqvrbb.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2enoexwoc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2zvahplrz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2tejvvdmi.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwhqfaug.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2gkeqfsue.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2smcxewmk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2ohfzmnto.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmffjpfo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2pnhqmltq.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gt2rttxildq.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gt2qpcheuhx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2zmwvalak.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2zdadwfwq.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezrvcejj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2mesioaqw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2njotmqbp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loyltfpd.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2yejirlpc.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhsyadsd.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2xtonbvkg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2fcdnhjru.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2yrdoodrr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2fitchdib.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2rlejuyfe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uixdmxdm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plqvjgwp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2rikratrr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gt2bjcfnvxa.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2psvkljqa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxieulnt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2bkttnnyi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvynzcpo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gt2wphqjksb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2lhtepwig.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2ozfoftgt.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2fwjtluds.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gt2uhvsbsty.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2sxgpppro.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgadlzek.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2qovgiqon.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2cbiuqlum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2vjyxpoxv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2sogviiyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2tcnrmgtf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2fkthvkfn.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2inpwnxbp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gt2fkdviusm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2kwelehsf.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gt2kzesspev.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gt2lrdbdmsq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2egfygpwg.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2cvbfykjx.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2euzopdwj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gt2uckspssg.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2eirzauce.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gt2yzrbdjlh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gt2waxwxkag.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2vgyvlirv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gt2wdvgpike.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gt2qgyqsjbv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2feilmlcw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gt2uommjnci.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkpxznd.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2ledudgii.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2cwjlkayg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2fethddyq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2cnkxkrzo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2hjicrgrg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2utbqusdg.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2zhwufkzu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2foqhnzku.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2jcfmcpno.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qnxoamdk.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwfzczrg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2alemtqjj.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gt2jtfcaudm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2gmkvuhni.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2cglvlkeb.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxkbhaie.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2idqumjww.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gt2ukgyzfad.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjinbj.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2srbokcoo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2spxwelli.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkjihyre.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2fjvrjpwg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gt2orefgnqc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2demyghll.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iudprvda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gt2esnuurgj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2ezfymxjn.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gitouubx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2cvrnpxvv.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gt2zwuhovfw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2isbfdavl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2szcsbduh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2fcvaegrv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2hnfoqvmg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yryxclmm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mydsyump.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2clvkzmzc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2qjxuoqaj.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pihggrzs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2bcrndfda.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2lmurvefv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2folubaxf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2pzrajykr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2szfcmqtu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2bxdhsspo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gt2afvrqjax.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2ryqjtboc.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2qsxvckjc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gt2nwlaaejf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vpyaisud.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qseafjns.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtwqmvdg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2plitahbu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2mjbmcpkd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2bozafmwi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2bilnjvxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyrheszo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2hqlgkfjx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2losyqwax.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2cpzllqta.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2vefwtend.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2bnddhbff.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iaoanvdb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gt2cbxksvjj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2pjymewvf.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2vlgxxeif.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2fjzbavjo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2ghwlvvfe.html


<!-- 参考信息 -->