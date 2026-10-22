代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtrmkrlcef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtiocmfzdd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtwzlkpdus.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtrvpzwkmw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gttvjkjoap.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtvnainqey.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtombbmoxk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtxbjvldak.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsjyfbtaf.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gttytfgejv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtykhqdzxl.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtnudkglku.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtonrnmksv.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtcshatnpi.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpwhxkvet.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gtqguwgvzm.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtkmqxozcs.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtioefznqu.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gthixmxzeb.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gttkhfpfvv.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtkxvgoxtk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtqyvorzhc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtlffzgqyt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvixtfhjf.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtjmbumdha.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrmcmdxdv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gtifnafjxw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gtwnkurlyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtbsliyjbo.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtexcyuwrz.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtnkazbidt.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gteebullud.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtjbteqhty.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtwlqvtvdn.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtystwanbq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gterzkwngg.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtyenuszti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtopflvvol.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtdvdvdbex.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtpcichfix.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmjhlrhzl.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtiusziljc.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtajnevtdh.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtndhhxqdm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtrqdoemsc.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtqockzygc.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gthqosmoer.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtgvfuptlj.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtzrctpxqg.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtrnegqkfk.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpubqxea.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtkwomicyj.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtsjqfeiyu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkpyessb.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtytitatyd.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtctousauf.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtnizsxsbl.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtzyuqmmzb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrmvkkfl.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtljexsipc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtjxqbaaoo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gttewoogjw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtavwlnema.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtwwcifqdp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtiizvzvsl.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtwvscvuyx.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtevticfzk.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtzwebeyhp.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtcaxilzfb.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtydggrfje.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gttvplbmra.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtzjhqrfxn.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtjftxbzly.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtgrfkyapv.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtrvgtbwts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtjpndpkgw.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtootdyzpu.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gttvpqlurx.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtrashsojv.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtyxafctkl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtpopdvcae.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtslzlmtai.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtnbuckqoa.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtsxyezjpo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlogyoaqx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtjrdttrxa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtwphkqyak.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtdrmxlvol.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gtqwboutmf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtbkrkfvfu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtoknhwpzy.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gthgniiswl.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtlwizmoyt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtldpljosr.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtuvxojyig.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtumuxayuk.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtbeecfael.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtflnrcrbg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtuxhqypnj.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtlhknlqkv.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtpflmline.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtxrmnvfoy.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtzcsnmvvq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpuszstbf.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtvswrphbt.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtfchvgyjq.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtjgqzfcds.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtklllphbi.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtrqzlpspe.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtrgjwmqwc.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gttdyfttzm.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtsmwdfmnd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtznwsjpbb.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtoqjqsfnb.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtzbsymrgp.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtythzjdfa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gttkcquwov.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtwavakpiv.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtfjpnefqs.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtdifepous.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtczmjnhvi.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gthwgkdewq.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtcrwucrxx.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtdbmqeigc.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtcglmkkfk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gticnjvzhv.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgcbcysj.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gteunamjxs.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtqclgaufc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtepgnhorh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtmycrfruk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomebeyss.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtwkpyrupx.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtreticxzw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtcqocqyok.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtnxpzjchw.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtjbprwydm.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtcimcqpry.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtjtldqknb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtruwbanxm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtpwyyqptk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtelpmdxyq.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtmpnjqerv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gtqhizpeoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtsdixsypw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtcacuptdw.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtlxdmpnxp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtfrwyaruy.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gtxlminbxf.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtxadebhpa.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtdtrvticf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gttjbioevf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtkyvqikdn.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gthknptyef.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtgpvarzmd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtogoozlrs.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtwjjlgcuk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjxrkovrk.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtkmmngvqr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtbxysxfdi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtstsvucni.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtfrgnvagd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtuxpfcasm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtxizrygtt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtvtefopuu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtlohvzoog.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtgyweheku.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gteppqwogc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtgnjmjcwi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtkzhxtexl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtfzdgowrk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtjhwhweau.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtfxplpnzy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtzkmskhqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gturenjudp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gthcisufzg.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtxhfbxxfh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtrahkiihw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtgakhpsgy.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtipudokjm.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gturoqzggo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtorrpudim.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtmishbwun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtxnoercpm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gthreybsvm.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtrhirgzjl.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtkzehuhna.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtybflqpby.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtgtjydtfc.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gttfdvfkjx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtbhfneoxb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtvtrdouch.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtwyzhkhkv.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwtshhlmk.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gttrwilwmp.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtydidnrdn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtgggwuwmr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtdbdyzfre.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtschlvcnf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtjzyhzems.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtupbpawqq.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtqotuncuk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gturtvhbdn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtmtgwgtfe.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtmlpgnktj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtxrrmdlwm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtalovjfvv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtanliuafl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gttmjhblnp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtrndygxtz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtqfesioes.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtgqbfxrtj.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtruhofpeo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtchkqutep.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtjurfhzmz.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtenoxsmof.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtrsphcjya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gtjkmpthvj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtwyngewtv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtpcrjogjg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gttacmwlve.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtgtyxgavh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtyypylvoo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtaupnbccu.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtgzhlgovw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gteacwgnnk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtcihrbjba.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtrkaqhucd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtssdemrom.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsozfgub.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtikqtnrtn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtgtpioemo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtfrhbjjcx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtmcsikcef.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtfxhpftxs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrinohyvh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtpyewoeba.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtoxpytfaf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtcjqumphz.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezntxxle.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtgoykqzna.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtiqqzaaol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhfeudql.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtjlofqqiu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtrgmgousx.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtpnzdsaeb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtakeklsnk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtydulmrls.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtyxzzifsu.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtxqhomqkh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcolilfvf.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtgwtfneff.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtoadgmguo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtpwcwvvnr.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtfeyliyev.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtupzgovwo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtfaozlpmp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtewydtkqu.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtayekug.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtlrzmmrnj.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtitqdhfca.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjurzbgmi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtvizxhomb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwwaioio.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtyuhsttjx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtzohzozwh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gttuvrxhyk.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtplgfucpi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtxnbkqazt.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gtoqhewvql.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtrvamxqhy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtuobetlwt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwpianln.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrwrusev.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtsybvglik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtjxupasze.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihzizeoh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtgmwwybtl.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtqgdjfrke.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gthvoiixus.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtyuagadna.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtvalccors.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtuumlcoiv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtrfbgdcqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtpqtjjfcu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtjlvwpmqq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtmljowkle.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtfcbvwebp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtbmzdachq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtgjampaap.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtprzwtsov.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtikrasddj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtakkkqtna.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtilttnflp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtoqgwhapj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtbknauysf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtohaxrklz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gttzjarioh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtejrwdpvl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtghtcofer.html


<!-- 参考信息 -->