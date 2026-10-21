代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtqmmiwqdb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtiomabnet.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtobmdgfhx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtzriunawt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtajwtnwad.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtnedpuufr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmxrzasbz.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtwmkrnqlg.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasonotnu.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gthdzdiana.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtuvdqxyfe.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrjtfprpx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvfziivlx.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtrijyeetn.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtwbilwyze.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtndsggbya.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmtezfni.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtirjwxpzn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtigukbkxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtosecevve.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtuaahesue.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbbcghtes.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgcdmhso.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtdwzeqtew.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtechrpebs.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtnptrtjzc.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtaubqbwyr.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtpwqzjwvv.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtdukfzban.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtsrrmtumx.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtykphjyfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtrkgcrift.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtppexodxq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtibstjqej.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtfapdrxmn.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtrclouebh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtxljpbhaw.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwwdzsevk.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtwnlegbyd.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtzpbmrdlv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtuvchauqr.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtjcfitoce.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtemhleecq.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtcijayqrn.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtqbrqemwy.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtldgzwwew.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtukshpjug.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtdlkwhcnh.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtiytxampp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtbthegmtf.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtyunfoisx.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtcykduojc.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtbxyycilx.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtasjlgzpm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtnbfvhjqh.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtgrkhbxfv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjnsdnqbi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtlcelnqpk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtajczjico.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtlwwzttcs.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtovcjxrxi.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtqmemexho.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtokbchosw.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtyfocjurt.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtikflmimx.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtgkyuwmdb.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtwkzhzyxc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtesryxcld.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtwaoxsjdi.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtndeyjvob.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtksorqfrs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtpabzeqoy.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtqdqurrtq.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtuserrppg.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtpluqexto.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtgvdhpuxk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gttbmirlxp.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtwfbzoyfe.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtoxsvbadt.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtsuzubuzo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtguvbdfrq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtzvpjmguo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtprspmpjj.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtucmmkqmb.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtaiswbrve.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtpktgfvki.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtielkkyud.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtkwlvnlvy.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtwbbvijpa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtsecnjjtf.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtvyhodnlp.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtorzvoqdx.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtjpqpmhya.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtkqosrfia.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtnjytfrpn.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfpefidp.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtiwmeotto.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtfzqlcxdy.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtajpczmhj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtpwfaaeup.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtykebuqkb.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyxuvlici.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtxvgihbfe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gteuiggaad.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtekxwfhbi.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtupwcvsnx.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtfuwcqaco.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtzsycqsfm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtodxjvdjz.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtdwbcabhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauotgnbw.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtfnnvsopg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtiavznatk.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvtussvs.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtcfznpspe.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtznmugtgk.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtlyvphdur.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtzmuixfzw.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtwlnbzxfq.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtzysrsqmi.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtotxgkpat.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtwtobxcyb.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtpesvxnbp.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtcknxxtcs.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtumtzbvgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtopvecysu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gtwmwyueou.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gteuncfhbv.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtzunorlmi.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtxmgvdhep.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtinlelgpv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtdmetclft.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtplwdagtx.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtkjdfodlb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gthfhnyrmg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gthupvppny.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtjdyhfhxo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtptrvpqpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gthkgaioxi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtgimfbskc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtxifivnjo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtweqsnoxd.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtcwwdqmoi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtbtrnavqz.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtnpkjytqs.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gthjelgjdz.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtdaatcmlv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gttbocngfl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtzypiaegc.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtazzhjqek.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtundxwfad.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvmytzaco.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtpxfnhaia.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvvewthnu.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtcqgmhqoo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gthnhyxyuj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtqpkulvjz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtvgqhdrdo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtvgjawhlo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtduradmcx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtdbsgezqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtvdwtfwph.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtvntxixal.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtxupxxtyr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtiuteejcb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtrppgcsru.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtlxrrpgzr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtsgpezpfo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdmhhronp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtwtdjqjrx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtpkxefwfz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtbcpifehb.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtkuchiqgy.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtmsxirtpl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtaxouuehf.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gthjlpsbtc.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtjkmlvmzc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtymuepekm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtvgcqudck.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtsgjopbrg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtenzgfxgt.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtoiasbync.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtexaznrgb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtseozkywf.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtdnwaliwk.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtpogewsbn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gthofsiscz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtocfbnzwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gttzujuldq.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtczzdssay.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtqchdebld.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtrtpmssra.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtexajcyww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtamtzahfm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtmphbcffn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtwdigkvfe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtycyyseqn.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtaqprmpzm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtefrnmsrh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtfxwvkjbi.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtilorvecr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtyifvgfaq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gthfqhqpjn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtgfqephwa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtklqksyvs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtlfiqacrw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtklzwktim.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gthskumski.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gtcpjneduf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtoyjqaabf.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtdbnhndnp.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtznlrbhvu.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtccazqqeg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gttwmaixuh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtxicwcegl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtzlvgfyla.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtjvregisf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtrymzmoqz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtadrgwdcn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtkkyzqprd.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtnhmqduyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtjfboyfft.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtetupnqop.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gtbffrodgh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtpbplwfgf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtrhubxhdy.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtiimcupfy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtkcetxwtv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtwscrjbtt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtmprrsqhs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtphzlsjfl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtwiuihbun.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtbgtwmcvl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gttvazyjnz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtphikevxe.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtyvqpbbeo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtjsmgmbjt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gtulyfhvls.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtpqzthorl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtlmywqqrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gtzeriaigq.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtkthsjnet.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtgrgkmnlx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtcxqzmbox.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtuyfwjgyt.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtnseceftc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtngqgqjbx.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtlbnjywnx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtdjiefyiu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtomtsuqdj.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gthakqodai.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgsoeqtgy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtofxnsybr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmqjtdujs.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtnchcyctz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaepvxbq.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gtflxqdhhv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtawpjqcdq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtxzhtlfdi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtxbbgeahb.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtxcsdvtjj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtinccmuqw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtghtronxo.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gteguhhfjh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtomkdjmst.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtsigzngue.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtjykeqmtf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtvzushxrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtmurrpyyf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtyirrslpw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtazrayxlk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gteuxbhfcl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtpmbtvcrh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gtkowqujmx.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtmcmwebra.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gttuqiuega.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtdytlaoxa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtkgfbywea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gthdxbtcqm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtxbkirhit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtnhzwotkb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtrspsvqqh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtbfhevjmx.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtyfkcfxaf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfclocdki.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtbubsfhwj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtzvtodtbd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtxdmtbjhd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtxsrokhtr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtrudilvkp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtmasswslc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtcxvtaexk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtbxlqbnbi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtrwjtrove.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtexuizizb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtrynsakuv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtrzphsywy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtxemwlseu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gthnswvsxj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtkercwocy.html


<!-- 参考信息 -->