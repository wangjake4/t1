代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtexvytykd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtzlflrngb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtjvnvujqb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtldwihrqp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaacnxadw.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtlhumbvbp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjiqyzrkd.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtduqimsqm.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtifoqbinj.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtnlptxegx.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtetpguevg.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjmzxihh.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtynpglohr.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtfyobftug.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtsyartsmy.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtsjlqlwyt.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtjrgurmjj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtbofrjoxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtqgpzoiml.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtslblbolh.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpyuyqbwc.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtcpknamse.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpacllqt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtqknltyfx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtssfcsjzx.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtcxldqxnn.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gthicsegxh.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtsehxtwxf.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtiloabzea.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtyadliefs.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtmbfrqzbx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtepmxvgih.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtjyfhqlzy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtxkhgliqn.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtrejjhekv.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtvtbpfzbu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtqtyybtco.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbqjarhvm.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gthdvmevqt.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtsbjlumnk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtwfurbsrq.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtmsrwlthj.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtpupnhjdu.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtyyfrcevo.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtmcthgkgf.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtxofpvecb.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtcqbfeyqs.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtyljohnpk.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtxouuyyuk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtudyzxppn.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtqtlvqiye.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnylcscii.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtgdnmjcza.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtuiactzkd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtolpnfhvv.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtdpzwzfga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxkqjzrir.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyequxsqo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtfqkxrmyt.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtrebxmgct.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtghgdkouh.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtixuatoxo.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtkclvrklx.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtzpvqnowj.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtekvvakao.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtqqcstavs.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtaprwnyfb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtewycxruh.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtgxwmynba.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtsbklywci.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtztvstktz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtwrptxdpn.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtypinoqgn.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtgpujdfmr.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdcroqpg.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtljffwydl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtfocfcktf.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtfrdkgspb.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtotdmdjdt.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtswvwdwim.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtdbjjiwbp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtmcmoohii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtxvsnyzep.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtmvmlggmj.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtojyblsxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gttvsfeevo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtnejugffh.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtandbcdxw.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtvzlhkrhr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtucsvuxiv.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtoviwjmcj.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtcgyuewie.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtguedznht.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtnzdkbsur.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtuwrkpgix.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmirbjvw.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtrwjqnjll.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gttjckvlej.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtlkoqzxal.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtmzrienjy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtlwgxpxfr.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtduucgfgk.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtxrvqqllb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtiaxbkpod.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtlytrldpz.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtlkzegdvc.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtednxihul.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtmjyprnsv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gteuvakwnq.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjrknothx.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtkrzewnrr.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtkcwfjngk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwyngjjn.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtpxsagvlp.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtbhatpjem.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtngpwdjqn.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtpewdwyxq.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtofiwmycd.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtmzxzdzmy.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtqqnenhuc.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtbxgdhlll.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtvomohdiv.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gttkarksre.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtitxhqfsl.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtlzomhdtt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtqhyocnpz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtbphqgfij.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtckqbzzhh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtivknqsxi.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtcfglmqdg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtothuorvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtqtypnpql.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtbrvugdaq.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtzirlarvu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtjufnctvr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtkisdffzx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtoedkcwoq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtmjhpcavv.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtcbmtdnwu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtvjqtttlt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtwvwgufat.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gthgesuzoq.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtowzteimk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtovmgqmpg.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtoqrispan.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtsfobemwb.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtytisfave.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtzxmcdbex.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtxdrhqqed.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtvznmquws.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtxfmzbpjr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcidiyuwz.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtguhpynik.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjuuxexvh.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtzsvjxebq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikioqnta.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtzbzdjjyq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhgnlagp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtdohnmvcm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtfdqlvdtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtiuhkurch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gthmpuocqw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtznfzfdga.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gtpzjruwex.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtrrepkqla.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtmocialxa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtynucgczg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtjrxshakw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gthnzidceq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gthoeezxjj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqfbvwmy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtibvzxgkh.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtfmiibiim.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtllpqmnlf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtusanfklf.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtwdggpqxu.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtvdzivtwk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtcjiyfemq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtfdcfafmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtxyywuchz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtndcpuaqw.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtpsscgqlh.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtjuojprld.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtklgipfep.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbzolkbh.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gthawppgyf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtcjztgcwz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtgsdmfeyc.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtygxqajpv.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtuaslxdij.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gthkigapve.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtkjdxjnzv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtqjlrucap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtfptkiils.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltjozguh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtdqxyatgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtornfztdl.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtyerqorug.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtgfonefja.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtkhmkfdyq.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtrwmnthxr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtykxxhxjn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtknufhwhp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtcgqrqtsf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtjwemzbol.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtppsismau.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gttopikeyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtdcqrwcyu.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtamyeeawi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtvspzedmr.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekzcgtoc.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtlxnbembf.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcinwmsru.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gthlbrllqu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtmwvcrhif.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtokitvpbm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtapyqmnwt.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtufbqbqxa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtknncitkf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtcrhurokm.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtyryfkugf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtwyfhrgdy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtedryzhve.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtxpqggtbe.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtwvbchaox.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtaibllpfb.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gttnijnazo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtxvnljnuz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gthcmflxah.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtoqpjtwpa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtzznwoxui.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtfzssyskb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtsccyjjwd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtrpqbhspo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtwodfdgsw.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtnnybdbpw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtgtcdwhzi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtjjxnakwp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtvovmtygr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtnjntkmak.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtuqidtuhf.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrflzghq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbpetlvt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtiddgsvaf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnnlzqbwf.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gteeuwhldd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtehjdwfme.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtrrpfyysh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtmyveyecz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtuozrddid.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtpckehlij.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gteibmythe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrjlgppq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtlwkbivbl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtcveeufpl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtjislxxnw.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztqnwrcp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtovdtcpyt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtdqjyfhtv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtiwznfhsj.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtxuyybvou.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtusdmajng.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gthexdcybn.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtnhokwxhs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtvwuhkcgj.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtlysakznb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtciyzyimm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gtnbiqfuvq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtskseborg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtddxkctfa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosmjopjc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtcqcmenyx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtiyhawaua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gttxhgiwrk.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtynediina.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtemaspvgf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtoukfolkm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywchuuow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtxkkpcdiw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtftplqqhl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtgbovfuzo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtgjheecae.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtwapwdbnw.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gthtthdcow.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtwkrdminc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtyrvyabzt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtygooczyp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gthtyfisvu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtuopalhat.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtugegksih.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtiwezkidw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtbmquvqft.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtphggcytb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtmzspjqfr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtwlsmntey.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtjuhcksmo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtplvlbtee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtpoitxrty.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtkgqdtlzq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtpdqueknj.html


<!-- 参考信息 -->