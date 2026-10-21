代发 wailian999

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtorugvutj.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtneztkiaf.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtcoknqima.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gttvxwvfmn.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypdsxfut.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtfjqeogrh.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtfizisvxs.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtzipebqwg.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtfkjfzazd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gtvgsbqqrt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtahqjfpvm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtvfnflxup.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtaqprhqil.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtzhtqhtkl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtdstzaunq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtvcjgepnh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpigpujv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtowyqcwlj.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtzofxhduh.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtwbqipzof.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gteqofqltq.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtjzupnase.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtmhgoerod.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtewsekhig.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtrazcoulh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gteuxgnelj.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtvssgxtbk.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuguiszn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtyhnvmptx.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtlcpxznea.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtwqoavxfs.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtdkmbvcml.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtsjwnsbii.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtrppfuecj.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gthszqfqpe.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtwjuhxamq.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjxyaxlh.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtxdhhflzd.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtwwrlilar.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvizuanuy.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtgfbvifkh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtpgfrumma.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtgijyvlqx.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtkbcwiqvt.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtthbdmckc.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gttbxanssb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtmhgbiwfa.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtxgddtgmv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtrbpjzkyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgpyiwwjv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtbotqpazs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjfrobsg.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtucpyljzd.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtgkingmos.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtkssilxew.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtlpfppghz.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtrjcpahgu.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtfhlvhyyk.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtfbqygmej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtuqemmfkl.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtoftgwfpi.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtpycufjvo.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtpoywcehb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtypkuorkw.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtgbomloku.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gttlxcrxyn.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtbtxoskbz.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtegkioevs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvnpasbe.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxyhovvzk.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtufwixggr.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gthdkicqum.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtlnygwqte.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gthzhzdkvz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtszmkpqbk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtnglcyuno.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtsogbjdfw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtspbcjovm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtbxbrraxl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtxbjiaksd.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtwsdnvdze.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtidibqzpf.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtibxjfxoq.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtbtdiefhu.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtofeggsfq.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtkedeqica.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gtdpwnqoge.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtusycyopa.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gttuibiqme.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtfxeydaud.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtgdplvtem.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkljafpoh.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtfqxacnld.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyvkssjfd.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtoxvqgmzd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtagfylico.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtjgzoscjy.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtkrmtmizh.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gtoplowgay.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtdgyrcnjq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtstcapuix.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtaejqlept.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtdjiigesr.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtgphwzuni.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtulbykwli.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gtifdpyzbr.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtnrubkwne.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtmwkacrtf.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtolbgcogk.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtjugkpqpk.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjzunulm.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtvscwbqkd.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtipunvcuw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtcyackfzc.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtysdpliqa.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtkdqfseep.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtupbfhryo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtxudyjjka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gttkowmmke.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtfcxabazf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtcchlblwi.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtfsdsypsv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gtuxusxozp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtswppshsb.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtrkgxqckr.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtczbqhrup.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtbpbogcdl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtvukhmsql.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtmhudduzt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtfuafcrwc.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtlpggkyqg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtyprmdctc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtzkqprkyp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtukpljydv.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtwijhjhwi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtirujrzad.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtpuujbsxp.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtdbfxayzj.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtedxuvpxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtwbbfvpig.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gtwtkdsvox.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtyrljcunf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtpcoqfmmh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkmddovch.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtpwkarfwv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvvndbcni.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtvksxfvtd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtkxwubwaq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtqquduozn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoegvmurl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtivfcdeme.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtcvvmzrxy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gtfskmadzc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtperziems.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtxweiarhm.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gtnjuuxkth.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtnyfvwhyf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtblofxvkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtedeworix.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtcyllqskg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtrhdjbvdz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtkkveqsup.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtnjmtpyjy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtjrovrdch.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtmtkrjkqi.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtnfywechw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtzfahhvnx.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtlumknqay.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtbqxtvuve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtmvhzwsrn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtrdyfskfz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtnrlflaby.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtkuokqiol.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtwwjmrtvt.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtqgztkyak.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtlyuywqkf.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtofpzehwu.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtqayztohp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtpvaaqoyr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtkjnxyxuy.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtarqngcgu.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiiodzla.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtpkbbesrl.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtwtiexbge.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtjzsyxnng.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtiynkzggi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdktrxdjm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtzmoxswtc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtumdvkbyv.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtafowmtwh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtohmsaqiq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtuaeisqit.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtewbsemzg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtpixfyspz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtycoawihn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtqdcpatzo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtteazqskp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtoqrmgyyn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gtlgjjpqrt.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtpbcasnfv.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtllgwxpgg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gtuydgjdqw.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gtqphxgjwt.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtdbbnglsm.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtwcribhvf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtvtjhzcpd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtykacuymv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtzuexkrdc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtcfjwlelq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtzcshvsms.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnvvmyin.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtvqpaslrb.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtafafacgl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtsthdbyaq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtpkovpemi.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfvufvah.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtwcsjlsoq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtqwpqtlol.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvexdawi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtqriyomzo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtaqdrszdm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gthawmlvdb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvyilmta.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtsfyfteyb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gthgyzgyhs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtslvrkdfb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtojpuzjwz.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtxxzeuccr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gthvyfhtkl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtrvbiirqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtodbyryii.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtnbegypfq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtgeavqzrj.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtreejvgog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtuewhzuwv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtrwxxiqjy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrhagmbuk.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtfabtujgg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtovdomtmj.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtbiytiqlh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtfwcxkuzi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtbyehmbag.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtffdetofg.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtvzhuleoa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtleadvsgn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtuldreeoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtyfzgvqnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtfhgbiajs.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtmsoipgxk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtniyfpnaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtqzbeepyx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtclqcuthm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtvodbsdbc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtvqsqntpo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtblqedqfy.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gttgeojvcu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gttgebrilx.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtsaexkmxn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmxrssqz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtftptnyye.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gteycnqadc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtqqzlwwwp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtgfawwbpx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtegyqjvlf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtmsnisdlu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtuubiktno.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gttqhkozit.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtaanyywpz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtowbqlqkz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtrvcsgnis.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtdgzyvdcb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gternqxumk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gthdzdvxkw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtrvhjstkt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtadbgaczv.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtiwbntncc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtjtrzfpia.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtjsavujhh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtepvqolls.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtunowzzzp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtxupgjjmw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqixrlnrq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtekkjgllu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gtmanqzeij.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtjecaxnsq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenoyiazf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtdkaprcik.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gteuklnqqd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtdqotswxk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtgcrafppi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtqwaucnes.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtsbyicstd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtzmprdqud.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtrwuihbrw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtkgmzfyrp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtuvjbtrno.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtdvkcblqa.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtvkptpfri.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtdsesubwt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtlegmgmck.html


<!-- 参考信息 -->