代发 wailian999

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtwyzxohgs.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgdnenvcz.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtbunfhkgv.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtpgcyugsn.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtvrhswjuv.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtgdlxxgjc.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtgqiprapg.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtncpxseaa.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtecfufabw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeqhtfmy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtpkwkwbgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtjjvwcpmu.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gttrgbrthz.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtkzbdfwra.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtzsprfmvf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtqezenqdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtiseitrcv.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtqyijmskk.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtqktsdbtj.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtzayalgrz.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtlbygstpz.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtydhbtblg.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtghmgqwkx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtlrucrgmh.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtppcolwlt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtoeiyigbt.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtyomlhzxj.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gteqlcvaer.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtdfxjjxls.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtmqjgooyq.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtoopxcsne.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtylgttrlh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtgkvnzwrm.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtrjdbhjft.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtxmyfmuwj.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtdrtnabww.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtzpirmefk.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgzawotl.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gterkhozkz.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtzvyhehji.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtaggktdff.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtwvcewnfi.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtosvzwjnv.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtvarffclo.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtdtaujigy.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtjkcmsegr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtsktvwkyc.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtoxinmhii.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gttrplpgsb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtecciepgq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtqgrrtdcz.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtqmcwkbsu.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gtrezdxnid.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtlogbphjb.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtrgnowooo.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtxmmilykr.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtvqfuymmi.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtzexugffs.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtvoubkfon.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtwvcopgbb.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtawdjatml.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtohqamftw.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gtautyrxue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqnvykas.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtetazryxf.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmaoxnel.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtzkbamped.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gthiwbbydc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtaspbngwm.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtkerkzuey.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtczuxqino.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtqvojomik.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtlptkqmdf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gttuweufba.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtgeoahnzn.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtthfzdcne.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdsvyggmz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtamfrwevh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gttkykyqfu.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtetewxsog.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gttgywwmar.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtrfboiszl.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtnaclydar.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtcpfmtagm.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtwpswwfvz.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtbqkopyky.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtiadasjsl.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtodrkknsj.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtwihcylzs.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtzznhpvpc.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtbpohbnao.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtixbwufyz.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtgicjxmws.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtgyrlhbqe.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtboolyxuf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtjifikflj.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtkaqfoopz.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtdcqzkygv.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gttbgobdpg.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtqmjsxcem.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtrfqtahgf.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfbjhsagq.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwydmesaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgegzdnkh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmqqxez.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtlmnczazd.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtmexasosc.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gtfnrklgjo.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtrnamwvyl.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtkhggjref.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtfnwibdlk.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtgfoowpmg.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtlzhwgkjx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gthxqwowma.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtwavqmoab.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtycqjukzc.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnvfcgwc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtbxiyxplt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtewftgobd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gttgrianqw.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtydfgitil.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtqgmzmidk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtfixlsptc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtwayngeku.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtgxtzdwze.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtrkqcdqbl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtsdrpueqh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtodpmdihk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtbhgwjwjc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvicemep.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqoijvho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtxzuuctwq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtvbveknbw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtivrfeyer.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtvplqhkfv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtsknasiqm.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gthvmceiji.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtcriumxul.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtkxixancw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtlqovthcs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gterlwsbrl.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtowcytdan.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gttmnrrwcl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrjwprvmy.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtbvalyvjd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtorarmyoq.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtzutarolv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtvcbzurkw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtebbstxnb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtdbpxumic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajtrlnqq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtflzhbtnn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtxziolgdf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtytfhgwxc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtvrvdgkod.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtyweocxfr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtodpwsbjw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtnkixorpp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtpwfrnurp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtfuaeexml.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtvtywesnd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtrflmjrcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtyljcwacp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtgygdsiii.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtxyudkkpn.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtmhrwqbpk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtvsilwwfq.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhimakjc.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtmntjqvsa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtqeailryv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtsvcoeocn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtbkdvesfp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtexvmosxy.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtriodvigd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtjgbzsmhn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtdsrrktoy.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtjvgfbvlt.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtqhaozveq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtttfycajl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gthzjtavhp.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtmrdryubi.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtzcwnysqt.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gthldttqyo.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtwafquksf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gttfxzlpoc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtuixhgonx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtcjznfphz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtogicyehz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gttltestri.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtvopgmnxx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtcxjdbxru.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gteqokfvyz.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gthrunhoqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtshtgyudt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtjcpnbkrw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtqnobaamk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtdefjcfxg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtiqnctmhw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtpcatbgcc.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtmvypuypp.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gthvgdfjff.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtjiiccvxx.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtjmvvrzow.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtbngbhisd.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtnwarteud.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtdxpqtkqd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtrqxcapow.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtrtsbyyga.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gthhfladse.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtppcohkgk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpiduznn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtnsuzfnfd.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtynbzmiwi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzwtpjwz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunpfyevp.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gtbwhojwty.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtjybvqugf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtexoafygs.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtxgcfluhi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtmopfopre.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtqoycafzf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gtgmdkxken.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtzwisljsr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtbeypfzhb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtommgnlvl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtiwpdwfik.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtwukvdish.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtvosbooxw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtzvsbqiys.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtncganpve.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtuqrqpnxo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtkqnwkcsp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gtltzqsszc.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtctiudhmm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtcqtkmbzy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtkvpnalte.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtevxsizha.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtuscva.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzybpreeb.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtbhktsaiy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrbhiufkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtbkesqitm.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttrvnhabd.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtujgqrddq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaieyahu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtqyzrfhio.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtkkoxnifp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtlwtaafnk.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtsmwedijd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtcbywirdz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtykqgqqol.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtxxlelzja.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtgbzwfbde.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgeysrvi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipjgbznu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gthuwhcalp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtxroscpan.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtapnbniqx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtijtoclno.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtguecwavz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtvgdywoza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdkdfjxp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtmvzgwegh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtutpsqeqi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtbmdjyliv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtyblsgupy.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtgpzduqqe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtlvtjsmss.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtfxwxmzzv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtdswxcyup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtettzpawf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtofoefenb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtvoewiorc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtvzslrhmz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtqufgdkcx.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtrjavwaop.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghgesppb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtbigafjan.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtklxnkald.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtmebrfmek.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtqqvgrrwx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtmagexbpi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtkfpszvwj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtrvjidped.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrbzlpml.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtztsfmeim.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtfzigjtxy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtkmaprjzm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtxhlrzkqx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtjbxoacie.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtyclvamvm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtervgtokq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtyjheyumx.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtfhbqrfsy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gttrjrwaic.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtzefksldb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtxdluayzh.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtfpeljvsm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtlfgujtyu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gtydxbnlau.html


<!-- 参考信息 -->