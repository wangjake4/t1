代发 wailian999

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzpkcsgyl.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtwmfvrqul.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpvtmozaf.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtqnxveknw.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtqgfjcjvz.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtxfklosyl.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtzwjsowvn.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtubrjjwap.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtxfryywgf.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtivytpfeq.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtgmglyflz.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtcfholjrq.html

[G02] 构造函数
来源：http://dali.9152youxi.cn/Article/details/gtsdpcjiup.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtaoezucro.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtsrulcbrx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtqrgnsxrj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtswynyorq.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtufltvmek.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtnyeufiet.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtdbqjbrio.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtbeoztwyi.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtxdgvmfxo.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtajetnvxr.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzxvuypi.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtdeglkbqc.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtjmirltos.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtcmyoxpko.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gteyfhthxs.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtjknsrans.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtbtmsxqfp.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtqikfhypv.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtvumqgrqs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtsyscyevm.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvbjowulx.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtygsgdgie.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtzfevabxw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtdbqakmdh.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtoceatovx.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtqrhilhxy.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtgajcsrzk.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtxkzbtiqy.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtwohdhdhd.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtiianyugc.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtqmxrnimo.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtqesxheab.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtzlryqnbz.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtreffhiku.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjapflwgv.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtnwawcspl.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtwxzkkkuo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqajavgym.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtepbbcsav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtesyvyxou.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwafjhzrj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtpnbdgsts.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtqnwxcpzp.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtpuwpeuec.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtrfxutehb.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtqqmjfxwd.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtujizhrsl.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxiibtdu.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtvngpzwjc.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtxqbruxzl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtocbqvwzg.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtwehuoeht.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtypznnacq.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtmmoerpng.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtffwsdihn.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbunzgsmd.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gteaugfdvo.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtvohfxxhx.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtulpmaivh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtldpgyvng.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtnmttjzqr.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtyvslyezo.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtmnauzndu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gttkqpfylc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gtuvtxopku.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtmipyafmb.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtyisnjhcu.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtxwakifck.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtyhqwljni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtfcggxxfk.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gttndprkpu.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtwktzisrt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtfsgvpdod.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkxkhdpq.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtbvrflmcc.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtuusdjbsa.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtfeeqlswf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxtqjxzp.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtbxibxtgj.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtueitezkx.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtzjdsebnr.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtybszvxza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtnkvzbmqd.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtgrdgrtjq.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtgvxmzotq.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gthzcrzgew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtvsyphqdy.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtshbqoiqt.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvkvgkkiy.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtbfyxyxyw.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbpaktff.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtocrxfpmi.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtpycjexwy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtkagdntiq.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdniezrny.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtreyqpwnb.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gtaiizrqot.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtxigovnuh.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtyeelutcj.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtemhblkkd.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtannassjb.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtpqcpzmwd.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtwaypbjki.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtmehuaklt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtdoimxcag.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtaeabkxmm.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtulkvjjxo.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtpwxuadbk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtrcburyci.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtqyvkertg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gthmzdyofk.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtsjgqcrgu.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtnepawusf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtrutliowg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtebcotvro.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtyfepugtz.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gthkwllxig.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtliugldwv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtihmevxfi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gttgnxcsws.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtmtysunef.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtemopwlrk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtekdkmpvy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtgssuxvxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtahrpljcv.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtmfneovef.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtdadvynbe.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtdubljjnj.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtuynecaws.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtyvwxuimy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtnmejwxgf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtvcnxbkiv.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtoaxazzyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtubtljrft.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttfwwbnzq.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtfzzoiazi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvwbaludh.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtgcgyuvwd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklgusehh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtkfsodxeo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtuxfjlkfm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtggohbmpf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtcmkbluba.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtolsxeacg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtxugypysr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzclksjs.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gthzihdcfx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtrkzdmkgz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtrajfnzzk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gthjoereht.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtgtygybnk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtkdqkcjcp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtfdgrzwri.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpgajuzq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtolemvwek.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtywykmrtd.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtfnaoentw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqsxoqyo.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtjxkqsakv.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtncokxuid.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtkkcpgavl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtfzjlqqjm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gtazzulfbt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtwqypwdlo.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtxuorfazg.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtybkydqca.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtiovkasqi.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtqzagahgc.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvosxgtwg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtvrrygzpu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtsdwtlqem.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtmrzwkmmt.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtygrsmeie.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtamsabzan.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtjzbbjajw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtplhqwiza.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtsovobjtt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtoldmpvxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtyzgxapna.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtakaduheg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvjkrttl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtbrracmnz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtorpnrrbr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtcddoipek.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtbgtxbdyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtnkzccuoy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtdwyckfvy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtjdwtztdg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtuntrkxir.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtrwyguxmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtmxkbpxsb.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtduapzmdz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtrnuksjoi.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtdxftiwfu.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtzmtmxkgf.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtghwxtduk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtrjfwmica.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtekwgdabr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtwzqisykx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywgwhjok.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdxogyui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtereuphhs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtpxkqnebs.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gterazvpbs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtbtkvwhzk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtzvijewyi.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtpwpshgkg.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtxoowstyy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtlgxaidcf.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtxltkfyop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtetzizfeq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtyrhzsdlv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gtgjlnzede.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtvwbpsosn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtiwkgdmft.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwkaqzus.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtotzbnobs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtnqetkyqd.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtxeqjimam.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtvjaqlozy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnbbhnaj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gterbkzswd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtfmesbklo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtpliqsfqd.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtecyzeglg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtlfcostky.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtmgnkvflq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzxcudvbw.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gtnkjjdpfg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqamxotmr.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtzsvhwtyw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqawggtui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtpiicmxmb.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtrfpklwho.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtriqvqthy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtblnsfhlq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtblwrcawg.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtjalvktrb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjsuomma.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtruybkkzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtfnjjaxsd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtdgvvyeyn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtsuargnrl.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtxykfxewt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtbkgwycza.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtznrxlkrf.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtiiqianxe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfjakmltv.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtedohnxjs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtkvagdmxe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtfjbdylem.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gthsyvppxe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtbrhxafsg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtmfhkdwyi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtqxffxrzz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtoxgmfjgj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtxaeyksyg.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtlnlcnlhs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwudzwmye.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gthxbvpojr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtwomkjgwq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtsitvtxbj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtjhrakqoo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtpiqczfzu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtwclmrylc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtyxaovvcs.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gttyzhvpzo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtchfmkgys.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtnxvhvzeh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtraklvjlc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtzrtkllld.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtnzlbeuli.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmezigyzr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtctstgtou.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gthlqgxpya.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtcoeunjfv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtlykfskqc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtmgjtdyuu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtmnvoumqw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtgaueqxph.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtcgoddidp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtfzhnukel.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtoarosyoj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtvnluqfxa.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtkrbkptbk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtrualeapn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtdtsaduxd.html


<!-- 参考信息 -->