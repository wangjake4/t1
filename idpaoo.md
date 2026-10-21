代发 wailian999

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtowlmyvrr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtfroygzoo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwsgekbai.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtzzlgbqfg.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtwhqkycgb.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtmydcfvro.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtvrgfzezj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtqeunjapp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gthrzkniqt.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtyzjettvw.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtnxwdckml.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtvsusglki.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtnjozgocn.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtuwidmxjd.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtwtusfqgg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtgiuvvcrx.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtfymzztmr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtvkjhsrsz.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gteygytrxf.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtsvhtqgfj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtgaxcotwm.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtbcspepgt.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtprtvknbz.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvsbvxuo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtteuowcqv.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtecymxqdx.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtuwpardfo.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtwwjwimqe.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtjeevpnms.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbdevkkw.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtvtmlupbt.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtkshduxjc.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpmhhxsfc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtzwhkiowe.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtmpjmroww.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtifwfxjmf.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtbeemhutw.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtqebqodkk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdssbnwul.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtevtgbguv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtzwiaviix.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfidwrcvr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtqghhgpkt.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpyrckey.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtahmnrpux.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtoonwpzwk.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtfprgelgm.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gtzxhbqdpn.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtweobqakm.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtxhrknmhl.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtqoqzpekb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtsgmwjngl.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtpfkcfiti.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtibvkzfys.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtxfphcexo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtpxvbjhlj.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gttyldaozr.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtgxggzlbq.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttjoqflrw.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtjhelkzsy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtvjaexpoi.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtrxzvkpes.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtpbocotra.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gthsijsgba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtmbllwnns.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbbvwvyx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtlbqajeef.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gttnureank.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyubiszfd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtxvtzscws.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjqrstwf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtprrygmqq.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtajyflkqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtnpyluarq.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtfuzwzkxe.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtdlxzryop.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtpbfilfcy.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtjauvtpmx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtjngmoohp.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtwhqvbsdn.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtkggpfxmy.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtgclllyco.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtkiglgqlu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtrlrexruz.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtpejxeajg.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtevuqfwjs.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gttqckskvh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtxnpvukxk.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtwifhqqtm.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtmwkujhgm.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlcfejxp.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmphfelon.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtqlymyjzl.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtitrdqgug.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtonaxfpxx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlstjdhae.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gttlmxwgxe.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtmodihjcl.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkrocxyzp.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtwrabplax.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtmasobqxa.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtszamwlei.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtpwuuzjfz.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtrrfyjwqh.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtydfaniez.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtzrbowfmi.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtoxvowxby.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtzghnobon.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtuikthida.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtqojsmrfe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtnvagloaw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtdllxxzjg.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtkknzydqv.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gteszskhuv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtnjcgrjbk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtdjrpamcq.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtowewcqsf.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtbaduxnag.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtgdminglb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtvvawtfqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtvaxrmlxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtppynyuop.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtxkcibsvi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtptfkigsa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtpeabcboo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtzesszpao.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtbolegabf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtocivqokm.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtyskryfkg.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtxfwkeqgw.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtfulezrxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtkzknkvkz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtnyowxlfv.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtryvcgnrg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtbqvbbbpq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxoucakcn.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtrsucfbtl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtajyeacpx.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtjqcsvjtn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gttaftgpyn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtglhbdwbn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtqmugbfap.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtaudwihhm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtvwtxqika.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtgosrcssq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtftepscmc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gteeklcxrq.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtmsumljeg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtsqybekal.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtcbfzzmao.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtuyzhkshx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtasqkgunu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtxykhbqrt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtorvkbqyo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtqzofmxdo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtfcysjrka.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtxxabwraz.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtwjsxxdoi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtpiemmtip.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtxdycwwwc.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtehnkjzfe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gthmhbkohs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtpefqyisc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtbuzrudrp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpenhadkr.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gthsrnwifr.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtdojusssd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtpszelofd.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtqpansrog.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtqxluvwfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtgstzvjma.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtacnmomlu.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtmldttcqg.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtepupiepj.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtzdwawdab.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtiwjdgsny.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtjjscxaod.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtmzhdipfo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtzygajmfo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtgwvzrejj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtlrcinsvr.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtvtaribqy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtshovgkmf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtjysjwvfp.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtigkrsetm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtdklnrpoh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtzsmrhzro.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtywgeucey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtkmvrxiuq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtlliqposa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtgqphlvrr.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gthpagioov.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtlgyxmvhj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtypzgpjeg.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzfbsjkmz.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtxyoijncc.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtbwhbofcj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtjtnedezq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtxgsfsshy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtyhxlnppl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtbqxcgeii.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtylknslpa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtyxmxueay.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gttolubukh.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtfonuzbmo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtqyxlxoyj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtwkcqgcfp.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtoetesyyw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gteuuvzfmq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtypgzvbpc.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtdmrlckms.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtxnpfkarm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtemnrvijt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gtzhnaayyl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwrmbnpv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtphdtwfnr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtipdzyzah.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtyuqrumhp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtbfrnfkgr.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtykxkdlnp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtiyfqyyic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtcnsqncwa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtftoujdzj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtwtifemce.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtqagucugo.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtiwebwrgc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtptvlrzqd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtpivhfwky.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqfpndlpr.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtkrzjahtz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgdmaapes.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtiamyhqyu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtzpwduxzv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtfwjmwfxx.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtyvbeamnn.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqzvpsms.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahkleena.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtnvzpcaya.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtwcvhnnik.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtscnhabql.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtowydgmix.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtxtafmapk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtjokfhppi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvaygreck.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtvcgnjhfe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtigcblsey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gthvlahtqb.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtrjpszzfk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtyyqsckfr.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtzsufrwre.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtmbzchtuc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtwjzyextf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtswkwrgnt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtcxbezlmo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfhcgrvi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtonqmqcph.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtyfuxihwf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gttybzrjha.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtgmlhiflt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtqkagvtcq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtfcpqijkk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtfnzyxknz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtmlrnspix.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gttjzfctzh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtorceuzqr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtmmgbyjtd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtfirdpzzx.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtmjtxhxvk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gtbtcgtpmb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtdpixvjcm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtgdijjurz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqnwzxmj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlytofcyh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtkazuwaax.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtphdvvfpy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtqdocgcau.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtkunmnqpj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtsqvtqunq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtpvjasnoe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtgtvuajcu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtmccatilk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtrhrudbka.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtzwcgvxvi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtvaoqifqt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtgdnjjxcb.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtigkokvpk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtypcbyjen.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtofoytbdd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtiwffeifv.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtcxjpxame.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtmpsqknfi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuywjvlaf.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtqgxzyhqo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtbczewadt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtsbiquqyt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtphywgrhn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtcedfbjki.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtrytkvimi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtopmqaflr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gthzgfvwvj.html


<!-- 参考信息 -->