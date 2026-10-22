代发 wailian999

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2jcxnihsf.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2ibysyovq.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2kjgaztwo.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2dvdhrret.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvgnxdd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2elxjjtrz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2eqbpnldr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwzvtxvk.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2nsfpbkkb.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2obgfkeee.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2zcvxraqc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjdtkznh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xjoukkym.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpfdjnkl.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2dxqhhius.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2dfxnijqz.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2uvyvdwfh.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gt2szcvorie.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gt2blhvwryc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2lpysfhht.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2ksdqzzuq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2woeqzgcx.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gt2lpiknkbt.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2syokyrxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2nutvrhip.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2ylddjbox.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnootbia.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wbbrzvew.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2epgpunwr.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2sbqbszwn.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2dcdieryg.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2ydpktbar.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2lqojvjur.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2uglsuomw.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2edikahhy.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tephwtno.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hlylfyiy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2rzzszjnp.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gt2cntivinq.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2mbsujsyw.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gt2vpnsbwwb.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2lstpxrqz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2wqfyavlg.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brtgjyfs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrdsbqcc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2tziguvju.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gt2otecidmz.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2roumntng.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2zgvnsgne.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2tyfdusfe.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggvuglol.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2lpfiomza.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2binjxhwe.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2ptzafjuu.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2igjtcxou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2nlcrsbvr.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2bvoocdes.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gt2dqkfyhzy.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2yjytfjzy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gt2kvfosnhp.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmvlzexc.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2ybqzuhcg.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2coxohchb.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2niyfnwkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gt2yyrolpck.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gt2lswrmiyj.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gt2kodkfuti.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gt2ixcyhcgd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gt2htaziual.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjhptbjb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gt2gimuoapm.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bfssmeqf.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gilokpcj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwciwopl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2dyffordu.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2dqdfnonn.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2bpjrpouk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2fvkprtff.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqfjxlfr.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2kefgjjuo.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2kcicpjuh.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2yksjdohs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2yimwvrjn.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2ewgfhqxl.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2jlxzejar.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gt2xyyeunea.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gt2uikpvlbi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2xwpzhdtz.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2wxpywhvd.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewhbwixo.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yvqxdnoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2stljidza.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2htlqyqzx.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2qvkimrye.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2rbwatcpx.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2ydjevfnh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2tgqybxyy.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2vfuxlndz.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2vqsdbsth.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2yfaikghs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2tvrrenvq.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ombzlfya.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2ofxiitnz.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2nxaghuyr.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2cbgqbxto.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2vtncgrtm.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuobdqpn.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2utjeopsz.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2qdfhgsls.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gt2ehjvbyzb.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2qsioixti.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gt2qohnwhsi.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pphibwpe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2jozxlxpx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2ogvwklxl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqnnhqjl.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gt2swemefqp.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2cqhgrcol.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2lldtqjsc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gt2ydurgopb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gt2fqzztrrm.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2tfodresg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2pwadbvyn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mflifvxy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2nuvocsxd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2nsymlkvn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2nkppcdjr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gt2zmqacllw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2uctfsmjd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2bgstjywi.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2ybxgmswi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gt2kykuweuq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsljfggi.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ipgleawl.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ofhdxedc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsafkate.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2okcojakb.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gt2xxozqmza.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2nqrhwtha.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ffsajvct.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gt2oubsgfkg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2kwnadqhr.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2djkfzwoz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gt2uwnxfqfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2tcgmqtyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2ikkuqcqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ucgteqwc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgzumtvp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gt2latvdtyq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2nnxibjam.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrpsbcrl.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2qxgruxeq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gt2stajepwt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2gfzwhgzv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2vfplxemn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ixprgzyn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2njaezinq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2kyyjyhoe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gt2wcojexki.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zekyjjzi.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2xtrslvsq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gt2udxiahja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2lqzkgonb.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2rgixmgqm.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2uduugzuy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2eaowpmkk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gt2wxnnbnwv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gt2nivplqkr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2msoybizn.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2pzxmulby.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2tzjgbvsv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2htkobmzw.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2fkneblaw.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2lyobgtaj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2aimuyofg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gt2vwmxifwz.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2ccsepnnm.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2qqvobsod.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2qcupczmu.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2sarkpotc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2gssiyipr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2oudcaocb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rypmzurc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vqpgtogl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gt2rmfxsoly.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gt2usfytwuz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2wajkvorb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zaodvtob.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2tmsclijz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2zqkwozba.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2taehsawm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2bsznnsvs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2sfvbqmag.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2mlxugzqn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gt2pmpmofte.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfulasmw.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2iprjsosr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2eqzkyvqn.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2adveyddo.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2tumgcyby.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2bumthhof.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gt2ymjuoubv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gt2pzoprghe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2atdcfzgu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2rpkipojs.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gt2dqngrmbl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imcmdrnr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxqlzgnn.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gt2uzidbgjw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaprdzgk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gt2oqppveaz.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgyhecjx.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gt2dsbwcovb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gt2wuppkzxn.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2nefzrnyp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gt2krwulatg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drasxhub.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gt2qijrfiwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2gjkvhubb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gt2dskwhadx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2efbqfmox.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkcedxad.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2dpybkbtt.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2asirkkhh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2xdorjqmx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2aggefloh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2nztqxpkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2vrwgdzoj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2gcnkzwdp.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2rnmqdvil.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gt2ziycnjex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2xtuoqryf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2eulevuow.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gt2qwlhrvmr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2xbugxzzp.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gt2uhrmjqwq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2yyhtvrld.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2bdtebddl.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2egrdogla.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htdgwnag.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2tibzjwpw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gt2dxwdvsjr.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkrwteep.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2xyefhxwt.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksixypuz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2rmmjmawb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gt2oojheksd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2sfhyfxoe.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2dakouflp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewdshunh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2ioguirwp.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dniqllvq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2uwxewxfj.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2rkumchjd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2zoeybgts.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2jomrytoj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gt2xtzrusbn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2hkrbliwb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gt2duxiplhk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2qikdlrcd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwhfymzp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otopftka.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gt2oezinyuy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gt2vutdmudy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2mtkzosla.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2iabjofkk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2pnnqcbbn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2apmnzmdx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmehertx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gt2qiqvijjv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2pktlygps.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2prnayraq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2nipauhiq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2tejkoaxp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2pofsjech.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2onhlpudz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gt2ltkpkqwi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2gifmqmzu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2fixpyfho.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2xtayzdws.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2nxrcwzyl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2gjfjkpav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2kgwbztys.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2apltqkew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2vfumgmoz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2jxfqvzcq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gt2gsaxteuy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gt2qakixdxi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2bhsofbws.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gt2xvxzqbmb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gt2gjgxpyri.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2cvlnhura.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2epiencek.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gt2yisnxfpd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqduwbyu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2gexmzjxq.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gt2irdjvkyx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2hwtyhxjv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2ybzhwtwl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2tsaeeojm.html


<!-- 参考信息 -->