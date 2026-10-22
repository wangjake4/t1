代发 wailian999

================================================================================
来源：http://dali.cheryme.top/Article/details/gtucmceoqp.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtzdwnvpqr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthpuzkrmk.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtqpjvimye.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtirrvveko.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtjsvhiygt.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtwgyfzbyc.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtbqbfiwzl.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gthgfksyek.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtmdxbkfrf.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtsnvinlcz.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtjjhafnpy.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtzavueqdg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtvaaktgqy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtgzgqfjzc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsxkxeomg.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtuxkqbtqv.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtobwptqrk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtnkcsuraf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtnhjkifue.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgxggbpbi.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtbgfbkgie.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqpmrraz.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtdzztsjtj.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gthrqgnsap.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtbyxsluhs.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtskzcefcn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gteydihsaf.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtjcueivox.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtjwznjcbv.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtlvtjbmak.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtknoyvqdc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtsvkjcjbv.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtothxtyes.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtuifhpboy.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtplxawbwt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtjwbfegdu.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gttxbtwkth.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtcmeexbee.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtezxneaen.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gthwkbkjpl.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtrpoerfeq.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcepxfbxi.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtamhnrqtj.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtlpouevjj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtfatciwvk.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtzznhgzfx.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtkzlgwrmw.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gthhbunpei.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtdiqyrhkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtvfwvccer.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtylrcoyzl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtvfqbapzg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtsytaprno.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtltislxge.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtyrtftzek.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtubiopabf.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtdxmmvwxz.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtmqeiotas.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtntntfwic.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gttjxtzswy.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtmxtezafv.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtixzjzqmg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtikmbuevo.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtalsedceo.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrwiglwj.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtqgiybhpq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgllrnjc.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhzxbuin.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtykzohbrn.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtyxlpvenl.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtbytamthy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gteocisdch.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtybpkciwk.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtprwjaqnj.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtkxdtekxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtbjhlzpua.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtrrpvmavh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtumgkxrzz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtxcajgmhh.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtrzggzvvk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbcrmkvgy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gtvbpazixn.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtoyoqofrx.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgakgwsll.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzeouapy.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtslqflbuh.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtdhtufval.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtigesiwqj.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtsaaoefns.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtihrujtwd.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtjfkzzwtr.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtiojvavgw.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gtvgzhmnbr.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtfnxjlehu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtfsjrvpvm.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtxppcxtfj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpvemuqxq.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtcyywxqlq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtykjpnmvx.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtdgxwnnrx.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gttdvkiois.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcbnnquev.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtmfgcomuh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtcbwhjwsj.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtoqkuchwx.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtgewpfyfa.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gthiiumbsi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtdbuhflhm.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgejicupb.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtgwyshqyn.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtilkshevq.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtaojxbcui.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtwntdzlyy.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gttxjgskcu.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtfugkrrid.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkprpjzh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtepjhyntm.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gthumarcjm.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtmxamprgl.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtcgdddvvp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtzobacfcn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtcurxozba.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwaudwzz.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtcdnceqzd.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtqygrjryk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtpssczteu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtuognalot.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtpgdiqbld.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtmfohwrdi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtbnxfhozp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtcnzwgcqu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtyizwjzrd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gthiozmvju.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtbpuvvkpt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhsuaufh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gttpfdnnlx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtzjkfoape.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafwhqvls.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtyrtqpbck.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtmyicbxdr.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtuhswzkoy.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtujklwmwv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtwhujcadl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtubtiwzgz.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtkkyqtwoi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtqzlhjnlk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtchfnkbqb.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtmoryrmkz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtymgnotfw.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtisutqcfi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtkdlujsmg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtrzegtamn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtbdeibnpx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtbzylxcgs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gthboejvdc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtgfhzpepn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtjryzupgl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtcmxchljz.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtdmpltjpa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtnegxonck.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtluatwrvw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtodufvzqk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtlowtdazh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtgugrmggv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtbskfyymh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtqqvcmkgt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtzvngejcf.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtegudiist.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtjpxdndmb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtisfxjlwi.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtjwofzpge.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtgtxvnhqp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtczsduxfu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtkwhuhnvu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtdilqbgdy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gthbxesaqg.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtkyooetwy.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gthuxqdhgo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gthxuulxda.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqqzhcgig.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtjzgkpiel.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtyjsinzmu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtjpdvpbbt.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtipocuyha.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtmrnakxpg.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtyldxethi.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtnzpnrpsl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gticxgnwrl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyuaeectp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtgdtgdzpv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtujumfvwy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtwkoosqfs.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gttwzndvjr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtupaapnna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gthddtdjso.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtabzhlyte.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtsxwzgtsf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtklucvuwc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtiepvxfdf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtnvkypvil.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkofkhmh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtrnomvdld.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtpqrhwqpz.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtfbuwhetg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtkjcxmjhp.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtifowkedd.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gttzpspvwx.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtpagxaosi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtrhhsjuri.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkptrjywg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtncnvzihm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtsepnsfcm.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtlmhvrgbe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtwczrysbk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtiyrpstra.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtvzvognbr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtqucxquwd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtomhghxxe.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtydvzcmrf.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtwebslbea.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtstaswsgv.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtfgzzvhyn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtlyzdkmxq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtrwilvrgl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtfrysdtsd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtgiwickgl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtpfzelwca.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtmsrjqclw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtlyldzrrv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtloszzcdf.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gthfyrfnrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtrnhhaqcb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtlluhvfgx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtkmasajbv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtipsrwawk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gttonzmgdu.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtszhqaghc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtdpnljxvj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtjberngao.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtycjmbdxx.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtgezgkifj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzhpzqrls.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtichqnpgh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtrmjkvkvt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gteiuzdodz.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteknvkgex.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtqmcxvzng.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtsjmutyqz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gthrsxvqsh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtczenxkhg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtxwjsjlge.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtbwqhdcly.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtdreqfnfb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtyeyjfsqr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtxwuagrla.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtghgxoqae.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiweglepu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gturcfoekf.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtgkqljbtq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtgtfbebbr.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtdbsmpkft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtmbxanrfi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqstuhfib.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtnirwjgxt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtxpkkthyk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtmscxmmbg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtawipccek.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gttkdinmch.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gttkgosdjy.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtsxtjtepo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtzcwtgrxo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtngtyofwl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gttcmvithw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtorblujmh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtrndbhesu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtwmkefqfp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtlhtrxuii.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtzszpcaps.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtxyqpvpka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gtruwjcczq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtosmzvzcr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtkxfoddor.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gthlsehumn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtekxcsbtp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtthyrsqht.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtetrxplhs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbjwianl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtugevpstl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtdkaalxpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtsqnzhicj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtespdgtgr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtanmjphxd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtvmshxcky.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gthmlvoirh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtgsjmknrm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufsqrxct.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyzfyjyc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtfvgpqqoc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtqubxzvql.html


<!-- 参考信息 -->