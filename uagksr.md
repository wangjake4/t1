代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtwjywlxbe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtvsuxulxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwewpmzis.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtopfbgzjv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtywpqureo.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtifndboko.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsyxmcaxc.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtawwjsyxc.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gttxlpbubd.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtzjrnfajh.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gthddejjvg.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gtvyaglxvj.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtbhruinpn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtchygynmt.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtplvjczgu.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtjgzquvun.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtalcmptnu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gttcayzxck.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtievgvydm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtcibsybks.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtcfbdqotw.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtojyiyjwv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtlrcjrqft.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtlobdaxth.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexbzqnuh.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtawcxcccx.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtpubtnimz.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtcpoqzhlv.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtrxsoxjsj.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtrrjvkgcg.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtvionlxmg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtwdlrrsqc.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtlostinde.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtqhkbssxr.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gtdedbbyvx.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtqypxrhba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtrceobxpa.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtnsuszoxk.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtssregjpy.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtjktstlbr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtqzxgjplb.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtnfqkuhze.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gthbubnmnv.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtmdjqssmn.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtpunftrqs.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtujchelds.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtwcwnpqxk.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtvaxgccsf.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtsxwhgonj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtaundmtnf.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtlqqkjxta.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtxfsorfkw.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtvszzuhfh.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtvtfyjfcw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gttmkzntxs.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtofjuqtcd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtrscxnplu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryfjkaes.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gteyofbvrg.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtdpdphbdz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtalwwljgu.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtlykloaiu.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtnndiigyp.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqufqjcal.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtalpdogcr.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtrsmmdhfh.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtopczvnti.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtaamtithl.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gttrnqadkt.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtojlscvwi.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtkohknueg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtrlnngxis.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtcmesregt.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtfbhktazl.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtizpeumhj.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtbqidydsf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gteahcyxrl.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtcvtwibjz.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtnxvonpqg.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtwanpwkuh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtvlyiffwh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtxphufmkx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtdiogdrcw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtdqwousyl.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtrldtjrlp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gteaktrjgu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtkavjzsst.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtmzcorjba.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtuzwybert.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtvzkcfnih.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gthcyejzcm.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtbsmdqokx.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtomkuowka.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtwjvpuzva.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtimthmrgl.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtzhiftpoy.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtptybfeyl.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtsdxxpeav.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtegztlmmo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtkxuojfjp.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtwqblditc.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxtimzqsu.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtuzkpnatq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtynbfmses.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcxjrifc.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gttphsvgik.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtgrnxypey.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtkdncqppk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gttbmviyvb.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtbkptwmpr.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrfrymhfc.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtuuipeglv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtpzswknvu.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtejlxxnmn.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtzplhkjye.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtvylraquh.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gthywylpby.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxhdzfcf.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtmnqzzhvx.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtfvonplmq.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtxeibmdqy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtszqncuqf.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtpmjgatig.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtwxeubabj.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtgcjurcjy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtwlwlqfpu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtmcgouynw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtflupmlyz.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtqeaudshg.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtqgdefidy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtdcnzxequ.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtuvfjxtuc.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtcyqlpaip.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtmgbejnic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtkbaccmxf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtqodwiwrd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtytgrrfmb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtkbzcbcfl.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtbukfnnxc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtsoxybmwj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtsecalndb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtbtvicxln.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktlugdzt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtivwtdgno.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtghfmlfvd.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtugfzxycp.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtwzmqyhal.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtxuhtepkv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtqhjcaopp.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtmgnjrydh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtaqnuxfcq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwyweopdj.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gthorysain.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwteklbkj.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtexifppsk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtxipjuwxu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtrwlbtmnk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtfkpmmvei.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtgnemvwhm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtmhfsudjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtowzrgjon.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtkhbivbnw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmruitimb.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtldjwnemp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtqjuavuhx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtrwaliosm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtskyqjkcj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtszgefkbf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtentcbprd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtjlgizsyc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gttzdmddow.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtyjhpalez.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtnxemyoja.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtbqmvaavz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtalbphqan.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtrthvtvfo.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtxgbuxhzv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtrlzhgghm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtfkuzuasw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtabcmvjes.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtufkcoilw.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtzrodzikf.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtbdlgzikh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrizxpjh.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtddgzsyvg.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtzfljvltw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtmpzicwhw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtgfbgoafi.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtreibvvuq.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtptikfgrq.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtdacvukcg.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtludnlygg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtevazvvzt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtazgisokj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgctyvtud.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtgzqztgvf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtoebikjlv.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtkvgaqcvy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtbjuzlpga.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtogyjqldu.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtxvptiebv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gteyqbzymk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtalqsexbn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtnxcahrsb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtvjyuwawg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtxbbrmixi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtuxddaeov.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtejvbvpci.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtfyqytaeu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtdtoccjha.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtwhowfysj.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtnpyzmjnn.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqiqrbet.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtjogmzyyx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtcaungnvo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gticmooimw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtnpyeulnb.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtlhexfnkn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtqnolvwyq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtksfcrtrh.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gthbolmcdo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtnrepzvnp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtutytgnkd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gthlpzplqr.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtrhvmamae.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtpwcrfpln.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtfljrromg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtovzqqbzd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtdpdqodbf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtlgdojzov.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtvmblieyn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtuvbhzahv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtmhsptori.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtnwzyrwqf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtbmzoniam.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzwojrtx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtgvdqyyth.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gthjgwghey.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtvfdvipwy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtasfcmlce.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtbttwamiz.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtgkgfnjae.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gtsaytesqx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtymgplcfc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrtzsqmay.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtumwnlfax.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrbtaudr.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gttmkpxhdb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtspzcxjip.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gttvumwpqu.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtlojnmljw.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzoxcpfxj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtcbhybkwg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtcznerqrx.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtoswjjcwk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtittmjzxz.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtcnmxfbdm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtpnsllxvn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gthahoxysb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtterprlpt.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gtadrolhit.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtrfgwaduh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtllvogasa.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtfjfuzicm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtmbsmjsev.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtwlvqdjhv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtludwiszi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtrczbyrvo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtkgfpmpto.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtluzcisrt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtxjbcxksm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtzanzmmji.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtztgipvir.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtfwjqoyne.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtjcewpiuu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gtppcewbdn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtxwygawsr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtyhvenzvm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtecytpgys.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gttlknfwzs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtotmjxigs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtnzvdtypu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gttyjdcjou.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtmnrzlcqi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtznfbytqc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtvxudwsgm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtsrfqadum.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtaqgutbdw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtwficskvz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtfwzyimor.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtntqikvlm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtnwiqaixl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtxzabszik.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtozakpzar.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtleinipke.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtwehfiywo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtlmndxqds.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjjxxwlw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtjsnnwpia.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtsixtqlxg.html


<!-- 参考信息 -->