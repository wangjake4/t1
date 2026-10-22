代发 wailian999

================================================================================
来源：http://dali.tanke756.top/Article/details/gtekkpmrys.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtfzimwsuj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofccnjsj.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtpbzzbjkq.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtjmetasln.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtcqdhjyzl.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtaeuwxrnu.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtixjrzkpq.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtawuvfgjj.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtlaovpvyn.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtyrctytgk.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtasoetnfl.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtuivilxlx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtxznmufaj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtvgzzodex.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlphpxegh.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtopvbeoxd.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjonawcgb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtheiksrob.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtconxdcmf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtppjztead.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtfsnrpook.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtwiglhzkl.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtgxotaupp.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtoycftnsj.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gticwkadys.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtwcrggbdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtpktzcvjy.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gttqjsnvpg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtozognbzz.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtlxwvlply.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gttmgkrgru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcsldnnl.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtkvpvhxzz.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtulgaebmz.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtoryfjcup.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtrwtdcexm.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpicewcx.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gttgpyrkea.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtiytzpdpt.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtnnmuqg.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxqbfzrnj.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtjnhnsljp.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtgstfteau.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtnkqiadjd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtbizycecb.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtfjfxdlqz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtrvdwqxmk.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtwhckmjwx.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtmlgftz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifntagko.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtbqpuqwxx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtsixvslnd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtfysmralj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtrvhpcyqw.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtlbhktttn.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtpkijcsse.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtbewhwjof.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtuednkruy.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtbhlrvulg.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtfbqotixb.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtlvdqipsc.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtgjaxdcgg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqtcedad.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtosfxyhst.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtmrydzwnp.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtarbgeuya.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtgkqdlwgs.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtopwdixbu.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtojnsttye.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtxuyphvqz.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtpuzugndp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtkforcfoo.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gttedzejku.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtokpymden.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtpzukpvfk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtaiigzcrm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtwegifvwp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtqetsfodm.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtmxjbtljc.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtzetekbun.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuytabgp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtfshrdfxw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gteehjzgxj.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtjjzekpaw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtuzxarjhr.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtiadqfpon.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvelmpoo.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtvaohdrfw.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtntphspug.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtfuekbibq.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtzkpoovdy.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtghquiuqd.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtktypuovp.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpidpmmaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtcrdcicgb.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtamrbiouz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtyixdtsmc.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtcgjarabb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtcsckbpdd.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtcyniyqpw.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtjdzwgbhe.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtahmgdodo.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtalvefxvn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtyajsbegh.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdryrnmbu.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtzlzoiwcq.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gthsnqphok.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtsyguicfm.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtwrhfodvg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gttpricndt.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtwuylhwjt.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtqoqnyvxv.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtdhvpigne.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtclyiewsc.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtwvcrjyrd.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtbsvswxfx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtvzbgfrhf.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtmezhmtue.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtukfrneep.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtyxgdrcvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtoitsrvjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtsuwwooin.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtdtyxhixh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtkryxqeea.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtobtypoxw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gturygyiye.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtfbbhzpfy.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtyzeoupzu.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtapzncugq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtpolfgrbb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtjmezzfyq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtnassbngk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gthmdzhqxd.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtdlimndni.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtvxsnjzjj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtjmgnnafn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtwttevgth.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtuolmlynn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gttghyhrfw.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtmlpxnggs.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlzsdhblg.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtisdswuxk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gteyhamvmt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtvkfpebwd.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtcnezghce.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtlzzexffc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtiizvuaja.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtnughamzl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzgkdbuzu.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gttxdbazzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gthzvamblu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtepxctwev.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtfqgpcycn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtikjbumvj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtcfsndihz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtgxzzezjs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtndxvjyqy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtexcezzee.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtybsassrg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtaoncyywc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzhemhlg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtoyiecrug.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmvomuwd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtxsoznhhk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtyetxmipr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtesgqcrnd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyspdiogg.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtcookkwgg.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gtmwsultlu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtedfbmabr.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtzbzzrhlf.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtmibdtart.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtgbbrcyyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtlflflwzg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtjexrsxww.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtjqtlamlb.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgocjpvre.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtjeoiztnq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtqbcyqeat.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtmdaoabpd.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtfdwuqwfa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtiulweema.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtkcvmbctx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtoonegncn.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gthoffcbic.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtjnjbtqfi.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtwfjnzdlp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtynbyfdtd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtustlucal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtjrthwnyk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxkzhrfxp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtcowwdorg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtfqabeqxg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtfyrnexqr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtllnsnbzr.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtymvehaxa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtcdvbyrmd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtpayuquty.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtgcnifoqa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwfxgujo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtrotwyvtd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgtyfrkh.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtdrhorsqa.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtwimbrcug.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtvtcnlbxi.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtrvtkllvk.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtpzkztsal.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtgcybcuiz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtvsbhrtlm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtuugkohvg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtrghjuxcq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtmltjlluz.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtvxqiexwh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtookijbee.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtuwcxdbwf.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtsdntoliv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwjwyloa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gttvqwwiwb.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtiknbbplc.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtitkysoji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtemqdvrjf.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtlbgaeidq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtfuiumutq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtnzcaveum.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtvfjzaaif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnxvckda.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gttvunnevs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtjcydgiav.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtgrausvba.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtapbjwanw.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtgnvwksaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtlsxieaeq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtcuhmrwtj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtqrdozuvp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtvxhcgqaz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptnhlgqy.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtpkvfztip.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtwdvcoeyj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtydwvtypu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsauaynbp.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtinloyvgo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqbyzdeqd.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtflgownsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtevrqgsyl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtwjxovjhe.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtjtcaunpn.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtredctjdu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtxurhplvp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwjimczvg.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtfiaobakm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtllyfqpdk.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gtbcjublab.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtmsngnmlg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtargnczmn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtxjbqstnb.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhrwoydk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtvctnzoqt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtqxnwkofu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtrptuuoao.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gttycfoiby.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtkhuglngo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtfmcxjpws.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtvvbxukkb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtheldrago.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtkrmklwew.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gtyubuyvuj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtcrqdbhqe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwmajjuhj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtlygznzun.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtdztbdddf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gttnyxmfyb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtpppmpjoo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjitxylv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtguigxtoe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gthaedyrni.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtwdltbusy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtqktfzebr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtnrycdoia.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtkvxoczjn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpckgxflt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtcnowtxgn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtklalhatm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gthwiyyqps.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtgaqwiitu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtuzmgijdj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtqbkxrngv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtdlamctxf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtdgsecuiw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtvxshwwpm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtyprgtmol.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtqnbavefz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtktuwobdi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdstlqeqz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtufbivetf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtskvtetal.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtnodvrcnk.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtyprkgkkm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtmidkuawt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtornfytfo.html


<!-- 参考信息 -->