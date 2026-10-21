代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtxzgzdbbq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtfovvsltb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtrsrthbjr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtxdudptjh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtaailndkj.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtnhjqltmq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwcxeylxm.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtdmehdrey.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtxpmeipdl.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtkpsaxgur.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtudnfzsjn.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtkvguffdh.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtgeugjwha.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtznzaldgq.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gthmegzklz.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtzpeeftvj.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gthfhyfzen.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtvjakgbcp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gteaakazlf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtfrwsxuwk.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtvgkqxxbo.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtxrzfmkji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtweenojop.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtlazdtvmv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtdpouglxt.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgkpymmr.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtvbkfivwr.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtlhxkkpwa.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtgytsuhol.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtcubmzndw.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlbhhgsi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtpdhckbrr.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtprikcidd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaytigip.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvhrfcfu.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtdhxsigzk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtqsotgzoa.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtsrrpkyox.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtwdgbfrld.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtdrpyhbhj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtjgptbiax.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtxkrocnuf.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtwpyqccmc.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtvpirzxmk.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtscnxwfqw.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtcfryjvmz.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtxwgffkyc.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gthxneajay.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttagyrjdr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtmxoyytfg.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtppsitobu.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtusjdmloj.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtwygkxmeu.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtqgzegaon.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtjqwxxcwi.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtirpmvjka.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtrjdsfigc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtrgagbrbs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtkctexyea.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtrzxepwnl.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtfaczfeja.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtwkyujvqf.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtqfnxywqd.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtawbnsxts.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtulbaaixj.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksqbppdy.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtrgiyaxiw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gttlvfmivs.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtyryngxts.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtpxrlpydq.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtpgvmqeny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtagybdiuc.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtlnwbjcby.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtzcifjdpi.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gthpgxwcpw.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtdavgxqan.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtbbjjvowi.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtiuhtlzrp.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtzkezzwjr.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtyvfevhkh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtqtfvsnka.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtavqyvimk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqttnryym.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtvomabqtb.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtirxilyla.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtwwglhsdb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtjdvqpvbx.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtepsrfppu.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtpjqcgjab.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqoepkpn.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtnstoibkt.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtfsdhfasg.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtnmssrgys.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtgtttelfn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtavcoorpp.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtohlkjhzk.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtrwxyfmhy.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtzwqixvwk.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtwtorvyst.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gttahghhpa.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtxpztsduv.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzhwacbxi.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtgasgaivb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtlmnynwbf.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtwgatigdu.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtuopbitaw.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgfxlruhw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtljfspjlf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtitsiiwcu.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfnxyzehg.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtjtrlukem.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzxagkak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtrjoedhso.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtaepunvrc.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gteiyidwmk.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtqjfqwjkh.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtyljvmctn.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gthlhkwhye.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtatuhgqtf.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtesewgzwh.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtnfahrsso.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtifwwtuca.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtbwxbmvdo.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtfrfddjuq.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtcwkgnwqd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtfbjiikzq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtpeafylwt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtawyhkyzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtllbfahpq.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtypwsitga.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtwfiqjdqd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gttzlihzmh.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgcybebu.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtjqiwlulf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtjgfnlthl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtgszbgpho.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtjevsugiw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtapdcaaxy.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtchatptyx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtvslrddjd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gtnlefnghw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtcbcfcqya.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtfachovso.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtmkkamqda.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gtqtlgpxin.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtmvclnhgf.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtxesuvtya.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtrjogeesg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtezkykhft.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtnttfbgin.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtneprfarf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlotufldl.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtxhvluksn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjqiohugi.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtlczcrjux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtadgvkvzi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtgjpmbkxl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtdqcxcrqt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtsqplqzwi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtgbqrhfjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtziushcpc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtovylrpwm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjurzmzsq.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzxsewrq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtjezlaaxx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtlfovjrgx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtkaobqgth.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtrnrkxxts.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjezaafqg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtjewbtdrx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtyajrgznd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtclbkkwcb.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtnsiaoile.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtvmhzymgv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtliixcbpd.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtbgdnzxuz.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtagphgyqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gteihbqobm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtubznwxsp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtuplblxml.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkkivtwdt.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgohnrfqq.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtdzubaiqv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtxysqzjgj.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtcxfbtrpp.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtjdhxnyie.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjblleibo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtrhvhqlxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtkktuhorz.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtzdnhayyt.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtbpkwdevp.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtipmoexdo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtxrppcpgp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtsfkalwui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtakkphcvp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlmytdtkz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtgbdcuvyn.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtfeudlnal.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtkvioawqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtsjbnyzvn.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtgompvjcd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtbfurxivy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtafohmljf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gthuwffzzm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtgaxaxbuh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtohiuuqqa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtfpelfjbf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtnquchaaz.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtaxacgpeo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrxgjry.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtvhtsavwa.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtnuxgqzcj.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtjpksekad.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtzugpxjbd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtdmeifpbl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gtxfgnbsfn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtircdidtg.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtubzipyru.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gttaxzlzoi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoyovtlq.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtnilmtyng.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gtfoqqjzza.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtxzoyriba.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtngivnbsd.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtjdthwroj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtzeqhwxwn.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtrxrjikxj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gtkixmtzdi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtmiehagze.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtojbhfewi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtlftocwzk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtbupzdbch.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtcivdjuyi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtedpwvcuz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtybifzzky.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfbqjftx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtbvtkzugh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gttknrmais.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtlbxfrftr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtdxwjczpo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtfengcrjv.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtnzttwmtp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtdpbcewvj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtzxvdmxis.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgcdvjslg.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gtzcbkhjnu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwuwmhdyw.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtzlcqwffy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtkzqianbk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtnbrfgmyd.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtkpolhsey.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtryvgkrgt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gthkbgcvlh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtjpxbfaha.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtbkjesest.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtlqtcjcgb.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtyrfuojng.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdibmjml.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtoglpbihg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtwsaxuzag.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtwbbhdjms.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtiuzqestz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtegbexloe.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtuhvvxavo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtlkbuhuzz.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtsevwavpn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjwjeqcfy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtonzuofxy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtbgnvdewa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtshhgbzaj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtuulfyboe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtfzejmqve.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtecmsdunh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtrymeorxk.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtmtutzlze.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtzyuwqooa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtsetcnrbl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gttnqmezpj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtmjnpagwq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gthdplkuvo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtwyiemoku.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtqywbwsmy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtmyxorvzc.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtlzooypjw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtfgvdcpgu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gtygcyhghh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtcuimzidt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtatbtkqxs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gthwpuzius.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtfpfkhjhq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwczhjw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtfloemmdb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtfirkpxuy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtxmmwdnuo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gteycyumwr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtahjbfuix.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtcyequcxu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtmxuxsejn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtreygttki.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtykxdsbho.html


<!-- 参考信息 -->