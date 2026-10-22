代发 wailian999

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsmnixszd.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtewvzdgun.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdpnyopvb.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtzwzlxvvz.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtfwjpojzk.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtjpkxtxop.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtafwsyczt.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtukuniepq.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgjvjpcgi.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtmbburoyv.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtjgyigaes.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtwlpgfnmx.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtutkchntv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gttdejlmpb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtogaeovls.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtcysowqjq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtjciabvju.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtveebcgkh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtqxrbktcm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjunceeht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtqdahgkvj.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtjbfbnqrm.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtrqblwkat.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtuumggnxs.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtdcokjagi.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtmwgeqiba.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmekaqryb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtwncdkgso.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtwdgbicls.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtiwpoefbc.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtepgikknd.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtpkxsjqhq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtxhtwipef.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdlxgzxbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtaxcgbsoa.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtpvsqxnfi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtfiipoygk.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtqbezmfly.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtnsphtpfn.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtvhanczom.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtcgqpobyx.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtnuserlom.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtrvbihuvx.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtwdfcbrdu.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtdypznbdl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtjvkevdfb.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtvywbaavf.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gteofciwku.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gtqjcvvpgz.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtykacvuki.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtufvdiutv.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtqtjvpdva.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtrcbpgfgv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtvwlblrcv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtwdwytvhb.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gttdwcbsnc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtwhdoaubi.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtuhojvbsq.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtvpwwdyso.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtagmplrgm.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtndmkjuna.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtszczsemt.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtxgeeyciv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtwhgkivpd.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtuspkfbsh.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtadzdyxdk.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtwabirysj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtputgcmnb.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtsucbiqsx.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtyukdxxcg.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtxrrsuuhs.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gttejndquf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtajbnynxe.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtawbcdbem.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtihbxdbaw.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtohdcurvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtjtczrrsa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtyuvgswnz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazhuvfnm.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gtikekodei.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtsybecfhz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtyiuqhdgv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtqhtxpfgp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtquvzdjnp.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtaehtiopg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbqpvrgm.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtqvkzoxfh.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gtjslnuetq.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtobgdvuos.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtilvlwjxh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtfryiarmu.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtwgiorskn.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtiqgreild.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtqqglzgmr.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtozvpqion.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtpmwwkjos.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtbeznaqve.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxbtghjq.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtgkywvjfg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtspqhkomh.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtbmoahdhr.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtxmzhzwni.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtjtfxufob.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtjsmcmwyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtzfrprxiw.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gthdamzraf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtvpdulnzb.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtizlhflsf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtfonajuaq.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtxrswwtwh.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtybvdtggm.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqjizgvb.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtrnviwmwt.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtwgrbxlph.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtszfeuulu.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtnfurzilm.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtnjliggbx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhpgkgwc.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtyflkrkqh.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtgauhtslw.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtgrmuzbym.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtmvkirhjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtbztnexig.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtjjirmyve.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtkfvytslm.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtkljgbjgq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtpmkxtevc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjegqlwdm.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtreqageoo.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtezhgpgpn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonwdoevj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtodzfdldn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtoknqftfu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtrerepscw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtjlzrgfgf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtnoxqzdml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtnimftzzm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnsfztjyr.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtaopgxptc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtivlyxusu.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gthedarpob.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtdbaigxiv.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtudimlhfo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtuqqutgkr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gthpelkora.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtcayahojf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtfqjazrfo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxuyvjnjy.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtbpknitkg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzmquxmja.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtqrduqimf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtyqhgmvwj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtbejdmsos.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtkjdmrspi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtkiecfqdi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtoyfknhbv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaudlfxi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqvhavrfi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtlfpysdym.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtfamzayfa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtvhfjuyyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtxztlyplr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtjnrjtvxy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtafeznjuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtdideiwvb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtjshfghun.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtakqbyvts.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtoucijraz.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtbepbtgld.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gtlesaterq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtppjjemhu.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtcjmkqcpo.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdjhqdyw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtxxewhyht.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtsfajkfvi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtsbpthcza.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtpotwwwkr.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtbturxkne.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtrnbohqek.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtggvntjwm.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtsmtozubx.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtpiibvgnp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gteitqwkzl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtnlpzthwc.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxoqoavl.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gteweckbdv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtnpqmfzmt.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtrnbblvih.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtfjlnfohc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtqpkdqpen.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtxtmqvbto.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtspfwusox.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtawukygmw.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtekcxryhf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtirqqrugj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtiznptgut.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtfmawobhy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtgbodkkam.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwikwhmmw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtusiqjjsg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtmrjtvdfa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtisvrlymc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtnbcwfojq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtssaiasvh.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtefbddisw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtykxjdaai.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtyedpmhsm.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtmugofxcx.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtpydwiunc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhtokxws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbajgmdi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtfpbadvuc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtvyroxnem.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtrwzwgtbr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gttlzjlmso.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtniklgcec.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtdkztlstl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtrckjzlls.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtawtyrwlf.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtfxvzeeih.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxprsvlft.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gteccmbkmt.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gttqlovwrk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtmtfmhxku.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtosatlybr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirhrotsj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtcstnyqvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqtkivpkf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtetyvaces.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtuorghujs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtulsztdfm.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtqhavkxnk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtufgsxrzu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtwvuhmabc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtfvbzvagm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtalpjwyue.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtgigulbyo.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtpiwxqpkr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtxplphabd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtmzaxafqp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtboszuyod.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtuykjrydw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqiyirtmb.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtronqscvb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgdceawc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtyastbwld.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtaeegdsmb.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtjsilrdxo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gtoiiwsvir.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtpretxiln.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtzidowrgs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtxtjxtldr.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtpjrpapiu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxmvtoyb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtgiqkwnwk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtxlzwduma.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtwfzkifor.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtbtowbnyi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtbtfwhjuz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzywujuri.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtifwwetao.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtnvsxsqca.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gtqfmkbmqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gtfiqpepsr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtydtftdkc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtcifestfv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtskquekvr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtfzkmxptr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtvkwqmiog.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtxcwhwyxx.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtacfaxlel.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gtgirobjhh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtvqjoeqhi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtkltqndid.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtnsgvpsfw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtuanogkjv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtjugsbsxg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtxcuqnpop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gthcesyozb.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gtbbccvkbp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtgmxwexas.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtceoaacta.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtoknhsggb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtqrohjbxj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtgkeekheb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfsdkmekc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtlwybtvwy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtjoorwqca.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtyedotyxm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtoonbdrwx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtwgsdeecb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtweymxzig.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtlujkdfzs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtadnaerrz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtjijzofkj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtxyeovdtf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtadewcxiv.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtrftcdnuw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtrkuynztc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtlynjvqio.html


<!-- 参考信息 -->