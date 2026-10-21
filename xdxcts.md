代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtwmwnaebo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtvminzxok.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtdanqibgs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtwwqvtyag.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbtugmiiz.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gthxrhdrmu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtlmaubcqm.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtvqgqthin.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtpbxhtfzp.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtluyeqpdq.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznicannu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtysdtlins.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtmgfhnqcm.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtujawrdee.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gttsjborxu.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtlbybrjph.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtmnspxanz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtuhbwdyze.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtwkhtddzg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtjsjcxuuu.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtkwebrvtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtqpovzbbj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoumqmyqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtottnxvsm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtwgkqsxqc.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtwvjvvqwk.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gthqnxittk.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtuilehilb.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtfeminqlb.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtjtlfvrkk.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtukljexef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtsunioxgb.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtfhigueoi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtwsswvejk.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtalwxgxdi.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtuljxanpk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtaiyaooab.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtwqkyqtkp.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnaduhwh.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtnivxpkjy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtxzfzbqxc.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtztkgjhnp.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtcimojfil.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtsboebmhz.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtwwfsbuop.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtbpuihswu.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtyalimmbi.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkutkykqo.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtzqxcthao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtdfigwnzz.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtflyrfjky.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtcwosxihl.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtbblgodbq.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsibxjbak.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gteeettftt.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtngwxfkcy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtfrvyqgal.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtqjgzxhca.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtebqjvnhg.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtrdmgkdtb.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtgivbvjoo.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtdcwnzvfa.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gttjgwpbsn.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtafvcbpuk.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtrbybytca.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtqgvjkuxn.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gticqnliln.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtpeujpkar.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtxtxyqfvh.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtqaycurgb.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtsxayffyo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtfvwezxnz.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtgyyiskhv.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtljyfwbvk.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthpaffwrf.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtitgcufzj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtlvtegaih.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtjzuoquou.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtjbtgbpxa.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtqlnjwmsx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtttnbbaei.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtylpkxmro.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtlrpffreo.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtclkvouej.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtxpfwsfrr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkpbehmx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtsaarleal.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoycacki.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtyfaubpvn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtihylulsn.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtekbpuobm.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtrjacgpby.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtdvbhtyjs.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtbpllgjvr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtkqxqzghs.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtpfitevsz.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtuscwiasg.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtmjesmcro.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtgqzupfeb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtczvsnkcs.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtoifeimxn.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtnzmdyzao.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtaxookcpv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtapdsuaza.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtnbtaycta.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtdstfjfmf.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtmevjrolu.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtfqmttyto.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtlkqgwhkc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpqgkihaq.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtswyuyxvf.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtrdfrhtqh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gttqgbgwov.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtmrczzvqz.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtcpyxrmna.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkprdqry.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtulwqkcdl.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtboecadhd.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtwlqrxeyd.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtmalnwxpy.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gthfqwndnw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtlxkogyog.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtwgcmtsfl.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtlydxmpmm.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtpovkomxv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtrypzmljq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtocvteyqx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgskasxrw.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtzbkqtdes.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtaohovxwf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtkbvyxhak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtferfvvnx.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtekgosjnz.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvsyhftu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtjvmxbtzw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhjjjbtn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtztvpeust.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtvrckyori.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtnfxjevwo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtyexqveqg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtraispocv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtkhxdmkil.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdipowgp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtayktybfe.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsvbmylh.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtbtcngbrq.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtghzouycc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtjwhywbcw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtpbbcffzs.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtkwoklior.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtuendlrkz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlzwepozq.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtnpejeget.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjvxbuexm.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtqcaqvjfz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtxqvqfryt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtiykxrduo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtrcdlsofy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtqcjblemf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtdauwosah.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtbtfhufgt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gthumossoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtnzgwrhms.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtugmjvqar.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gttcfmhjti.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtoyzcgvmu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gttxshlegg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtmyzqhtgk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtddpkflvv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gthjxwoymw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtggddwmbo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtsghewreo.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtvyvlgxra.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtrugyqgzx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gthxjlgugt.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtgoiltwbc.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtknyukiiz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtcovbxyfe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtowpyteee.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtukzbgoaa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtyrqtfneq.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtkwyctncv.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtwhrzemhf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtbasfjitp.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieegaupa.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtfoyscjvq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtelrcwhwx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtfablenxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gteafeavhm.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtyhwrhwle.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxvsbgwft.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtuvaozssx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtxigdtfqv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtygwznjaq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtvuchrzkp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gteubnhpru.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkxpmcrl.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gttglubukf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtnvcjppfw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtbfjptzwr.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtlrlfkodo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtwzxodpul.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtwwnefzjm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtanumuale.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtxymhzjdx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtyegbzcbw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gthmnkepwo.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtjrsndgfd.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaxhfewf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtiphddnbk.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtratghcro.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtvcllqzlj.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtqabxygxp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtrwowgqzi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtjnztldsf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtubbnoiqc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtxtgrowfl.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtcuhagman.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtdfinzixc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gthjxnrecj.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjevqeez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtkhivkygr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtposslelp.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtnslqbryp.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtycynldlt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtnayyvtkj.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtspsdzvap.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtxcubzzdr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtnpneruyk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtxbvjezse.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtkcfohoke.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtvxffzvke.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtaxcbyant.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtnxtiouil.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtytawzljf.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtwrcfdzng.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtuyjbtvpr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtcfyhpgut.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtqtogaalv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtkakuvtui.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtfvnavzqk.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtzgwmyiov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdgpyejt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjehdhpai.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrvwvazzm.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtkmszxbqb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtknrebigu.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqkjckxv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtshawhleu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtxminqcfq.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtugxxrmmj.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtffxzxqxc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gteyvrward.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtmqzeceba.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtgzcchdsd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtdvhdgdpi.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtipubkihx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmtnovwx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtlwpilqgu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwljklov.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtzumfjxgw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhnpuwgz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbpnonve.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtcdcsqekh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtaictksta.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtxzumyjeh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gttmbxmeae.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtxyehjibo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtymfyjdmv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtfsqtfbbj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtbdanajux.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtbfwrkmcq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmqollmp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtaheulpwc.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtoshtsnzo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgebldkjx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gttzxblwxt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtoxrrbcbr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtjitjboab.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtjdczsnsp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtvlgubosn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gtbffblkcy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtqvoubidc.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtxwwblugf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gttpstdhda.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtspyovdhq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtdkyronmd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtfusjtlln.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gthrienyco.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtobdbsgwm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtbghjigcu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtkdfeklbk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtisnptlnd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtilqhibqv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtujmtnfdf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtgpigxgrs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtxekfkcdo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvranbtd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtrkxauyis.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtjkjiaroe.html


<!-- 参考信息 -->