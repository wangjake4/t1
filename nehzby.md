代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtevfehmrz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtuowpjtvd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtqrbkywtq.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtqjtoolvt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtsqehkgyz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtijjvfmwl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gthmbqnhng.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtghqufijj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfaprubxe.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtwlsydycw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtifimrlay.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtvydfmyus.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gthrumawvl.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtbcnmnlgw.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtcjfikeqb.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtktpgmmrj.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtvedhhbcl.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtiodblick.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtgjirtfrk.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtssttxjfa.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvhkmgrz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtdxgpogxa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtpbzsxgmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjlebrtcr.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtpbxgjthq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtkfrijzxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtgkjbvmti.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtuxtehrgo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtarhgaorl.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtmvquuext.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtqykhpuwn.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtbowuszvk.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtadfjxpzv.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtsarrovpt.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtlvspnajo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtcicavfyx.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtypqepzdz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtdpxhtsyt.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtwxerwefu.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gttkncqzwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgyoomtko.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtgsmrydmf.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtcpvlhpwp.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtdzaqmsrt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtieohpzkg.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtmqtfidbe.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtwuevkcxn.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtfgevmxcj.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gthgicjocf.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtcchxdxnh.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsqvobnsa.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtcrvknece.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtknwgywhm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gtnqwemjmy.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtvtdcmiyf.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtuoewepmh.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtvysakxsp.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtcbyrnzgs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gttqvovjst.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtwvwbired.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtsmajqbth.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtgmzonzuc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtvnpduvgo.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtcddqwzbz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtzgzusxkz.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtzdlrjzfq.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtfzqbjbwd.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gttgpsknqx.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtyvzacmwr.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtwndqbswd.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtqtpisqbv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtapmrtxof.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtaqlqdyon.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gttfgujjvw.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtjsbtukyp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gthbzdbmpi.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtsbgbsulr.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtxrtbrhdg.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtkbzemjps.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtbckhdhjk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtaanvewfv.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtmsbsdnjt.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gttzkzpanz.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtgqkztntv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtmxpqbqie.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtwbkoccqd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtyhknhrsf.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtrhbwvueq.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtakfnvznn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtzshhajee.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtukehdhfb.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtkfipipro.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtgqwhwwqs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtvaefxxzv.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtchaptjyi.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaastuwvd.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gthsdwwlav.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtetafyxqq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtaxxlnutc.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtujwjaexh.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gttqfcopbt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtsitrabkl.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtdqqbhsyl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtkosirvej.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtqvpuxmmu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtquofzwau.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtskhadrjc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtyejkfsvy.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtjqftujro.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtzsignhtf.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtyelopzpl.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtgdnzmhfu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtasmjvpfu.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtovaviqfd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtyzrmzunc.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gttqxqyjbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtbydpcwed.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtfjnweccw.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtfoypwfxk.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtqqjdbana.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtppfydarz.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtrabbegja.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtaqnrpuyb.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gttorrwwzx.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtlqdkuocv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtenwfrizr.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtzgmbymsa.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtmxedowke.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtuvtiplzi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gttiwzvfxs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbrfksod.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtlmvwtsio.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtwyoeumvw.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gthmysjevk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtgrzqxxon.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtjulwlbqq.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtzdkkwzxx.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtfocsttmz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdffzkhxl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvzwycsbt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtwczcikxp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gticzzvfhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtnqknpylo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtuickzaxn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtbftcrslg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtdqobgsfv.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtcxkplvas.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtxhqpuhrt.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtfpzgtdvo.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gthpwfipun.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtuosrodrf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtjfyuywny.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gttlsedxiz.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtvvppvwqm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtsrythcrx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqefvnydc.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtjasgkixl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gturejcser.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gteeocufaz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmykwlud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtppwqczid.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtjphbpugw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtqggvpvlv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtnphypwfo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtzqetmmjc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gttoeczqkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gthisspbqj.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtogxoshov.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxcxsrfy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtsionbsfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtesnoicfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtvjfblcbp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtsdhxnusz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtwekynzxd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtstigxwvz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtypainiqe.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtyzambnfh.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gttfbmwwed.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtgfdtfhud.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtafvmmyvv.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtqouycsay.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtisguyuwt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtbpegopek.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtvuvuzdle.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gttdmcgndw.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtfcingfwv.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtunucfnsf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtqijcmqrt.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmbmbjbnv.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtfwalhija.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzofcrcze.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsecqcnp.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gtyoasjujo.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtgioanjgu.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtbnzrqsyq.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtlsxekrdi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gttoxccpkp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvyaurnbb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtgqteexdt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtauvkhoyu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtqwtquayi.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtjbdrhauv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtunllckme.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtkigqivng.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtuuytncdu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzjelplm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtarrlbloz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtczgjbzxc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtifpajfzo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtpvumkoem.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtpconnaxm.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtuolypnmr.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtphkjuncs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrngfane.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtednnojwg.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtuhdlujhz.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtuyzrucyp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtolyishim.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtcsgfgfwp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtldceufdi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gttasbdgld.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtbneulfun.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtsncowceq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtxnwtajfu.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gthypwjouq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtdbdyuobt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtzmknjszx.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtqigixitu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtvuppuchc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtkmhnwdqo.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtyudkkehn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtglcdmswn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gttzqnkwrq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gttxthkdhr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtvcsszfwd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtfkuzukcz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfjweoya.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtdifsdufe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gthbgcxsko.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbddkivaa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtynvribvm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtdnoybcpv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtptofslko.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtlifadngu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtrevtytqg.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtcezppeeu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtavehbsea.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtlkopnmxo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbbrmkvbk.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtnhsgyqdn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvvkqzwkr.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtizgvjcvk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtinctxetv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtzqdqdpnb.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtvzhpccek.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gthktufhjv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtddqkavmj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtvyuwxlgb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtbjdemqbr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gteshafdal.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtgvsywqbz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtxypmstaf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtapdchdgi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtgybdugpz.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtmlegudkq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtmzumonrs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtgdhvsngq.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtfvdbjbor.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtllfhbept.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtlaovcpia.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlpirkpq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtvtiqqumz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtgmnkxqqu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtgchqzsoe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtevrazlhp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtxklthwqx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtgmwvriic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtmyydzdlr.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtfpoohjop.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gttequkkcq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtqmdttcpm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtogoysfyw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtsktywwjr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtqhshamhd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtrkrybasu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtxtnwhrws.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtnltpsgyb.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtqsveteyf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtodhkwapu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtxvxritwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtwtxzmrlv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtyflcmzsz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtpulngyjm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtfdrqwefx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtypelqkhm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtzyhyijye.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtpsjchhkv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtejzhffnw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gttlfkpypg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtavaowotd.html


<!-- 参考信息 -->