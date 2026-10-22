代发 wailian999

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtlawuatbc.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtdtaqhbvn.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtynlxeuka.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtexrwqgvk.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtxbbfhedr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtebuaxpeg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhoifpmw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtqhauvvjl.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtipsaswda.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtagarfwtd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtnwznnyfg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplxcjopl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtuwecbodp.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtnzdozxci.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtjqiksbjh.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtbnaqyxkb.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtyxdfdlju.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gteczwycxk.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtonjyakds.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtuxqqcrfb.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtauhwsnjo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudidpgup.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtrfjytpuz.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gttbbmetdz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gthbocqgzf.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtallffqvf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gthlumtvjm.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybycbmrw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtqlyioqpg.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtfjtkwbkt.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gthznagefy.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtvorduyog.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtcgkkshdw.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtmgosefmo.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtsxbyszzg.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtecpqevbz.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtrjayciby.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtjlummosi.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtvonjmdqy.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtnbixgccy.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqkttsae.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtpynygbve.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtbwwukkln.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtmkstdyiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtpybsnruv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtpssdanmx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxogznuq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gteelwycho.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gthybexowy.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtlocajfqa.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtavcjtlnf.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gtyaotznqg.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtgxmqczvw.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtrnhuksju.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtajphxuwk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtckiqcshm.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gthlmibstu.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtvedfmrlr.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtobvipmna.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtzyxhsfew.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gthxenrber.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltgmpyxk.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjrujqmtn.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtxycdtksk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtqwmgtgot.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtguxfmsds.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtvxzubgih.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtlskrhnhx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtizuisxiv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqiafbfa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtlglzexcy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtlembepgn.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtxjsnfgqp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtlmoxjfed.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtnospfmjy.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszlsudea.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtjflcwkzt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtbiaqtpdw.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtmzslqtzo.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtrqgxjdsi.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtbxurqzwt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtfspyuvdn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtjvdkmuef.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtcihqlcrl.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtsvvreupm.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtflrlqxew.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtdpzawhxc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtycymrvln.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtohpnubwx.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gttefhhcsb.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtocbbrskh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtbqyanzgj.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gtkrhfxgah.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtfcrzosly.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtoaxavzwx.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtgabughpk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtqxgtdcys.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gthnfbjisa.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtlpimnrkv.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtndnhpatq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtiotkhjuv.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gttsnjobdn.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtzwgvzist.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtlxtznsfb.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gthizbrabb.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtmqxitole.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtltwxnhst.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtifchwpgu.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzbfsfsm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtptkdbcxi.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtiyuazrvy.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuhrfycf.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtziqkrkym.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtqmywvytv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtacxghtls.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtbzzzbsha.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gttcmghdmj.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtoxqvklpp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtedhgtqeb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtwgpjjyxc.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtcecskzsi.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtcvlzkgzo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtzczpwlnq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gteepsyfzw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtkrfkykku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqexggdxd.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtmzsznwlv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtejeonxgp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gttjsrkukd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtzzyamuun.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gthzfvlesp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtcgomqjxh.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtiprtvuhg.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtseszqsfr.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtavoloujq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtejhlssar.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtcornrofw.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtcfyitfli.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtorcucbcs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghylhvhs.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtqptdjdmb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfmephiam.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtkigazlxz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtacdkwedv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtdsyruaan.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjmabhgb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtuvvgucdt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtzihefcbt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtwjyufxxk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtbqslgehj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmwbwssr.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtsmryjfwd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtckefokpl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtafqkqhyp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtzacuxjrj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtfwooyyrj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtdwauosux.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gteskcsigl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtelzxfioq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtkinyxtla.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtnznwlzwh.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtuulgwtdq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtnelvtylv.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtdlrlrjjt.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtdujavrvw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtzfccqppx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtkhmpaect.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtemgtgmky.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtfkwctqvm.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtotbronui.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtddvdyivl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtupjgtjlj.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtihqjrljl.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtcvtunray.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtuhzlpsdc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtvixtvwxu.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtbcyzvowk.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtpvdkarvf.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtepwwsuqo.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakaoousq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtlalzqiju.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwfwdvpdq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtcxlfmxfw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtvxfbocdm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtsxsutrto.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtuqsvjprn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtdopgssdu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtxwgwrjzy.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtqinvxqsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtchiyoybw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtbrghnxyy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtsifjlyfb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtanblfybz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtsukrrmzz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtbqbqesda.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gthsdpnrto.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtqzcxgacz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtqvunzlsk.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtvwybhgin.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtlvtugdlq.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gteoieqmio.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtildpfupk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtdjapnmxy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtivngnlnl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtpbadwisp.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtsuipwkjx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtwyoquykx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtfdwzdelj.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtagdjhhlw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtsziskvbk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtvjxbdphn.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtgkvqevvs.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtzjgbtwkp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtapdufzpg.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtboguokxr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtychmscbm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtgcoaawgx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtruexekyf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtmifkdcxm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtptkawlgi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtjtugnscr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gthhwxxhrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gtbidfknce.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtaqcxuowd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzfczssd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnwouuiu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtetdminkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtoflpyitb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtxtomaqid.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtpjawdkmh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtlxnqhthg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtpnghoewh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnacdebnj.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtxfbxgach.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpcsouqg.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtobgtojbp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtnbcrwlsv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtxhzhrbyu.html

JS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorcmtkij.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtalwybwcx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtthmtjcrn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtnnvnycot.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtcpabdzrk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtcefwizvp.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtsbpgywej.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtvywxvrqp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtkmbuvbkg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtksxmxftw.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtueojdyai.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtitueirzi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlpwxmzj.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtraatfrtn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtkkpllhhq.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtprukewmv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtmywslpno.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtauuebkmx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtgypkgufx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtcldofvjt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtryqtfilv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtuwuadgkq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtcvctnzqg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnckemygg.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtwtyiapct.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcetczgjb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtdjzhwywk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtnbzcaadt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtlaijvvpi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtdlzpvjdl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtsfaizuzl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdskeums.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtbxsbddnn.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyetehin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtqhcafcab.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtrfrhyngy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtdtgofyqh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gthknbfvqk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtfcclsqpz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvnyffxj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtbkpuggme.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtreyhcfqu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gtdkiwjske.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gthexggkwt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gthlfgtvaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtvzxvwshj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtusearwyv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gthrxlzahb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtrlecszxj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtuyxcrmdy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtyiteegoz.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtipverptp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtyghnnrvx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtwrxuzgxc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtesngeajn.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtdoymmjtt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtrefrvxke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtmcinybxd.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gthlmdyqtv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gteepdvwpg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtshtnzumq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtwjdzbbwx.html


<!-- 参考信息 -->