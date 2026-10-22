代发 wailian999

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtehwfamea.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtrznxigwy.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtztmiznbo.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtiigepixk.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtonbbvzmn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmbhvaxp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtudaouczj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtbtbwmvnc.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gthtxetpit.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzstxlseu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtksyzkipx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtpttatriz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtjydqqyif.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtbmxeswfo.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtvdvuzsav.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtvspetkzq.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfmgdsdz.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtytncgjuh.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtmhchkohh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtqgdsatvy.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtanxmbusl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gticpwqqrr.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtxqaikmmv.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtcnzavwxt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtoopplcbu.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtznzjfadr.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfswkdesr.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtuxnjgret.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhdwdtbr.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtwhcxzprv.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixbqpvzn.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmkcytcd.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtlogywgog.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtrwxpmnbm.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtrxxfqgam.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtovqxcibw.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gttqjdheno.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtwvgmhzep.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtearefidy.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtlocglnup.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtcjbidcxn.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtddrlqtun.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkxkgwibf.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtimawrdln.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtmtjglkms.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gturbshnqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtsqdfrrvq.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtghmegpzs.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtshphjmhc.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtrazaaxts.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtmlcrhine.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtvfojxhqm.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtuurokwyo.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtlpnfrwjx.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffegohcw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtvywyulzx.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtjefpsmqv.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtvdyuptlu.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gtaibhaala.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtwzbrabyo.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtzpzkzxho.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtrnsvffty.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gthkxtuhnz.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtcetldonk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtkskwkkwk.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtoqqfpdhy.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtcleswejf.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtztgzfsaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtvzhjwpis.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtopfwwgjf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtqqkmwsts.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gttrrdxxnf.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgrxmdvq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtzwbstxgs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gthmsrtxic.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmduubmjh.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtxfukdaxg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtleibtkbq.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtkiirjcft.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtlbvmzprw.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtgslfpxjb.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtsesajdqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtcfgskrxq.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtapcbqinp.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtdqaxeaub.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtmeormmir.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtaxyydwhy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoyfiqwrm.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlyvgntba.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzrkldsu.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtzomxowql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtitozovmw.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtavfbncdn.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtwiundrge.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtthrclnry.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtfhiipujd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtlpqspxtj.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtcpcirkfo.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtothghlil.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtupclzzef.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtbbqbqqbz.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtvwhnuunv.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtcbrtiwbg.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtdfkntrqi.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtzhgedmda.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtbjmykzfp.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtykmyxrsk.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtcwhrcexs.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtcuexotum.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtxiunbqan.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtfgwbanbr.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtrmdsoejx.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtrceuspya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtbpjltknm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtdqaqywtb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtvmdvfjkt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzbwueot.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtapymcbch.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtefylqdfe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtcwnhhgii.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwznqyuak.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtrykvruhv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdbjdobtn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtecsinoqn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtqaxuurof.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtfltkgqby.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gteyaotlax.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtoijxzcjf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gttbxxtkrh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gteoxumixp.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtcoepvijr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtdldmqyor.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtsvjnmzzv.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnanhmqxl.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtueoguizj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtwkktpdxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtusfrhxxu.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtvtbbnhjz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtsvcvtues.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfeuucxfy.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtovqckbns.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsozenqvz.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtrdlihsba.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtzgxakgvl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtijvssbyl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtutiliqpn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzanmgvwp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtfzitlqkf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtjfklywqc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtuuoamcdg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtqfzqvgst.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtsslidyuy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtkizkkcpl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsyrwngg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtxmsbitdd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwljjlinf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtygrdxgvo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtvicpofrv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtettyqfmc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtiijgjzhh.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtfofcfppq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtoorriyly.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtzyzghtra.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtonwkmoei.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtssbxuvpu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfmhayfr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtzhgiaasa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtvbisorpw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxmgeywy.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrayxeelz.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtqeswvcww.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gthvtrpupr.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtusclooqn.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtvqzllwgv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtmyijduet.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtwiyappdk.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtevvpxrqn.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gthxymztoy.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtfaiglrtf.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gteiwkvvvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtigdyyzdk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpnmokknw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtsbzwshrd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtjdiqjqrc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtrblgtcud.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtddnbsdoc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtqyfexgry.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtwukxnubf.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtdvaiqxto.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtjbtuippe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtvxdszsdg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtaoolxprg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtwqfarwhi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtvqjppsop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtexhhcvqz.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtbigzsxtk.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtydyzffih.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtdxlksmpn.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtdxygyljg.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtrozcbqdq.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gttrbhbtel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gttanoozko.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtwdshcxlf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtvfzplgac.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtbenigfbs.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtdjokjgjk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtahfqhkzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtsmsltbnh.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtymyuourx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhghlckz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtmyfwifno.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtrnljamru.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknzgdmdy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtxgcrdrnp.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtuewvbhae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtazxqhjgs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtqhzrccut.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtiqpizlek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtshmiczep.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gttemmffgh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtkbspjocv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtryibefxl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtohbgawvb.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtdnvhubpf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtdkhadvgs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gttqfzasmc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwnamkvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtdnchvopa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtrozpjqkt.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtuglsztnh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtjaekzldj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtdqogowlk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtruanptbf.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtfwsdkldf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiikhmvvo.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtfelbpocq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtypgahkgi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiudwhzj.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtdavpwgem.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtqkhihfeh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gtptyjrnen.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtbsbtebik.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtdyghtuol.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtddixkpek.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwyulcqzx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtpbyftimr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtdcslnlum.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gthqxcunau.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtpvbzyaky.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrtlgqbsf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtkmtezyjp.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtuzsckfnm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsnmcsks.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtckttaxcw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtjsgqyxnt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtyfrlckrq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtudxhkvfx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtcgrrtpqb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtjvtoncpg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbmoqgny.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtlpbajhgi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtybwhutxm.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtimjwkuov.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtgqoqotjj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtnszmrosv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtizoiavpb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gttiwxrizo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtnwpfddnc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtjcjwzmza.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtpmnsqgya.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtovonptos.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gthfnyhuvc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjrlquok.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtmpdkkjdb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtmolkejbh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtfoqtgdpk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gthvokxmve.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtvaitbong.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtqxpkzbjj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gtitvnwoyr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtnyxksbcd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtmfwpteru.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtdluxnkkz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtgdkmtabb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtoybifwfo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtkapiilva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtfondehrs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtzotwmneu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtbkprqzgu.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtiqnubbmp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gttypbbgap.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtmdshpdep.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtyonudkui.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtqjajnsar.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtvwzuoesk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtfbeewqde.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtuvusthbn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtoktceyqq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtnzrfrzrf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtqxnucbua.html


<!-- 参考信息 -->