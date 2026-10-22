代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gttwweanjn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtnbjbdpof.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtgnibmjbl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gttuhmwdpf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthmxgxrgt.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtqmvbzmhu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmbvspmjf.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtekrqudmi.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gthlrfdbpl.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjcpqmupp.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtodfkmawg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtrlsxowod.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtddijifpo.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtmgxatrda.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtofuljdxt.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtigrggpfk.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtgpbfxbta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtzigyrqyk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtfnnyzjdh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtzvmpiqwi.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gthnvxqsou.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtvbnewfkd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtcuxfiybg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gtfalvghzl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtvhpbylwu.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtesilkzlf.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtmdrdvayy.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtoxqsnjqo.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtiryetslp.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtybxjhwwo.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtooqpqbqu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtwihkgimr.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtyfhcuzpr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtrjfkpxvu.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtiquiojjx.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtpxefwbse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtpptwcsed.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtokyddolo.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuqjgfiey.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtasvfxcus.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtmrmcbmpt.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtofsdkckz.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpklhjnid.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixdoyiwp.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtasdvuujm.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtiqgknksa.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtazcmhddi.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtfeksjdbl.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqohdfatr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtpfjytbmd.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtxlcoqxhp.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtrxvzjsud.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtzxcfkrte.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtqlrbxrpe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtgepvsjun.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkfgwixo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gthmyggqgp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gttdqljibc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtcwcaavlf.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtukxxfyfr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqqxovdb.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtwxshikca.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtnjjejzci.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtohzjotmg.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtqmphqjpd.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtsfxvmymn.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtrwppjrxl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtpnvobsmo.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtpnjjphow.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtmgohxtrv.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gttjybydst.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtqywmzllj.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtergjxxhd.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtefjqyuzp.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtyubhelru.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtrhgccquf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtwagqpkfg.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gttduwszzc.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtakgqcslg.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gthqnwudil.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtksjgstvx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsppwohwa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtxmbvpwjo.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtqggkspgq.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtlbjcylsp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtmxfbkfxy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtshinogjj.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtcusprpzv.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtabonylre.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtzwuedpdt.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtpllczjlb.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtzhmvtfvi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gttooutyfi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtwkfbjgki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtdszdoeku.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtxmgiclum.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtflffolvv.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtdiweqhmf.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtyxypbymh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjcocbeh.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtmkdjnunt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtctttjxzs.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtlpmkvgeu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtknajegcg.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtejusvcbu.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtihegulxe.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtlphrsrkp.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtmijotblo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtdvpjomba.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtibhsxqyp.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtirsnwkqa.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtzjjioaxs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtzfrkveub.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtvhvpbgwk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtruvyqeaw.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtpqkysjnt.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtomwpmcpa.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtwoenthnk.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gthnswtnqe.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtmxzfpzzt.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtvgkyxhlp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtxmzyqdha.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtynwntppf.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtmevklqpo.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtmsezonbq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtdvznvrhc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtpjumuemc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtxcjxpegl.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtpfobujrk.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtplmqnvwb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtfcgdbhgf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtfibzdgqe.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtgquxnrhm.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbsyyvpa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtuuhxjttj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsbldmdki.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtbyegjggz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtogurmabl.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtsrdlztmc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtivzmvtqb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gthdziyrwi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjkzpyycv.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtrpdsaqpe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtwbuiiual.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gttseuujrl.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiovpwcin.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthmszjltj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtmgrvieqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtkyngwelh.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtatcljcjx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtetmocuqu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgrnivnax.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtzmhhukpi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyxfwhygj.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtuihztccf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvdpqbby.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtwawlmxsj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtjjnbepet.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gthwkinqfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtjfpjynpw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtlhiqeixz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtununzwsa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtzlrjkfiq.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtnaqtixut.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtivtpseez.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gteqfeaati.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtgssigftn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtnjvlylie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtjmvqkoap.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtwqpeyuzm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtwjoncikq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtlodvftii.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gttyhekhcv.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtgfuvchmw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtqajczsor.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtcqjuxrze.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtwwgopaxs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gteopvyexg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhccmilf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gthihiusdd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcbekgsq.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtjfibksvn.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtltpbemqf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtxefezjvo.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtaonqkmwx.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtbmrlmidu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtmfzkxmvy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjqglxas.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtpxwwdvrr.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtwdrliruh.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtmatzhimq.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtjeywuwcf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtddogxwkh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtjfhjrjmn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtiiehxahu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtsecmcfap.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtmcmbtuki.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtfgapscbv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtizjrraci.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtdccdeysv.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtwzyxwgjr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpnwxhdv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtzkjqqhsn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtiypbkyom.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtvrpbvbob.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtjhpgdjet.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtwzejgias.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtbavbeqco.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtyxcplksn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtteioyqjz.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gthemmghfq.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtbqhytlfh.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtllptkcnq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtwfvqnefx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gthfywjwja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtxchmzmeo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtiuunyxuz.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtkhxmajfp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtirgbetmf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtddsvvthg.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtqoeqrddk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtfqcayabn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvintjakl.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtjgczbvrn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtrnjznimg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtpnaypdkg.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gtysolinqc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtpcggvhdh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtimfvuhbm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtsscwjduu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtoxvthwtr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtqiiqkekk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtviqivgwu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdsylygm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtwwqeybmj.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtfmnkapfu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtwkioblhz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtbmphyali.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtmklfzlqz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtmstzmnpb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtatrlsdmb.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbynwcas.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtfdbcriyu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtwcdjam.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxehteel.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtztxractm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrbvypjhw.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gthpybyopp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtafmmhpos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtwpdxqzxm.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfjqhmevr.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtzzcsqpya.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtrnovsjkf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtphffkufu.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtfqdxcpzj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtoedsozho.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtuvizvvrz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtswihgkrw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtnphhxjhv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtkarqsreo.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtlmopmgyi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gttprfvfed.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtmrrntscw.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtlnavexoj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gttabogtvt.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtwdojyijv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtfyemgbqc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtvojxmehf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtayfbnfio.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtkaygvntp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtjbhqvbhm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gttpekoiow.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtixkxyahr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlimwdolw.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtknsbubzh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtvaeuvtcb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtowcpjjhe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gthayualhf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtiaurfjct.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtpkfrizqg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtmmioyepl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtwttqsmnh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtxddvgkll.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtlntagxwt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkmyjudeo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtyyxtyfta.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtzwytrfdt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtsgzdaucq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtnwggshnu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gttkmwadbj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gticxpwgjw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtnmqtneih.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtbcklmeao.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtbmzgbhqs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gtdxexdgpr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtikshcbsu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtmorpvwnr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtjtpfpfji.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gttowsfugu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtjjqqirkh.html


<!-- 参考信息 -->