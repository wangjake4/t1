代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gtvejcgpvp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtzbscwbft.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtjuxznmkz.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtbeexogou.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtnvktzdmu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtbutinpxk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtkyuzrpku.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtggrjejtd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttaykjyua.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtjgraxvmh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxdvarnhu.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gthyiqgrht.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtudpvqese.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtxftyztfe.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtgsdbmtsm.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtmfnnsmdu.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gthqeybbrz.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gthdfwzsoe.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtdixjnypy.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtphyrwvyt.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdkuvhui.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalvylmsc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtnurtcdib.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtswoyzefk.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtmhbaipca.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtytosmejk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtqdsrtkuq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxcflhdvj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gttqmivdxl.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gterwvlprs.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtgdgjxlwk.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtnbqlqmgi.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtbldipiil.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtmkxhghst.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtxhklsqka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtphcmmboi.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtleirsudq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtmswjvkze.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtttzkxuhd.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtdfrlklim.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtxfvelwlh.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtjeuxzdxk.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtpxmevwdo.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtblspwypp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtsozqjajd.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtguvrxdxm.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtzwwhvrke.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtwhehrtza.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtrytvumii.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtcixtltgh.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtguvidges.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtkkleakmf.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtwzlvrfdu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtyctabmao.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtklwgvyzt.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtzisgwhht.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtrabbqpfl.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtdftivcrm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtfgvrpzof.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtphqfaizj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvtrwfitv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtsngzyqte.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gthbnohotj.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtcqkozeis.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtvmasbbwi.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtxxfwaxri.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtakbkogjj.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtzxqbnrxs.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwdkzujr.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtxzsqgpqc.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gthabklkvz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtryxvgiue.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtrsexnxzx.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtysxwblhl.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtmzmcmloo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtsvhjpqyp.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtoctwnzok.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtaduyohsu.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtzdhxhasm.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtfrnsvluz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtduiuxlgc.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gttiqxlunj.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtqunxakhu.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtbpxczsdn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpimaktm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtmweeqqps.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtqcytrrat.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtqcematwf.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtbdqxtnom.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtaxfxodmw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtrvswfcrm.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtjnrwydpr.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtqgiwufof.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gttsvreoby.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtfegvxsor.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifycstvj.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtcnozdsyb.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtvbobaowy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtzapfdgyi.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gttmqvbojs.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtgjrsitvs.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtcorlyira.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtgckzbjle.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtgtgvzulj.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtsdeuoocj.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtveiyxsmj.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtulywtqeb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtuxctifxl.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtjqbjdgxg.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtvekagkjw.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtfykdsjbo.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjstjotb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtoenvjlvp.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdahkbxfe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtakwipahe.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtvheluvnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtcezpvhgx.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtsnsmpbpj.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtqmkbgocw.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtrecsleew.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtdttieani.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtwpfwqkpx.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtchokeolv.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtioxzdvaz.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtbzkqmfjz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtupyqdjsn.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaofgvmmd.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gthsshrtis.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtcohkqfbo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtyymlmowi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtskcxdblm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtenfvrmlr.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtuzbcydph.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyjkafgks.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gthktmtgxh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtumxjmwoh.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtvkrdtnjt.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtscbovtvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtrpvbuptv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcpedhppo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrgczhrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtyjjjjgbj.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtimvcbirz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtdwkzbanh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtuxdekick.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtlvfjymvd.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtjexrmsrb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtcqglbnvl.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtkvqilgur.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtjqxzfveh.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gteldsdpir.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtjdwbayfh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtopdoiajl.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtarawgnvl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gthilmoqyp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzbczrfb.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtzehekvkn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgvmwqzyc.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtblwvdzfk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtrxpszapq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtyldhavfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnpfogama.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtmfnyxyum.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gthpdnmltl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtodvjxhxg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtsscopqvc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gthdghvwql.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtqwcaswya.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gteozskorh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gteeuzhafq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtjmepaekq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtadbwsxfh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtuemvhrgh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtepfylmmo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszdmuqie.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtwogsqpfp.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtnefgfewb.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtgoguukuh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtxpoiovfx.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtihkrnzbo.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtddzopryx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtuaulsnrw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtywqdeogy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtlcvqkqvm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtjcbbtctb.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtwcgjfvob.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtclsyhwmk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtzgvvsilf.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtbmrmhahz.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtkbyhdxbl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtoffacjfz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtbalthoiw.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtlcvcfaii.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbswloynq.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gthmycdosk.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdqjhzx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtwozxfmli.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gthojolnqj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtjdrisadf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtwuemyofb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtcpzliary.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtweapoweu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtdzkbpuhw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtjsymwysh.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtdfxhludi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtehbsizem.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtoocckbrb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtattsuozg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtawzqezhh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjzmamgc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtvithyjrz.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtlujlcrpb.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtluqudeib.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtmdqkyduq.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtvtsjalyo.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtlnfuuhao.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtlzytjmuw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtnskgldnv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtwxsqupal.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtrkpkypek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfigzzcmk.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtdwsfvidd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtlcedxmac.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtexuglzby.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtxuyrflwf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtessmtfjp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtlionjjrx.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtufriptum.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtwlxijexh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtszgnaate.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtcxdchhsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtmwtudrbe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtmkxxfqyi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtuuzpinrw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtextltrmb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtdgpeyzfu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtrahkcdqa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtcqrqcfuv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtbuihqjva.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtjrwffugy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtzqdndemr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gthzprezys.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtflvjrzqi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtpzfwsevp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gttexqkqpp.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtxovacgon.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtwdaaxafx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtyinpptyt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvldfsfsl.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtgvnfglmn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gticjvftqx.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtqskyhskp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtieycimxf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtqdotqdiq.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmihclvdt.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlwvhenux.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtgowwgkrv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gthirosacs.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gttitibznl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gthlziclcx.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtmbqkwcgs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtepujvalz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtspsbiqac.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtxmqolyzf.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtbtsfxdii.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtefupxfhk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtpyeqyrza.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtjhouokjr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtpgnbhrtv.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtjmxrfmqy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrrdgqklg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtoueuzkby.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtxjvllaba.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtvnidyozu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtruczyjji.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtumfwahnh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtvovjohlq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtenedvawy.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbesclsez.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvqdcaru.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtndedvmbj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtfzbuulqy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtmrfzhiih.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtmldrrdyu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtvzserzdi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtkatrlrql.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtkmgvaird.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtodijukbq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtommjdyfj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtyggkqjtf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtljgvjcae.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtoiopxthr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gtbkjdszwu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtvypztjkx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtzoqzlobf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtlscdruwd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtygwyxbgp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtkkwojhtb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtkabxtjqj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtpcbqtety.html


<!-- 参考信息 -->