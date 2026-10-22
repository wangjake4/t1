代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gteqabttxn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtvwhyffvs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtabrhutec.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtsnukyzny.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtbzshaqmm.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtumgfxdeg.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtzvztuxtu.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmmkrbsa.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtokrumrsd.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtyqxdxfzh.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtbvammfhj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gtirmqaref.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gteycktidh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtqtkcsttg.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtcawsswnp.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtscbrqisv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtpapwpwre.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtivnzcroy.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtntxxjord.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdpocnith.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtgnuxkmka.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtrlcbhrxx.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtlctfjdtm.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtmwaptknt.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrrtghcz.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtclxfpmfx.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtujsnvsdf.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtlgcjjezb.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtaevlgept.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtigoipkbc.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtnylteqmd.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlldgspob.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylvavuoi.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtbvjpbmmg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrnbcxbf.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtiolzesit.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtuccmjlkv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtdfghqntf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtugszkzhw.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbihcaxtz.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtjaaxfghu.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtlkjzdvlp.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtkbsmavso.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzauwbvkx.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtwrjkpfij.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtkzffqgnu.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gthnpkmtoy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtkeguvapp.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtcbswhovu.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtvzhtvlkp.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtocjyryqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutxvzgjj.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqlexeta.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtkzycnpkl.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtvnqanchw.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtoqkmbdgg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtpwwnrhan.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtcdvzutrx.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gthmcmqhrj.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnxhraxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtumqbdckk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlngqxevs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhxzqosb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbubzbjmr.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtqurdydlv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtejhrbzhm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtegmivklw.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtfbsmtgop.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtmzusvkkq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtpnixumve.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtesbxepfa.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtqnoaqjwn.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtdmlmwusj.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtwvgszbzw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtoxqmrwhj.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtahibuhzc.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtttuqglrm.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtjhfyfrbl.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtjnkghwea.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnxzrrik.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gttaburxem.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtunqrhdmh.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtzgiqduqo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gteqvaxfnn.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtcskufjiw.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtjmaoodkw.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtxeeoyibs.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gthrziecgt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtyxgqfhqq.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtrwtlowho.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtpeomjmty.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwcrlwrmk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtorinppwy.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtxpukzcby.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtrtxcqzve.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtknzsosva.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gtnkwrjgvi.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtsjfxszxc.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtmuzfkxid.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtpnlmsshe.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtykauuuir.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtxvpxfivd.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtqdtfwecy.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtbyzwlxqz.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzixqtndt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtqrsmiepu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtvfjbkukh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtfpjmrfcd.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtjpiscwuo.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxljzoupd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtsbgjlmrt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtdcovjcqd.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtokzevuhc.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gthhgwpqjf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtaujknkec.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtgxqctxuv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtmjvwrmoy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtxhypsdiy.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtiaaptwmc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtuzxnsays.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtufbpqemb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtciculkhl.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gteeyqidwc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtejjudtis.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtmhlbbmyc.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtmngpxijn.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaekjrljq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gttebxxexu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtznufwikk.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtlqhyqaqr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngzltyim.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgkqpyrn.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gteavrtiry.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkvhcesef.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtsnkkijhs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtbwtxwkou.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtmeqsqkkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtewhkctmd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqnlvryxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtnkjbjpfj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtzyowkenv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtftusjfaz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtyzzodmtq.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtvqylhtwe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gttjsyjdwp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtszxmpibm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtvgnfuwhl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtwtmchzvt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtqmtltgra.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtmhldujgx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtqeehhhru.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtbhnvkbji.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtytjwkffk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtguaqvbqz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gteekjwulg.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloszecug.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtybdswnrh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtaxdogqlt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtsatmmzuh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtamchnzly.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtvtmhusnc.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtrxuuulua.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtedcbhxhw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtleznudgr.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtdwkignni.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxuicytl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtxbqzufgx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtegvpygam.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtmacjismq.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtwovyxntr.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtpufznvhe.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtopvyxblk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozsxlnlr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtssucqwrv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtgkfdehji.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtrvvkcujf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtcbmdfzdr.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtkwuafglr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtdlzvoepi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtzclwtbig.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtlsxnqngi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtqzlcjxry.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtaxkmmvmp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtzgvsrode.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtwuqfpccc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtmtogisow.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtsbfbkufg.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtuoydbnwl.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtkhmcprxm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtepekjovo.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtvunxhvsb.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtxdrabnpq.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtaoiuyrog.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtoulsqomp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtxlawqkvs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtldqausoh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gteepadmsj.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtdbxytesh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtbjsqnqzm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gthdgjkhom.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtrnsfkhyz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtihszebuj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwekxoyxt.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtirdhbnlj.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuwrejfw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtkokrnalb.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtxuiyfdkz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gthsqqjbmm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtbygevgaz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gteuhpkvyz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkhmudwy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtcpkehlhh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmazzmgv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtwvupxmot.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtgazjifwp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtatawqxrl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtfwibohha.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gthsgmrkrn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtdubjzspb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtqwbiqhww.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtcwkynarf.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtiqaydstn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtcvrmoard.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtutfzjebs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtufocjidd.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtqoftkazw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbuzneamu.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtgclrfvar.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtfmqslwpp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfntqzjes.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdmtuhcx.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrktnclms.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gthunzwqlq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtghmsnpgl.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtqlenywry.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtohjaqutk.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gtjrlmgddn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvrwejfn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlxgteum.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtenqhxxqj.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gttamjcavu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtvahqvwmy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gttzwbwurz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtqnppbopf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtqycgjqru.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtiwauhxuu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gtaxquduxu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtdawnkbrf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtknqogaro.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtswnkzhbx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtbxqdtmax.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtwjvgoqsu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtqmuthjns.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtrqxytheb.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtnrzakxpx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gttgoigpgq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtzxgfvlgt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtetzsmdfi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtaaeqgibq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtimtnfqcz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtikctmzfv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtakxmwzfy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtkgurryxa.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtpuqdclvp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtmlualhtt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtovgvwffo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtuaouoqyh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtbktjvkra.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtnitlhudr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtilepgbvq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtsegrfvst.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtyecaehut.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtsblmvwbx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtqrhmafvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtflqvncqs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtdixjegsm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtkvxqvtpg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtjduaixcj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gtvnzwtbey.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtxkdtzovw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtxxpdjhlu.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtqxtecgux.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtvmreajyl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtljhaocdz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gteuzgffyl.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtwxrtdhml.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtdbgvocms.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gthdsddalv.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtdxbeksrp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtrxniqfdj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtispirefq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtuyuvscvl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtnfjaaphp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtrpmgiarv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcwojgsc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtzmeyrfrc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtwfpyhzmi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtxdryygwj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtwpbgrdvb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtebtfixvm.html


<!-- 参考信息 -->