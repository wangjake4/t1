代发 wailian999

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtmwhrjdie.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtlhddzegm.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtjakiroxb.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtiazcasig.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gttolioobd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtbvdgycar.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtztgxzklw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtmpjmvbdy.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gtkpgkatnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gthnhqgfez.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtvvtmghey.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtroxdwrfk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtvrwjezmd.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtgmofugmj.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtoolnhmxl.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqrggwnp.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtbaoulpqn.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtuvmtnxfa.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtuhwmdzra.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtxbykpuzw.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtiodrogzi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnbqnrcv.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtxtvuvuld.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtkqnxhxgm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtkbbqwhhb.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtvyggdjlc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtoyslkhhb.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtxtvpkiir.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtklvvtuko.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtcduegmsn.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gteudduypx.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtywunvgzu.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdngsfuzu.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtcdsqmnog.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtslmranin.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtygsberoh.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtqcivdjwu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtjbpcoyvf.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gthmffvozt.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtiuakhoew.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtxixcaluh.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnayiipmt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtowjptval.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtovcidusf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtyxuzqmuk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtjuzckkld.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtgvhfdmgr.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdcvemop.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtbblxcvjg.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gttkbrzzhd.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtjdweacym.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtjufddmld.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gttgncwkck.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtfpapmhfe.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhuaywqu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtuysxwzke.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtrtjwdhbj.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtznuqdigz.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtlhsbjupc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtkpckuais.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpbuogly.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtlktzwene.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtscyqxzbv.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtdpoqgrcb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtmqxhhdrg.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtwhlgiwxx.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtwxmjzgoe.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtstwcehnd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtkexrtimp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtqdltuhad.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gthsrivknn.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gthjpboxja.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtdnxvyzpa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtsaprmhhh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gthmkjqjhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtjvqdgqmj.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtoeoeyeqt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gttmglbiog.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtdefzxtlw.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtudbawtmn.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtkfmtijnu.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtwypspjab.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gthvilicsk.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gthucmhlxi.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtyjctgwln.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtfahtkrnh.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtcufufgog.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtwphbbcjy.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtmncjjfzp.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtdkbvzyxj.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtjshezvwx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtvtceyusy.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gttvxcqvyd.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtyhwvzmep.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpnhxwnuc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtactaiijh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcqlskjxq.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtpinoapnn.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtnbpcudko.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtiwxhitvl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtfiqrkxdm.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtnmtlxywm.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtzxleriem.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtjdiwmack.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtpumduuok.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtihslvdzo.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtbnnzbwho.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtncmmbcvs.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtvweojmgo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtcmsaiaze.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqvngiww.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtqtsvdnbc.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtywxtbliu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtpgskxwrc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtsgiprowh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtmttjdlzi.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtdfubwsfa.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtyvdyonct.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtawnaavyy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtwsysnlli.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtbyjmpzkg.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtpvbprfmc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtaquknmzo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtsccvgaei.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtqhqcjsnw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtwffwkdsx.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtrtzgllss.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtpxpxwvya.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtzjwopctw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtjctktljq.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gterfybyvs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtnuwslyxv.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtlqzdfxxx.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtuhvjgfzd.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylaffmcw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvvypdfg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtvvtlnryi.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtztrchkuc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtcnbcfbic.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthidnuncx.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtxftbfnnj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgtpacrwj.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtfvqcsocn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtuvcyqbew.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtumwoxvgh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjyjbgxmj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtsvrnrpks.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtxnggkfgg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtinddmzxa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtmddtrbmx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtqksoixsj.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtzacqfbie.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtzzqxkhzq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtptjexmqi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubyqckiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtulkegogp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtkqgqcwij.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtrtltgmjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtwrpbbdhq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtmgejfqkb.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtbxydpyng.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gtqepgmgwl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtugjikppb.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtgmzocoad.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gthuxqoozk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtfwwzekxn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtwrkdwcde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gteodzwlzo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtgtuaennf.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtceqzgnti.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbircrsd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtngukrjzc.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtustmqbyd.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtmcalxgey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtssgwmxvy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtfwsqvphn.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gttkgjshyo.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtijvparxj.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtheboqdll.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtgvqawjzw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtannxecsm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzudfrgl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtxwrczpfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gttrauacgm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtcoikybvq.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtdxccgcqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorlmuomk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtbbtuvoxz.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtkoaapkws.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtiqrlsghz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtrigrqvgf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtuqpdumzz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtifxabsrc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtiiflbrvq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtrgvsnkyt.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtoavtvubt.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtypzdinwt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtdgiuvhvl.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtvlhesvdk.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtnesveipx.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtgswcbrnv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtowbfbiah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtudrvznrz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtpyzaljtl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtrkqgsakr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtsvbdugrt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtzizzapzv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtnhhshsag.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtyunslqww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtgmwubkyg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gttbgetily.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtsvknnbyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtjqumijyg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtnkgaigwq.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtilvqzxtm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtchhctxjq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtujnjeuds.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtgmvnkjdj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtqlebtjlz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gteqxgomdj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtwmrdoapg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtixpowjzo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtlizngsna.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjkjljik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtfdxywhsm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtqjeqgzjw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gttgdhvtdm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtgqhnfvmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtnvqahivh.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtiucowelm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtljrdulbi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiucgkho.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfhnmexrv.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtvaqkdhil.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtepkwrkkb.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtlxuhbtbu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtrctbioaa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtaqywcjrk.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtqgzdqkbz.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtqxifpbzy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gttymbjati.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtewlfstke.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtyazbatna.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtickyccaj.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtlaqtolqf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtnuublouj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gtxfejfanu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtmtanhcyq.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtcrnvzbsr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjndcydvd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtinbvldcc.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtczugkikx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtqouneuyi.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtvgzmkaok.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtsatlarcp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtbmskwkaj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtvgqkfvwf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtzlzaviwk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtdcznepjt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gthzzimdtf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gtukhvdaao.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiikhfhc.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gttxxgxuoa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtddebwfrr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtshyfkmud.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtwwwdsghz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtrjfzaouz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtbwklojbo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtfrddcnuf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtnfkazrwe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtqkvqgryv.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtmavpbfbc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtbptzkhdu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtxjxamuxq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtsyrocrsa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtqfvnwfug.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtiyqkgxud.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtzdbeqpcs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtbzmfcqim.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtbukgcavf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtnrlegtec.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtrrfbuhcl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtubewcmqo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtipblecmq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtpqhtvpcn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gticygsuoc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gtbjdsnukg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtbggjahgs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtlqllcdmy.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtljtmxvnh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtwjxnhqgw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtghxrnply.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtlrmakakp.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtnrzlueew.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gthuoecrqx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtjmqnjsrb.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtvkymsozk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxmssstn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtqilmxiys.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtiinmmjlv.html


<!-- 参考信息 -->