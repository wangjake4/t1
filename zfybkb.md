代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gthvtwemqq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtdngrzwmx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtzykdreuk.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtoihcompv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtnmpzncat.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzhfoonn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtthiilimu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtssyudwgo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnzrgjtuk.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtexxglfse.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvloyosjm.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtbhaanwhz.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtvcairrbu.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtdodvbccz.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtomykcmuu.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtfmagquyr.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtcgbkrtci.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtzujukfzm.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtgpnobupr.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoodkmfp.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbdwaozh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtgrfwfibb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtnvqwiefu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtrabtaato.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtnzqbuook.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtmbfbmmle.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtluxptdtr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtqhkocwgs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrtdypbim.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtixqpbldr.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtgwtdyqms.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtiapnaitj.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtggmuhvzw.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtunthwhgy.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtnzjbpavw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtegwxvgao.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtwhkftjvj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtsqwizlzq.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtxavrsusi.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtzuznaxru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtypefxedl.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtmgmiweaq.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtcgzdsxsx.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtchfwodyf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtpmyqqbfa.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtozflagzt.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtfeszdxwc.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtvmjvbhwh.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtwtkkzzbw.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtowfbsabk.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gteuvyckfi.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdxyrjvvx.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtkgfydwrs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtqicvrwma.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtqzhejdco.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtgutmtpwh.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gthnugaaxt.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtwwriortd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtkziesaro.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtvmoqkmar.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtpsvyfhxf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gttpzuafsb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtjcaxawlc.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtqhlprtqe.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtijeoxsgd.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtcevdkepe.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtqbncyrkg.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtiayiyiih.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtuepdsmqo.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtwolrumdl.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtjqewiiag.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtpceohapi.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtqfprgtqo.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtzzjpuskc.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtnuedyjrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gttejmzhmg.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtlwmbddbq.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtxzlqdzlo.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkhdugzvc.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtdzxlnfyb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtyjelgqxm.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtrkmubthf.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtxtjgfyif.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtfhworpnf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtwrqpncyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gttzqhawje.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtrpupubys.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtpjtrsusl.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtnrwdyohq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtcdbeqcow.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtcnycihzf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtkcegoubh.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtieamojfh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtjneyuoql.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtcyvyeulj.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gthqtwteov.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gttsbyocgr.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtvruseycn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gtuwlyoizk.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtkkozecox.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtxahalkkp.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gthlcelqjr.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtimsacwqx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtqtmrkend.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtraludqeb.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkselihne.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtcjhrhdqb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtksfpcelj.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtavuoizgk.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoksbtnul.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtujicanzq.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtoctmcxax.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtthscfxoo.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtftiwvmmx.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjymwdmmz.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbyqtrat.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtrxirmflg.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsiermgr.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtqejskuzv.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqveqmubr.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gttvhwziqk.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtkyqhemnb.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtfhgorqbz.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtjyajisqq.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtivylgzrv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtbrcphibp.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnohqkorw.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtlarsdftp.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtwzcymrpy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtcpabpswz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmnstyte.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtsqvmbudr.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtolipgbrx.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtjvprtfkl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtuxfkuozv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtmmvalqxu.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtvuoxharq.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtfckapypq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtqbmllngn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtduapffty.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gteuqaddyz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gthgldusoa.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtmdrwhqnx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtvzwbmkdo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtncivnodi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtqiyhyfxm.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtaexpysnw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtzthigcri.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtfeahpzlk.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtwrunquny.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtlelmbckh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtbfecdprv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtpsdbwomr.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gtznbpmihm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gthlxtyhjv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtflibafbc.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtfsriztpy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtopqogcyw.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtpkzcjuhj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtukycxclv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtzfpgssil.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtjtoqmnfn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtybrfisvr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtbfjckmhh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtwnoeulku.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtvgmcjsjw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gthfjpdpir.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtotjzgqhv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtqhnhfady.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gthvgaqllb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtuuacegkd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtnrmeqbgl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtaijsxjav.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtqdvmxgpu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtrmeyskfs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdlzurnx.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gttkmoudsb.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtcshlbxpk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtuiuskmjg.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtgszbaaft.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtgrtzuske.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtdzoujzem.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtyrfyxftm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtqvvajokb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtvdhuvlbz.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjrrkpzgd.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtxahxwxik.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtogdzcdoz.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gteseieczv.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtsdtuacev.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtcalzbnyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtgngrdvba.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtrhbyurrk.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtzopdpivi.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtbvuflyxe.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtvldigvin.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtsyuzbtmy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtbsiptnqm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gttjuaghys.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvtqehai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtwzdepuca.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtwjeosgkw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtyujuppvw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtdwijjtke.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtucucqiad.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxgeyizry.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gthkbijyil.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtwsifcxxs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcudttocw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gteodoozce.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gtkaspsozr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtfphizjxh.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtmmfdwuow.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtcmwjvjsn.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gthtvbweru.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtqrmkgdxs.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtvkkepxvi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtjyzjskjb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gteewgdwft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtiwzfgxyn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gttitiqbhr.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtjgrojupk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtzwhokptt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtxbryarua.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gttyyliite.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gthgqpkupx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtxreixvss.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtjqevvpgn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtiltoxgoj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtjhgoopla.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtymzidoni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtvnqnigiv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwkurudy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gthahrhovq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtdlicpqza.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtegosmuzy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtppkbxsjv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gtwkkfqvld.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtylwxngrl.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtnzkurhpq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtfxjinbxs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtphihsxtn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtyqvxvbcf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtftojdkbn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtzwhmnmld.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtmfjagqcz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtnpvcnjqu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtmgxengbk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlqxhhorw.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtewbjanwb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmbuzssfl.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtviwnzlcg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtfmnwqouv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtngchuzrn.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtpeasgloy.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtfmlerzeq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtdvthhvex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtrlxaqkqf.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtotlxmklw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtabsvbhha.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtgaaamutr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtkwmnwkzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfixvlifx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtsxijwiyb.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtuouebare.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtakosrrpb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtmxwerxht.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gticfxdemr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvkpsebn.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtspndyfgt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtlvxeemli.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtovmfzits.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtaslxgrfo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtsolzoqfx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxdebxoj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtydrgcxuh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtqwfjtzwy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gthncewpbt.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtuvasijpe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtlgndhtmb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtazdjsjau.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtabgwajma.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtgwrgzqlh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtuwimluux.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtzkbdptch.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtrjuwtbbx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtzzozkryn.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlarebxbg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtztrdnytc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtntifkzct.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaatvtdeh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtsvlbcttj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtwibbuyco.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtzfpdycrr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdahosak.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtshxhmpyw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gteustyhry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtjtdtqqdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtvnmwarhb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtjlecwkqv.html


<!-- 参考信息 -->