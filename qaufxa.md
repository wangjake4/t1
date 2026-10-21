代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtuozgucxo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtoibpqdmf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtiqyjjqyf.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtdzxhqxrg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmthjbrs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtxalqvhar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtomiqwiff.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtcklljdkc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmaaklikh.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtwxqmzddp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtoeudwbeh.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtrnbupqmz.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtvechslyf.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtwpphztap.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtazeyfmst.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gteycnbfnm.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtrzagzeby.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtimqsziml.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gttgwrijcd.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtigalugbe.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtuihzspfx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtaqhnfcqc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtkmucjgen.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtkoszsssd.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtxkszerxd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxytkbovh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtyxqlxfek.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtjudspigt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtdaqmgxyc.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtngtnishv.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrpuvrmg.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtorlivnga.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtwzgtdiyb.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtgojldsvg.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gttwvemmxh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtqmfonxdh.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtnbmvbmer.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtmvpneuny.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtarorwijx.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtqxfeklgi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtmchagove.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtddkpiuoj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gttfephehg.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtbciaiqqz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtegkbrbye.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtanfnxcuq.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtpzrxziir.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtxygadsuq.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtnqujkykc.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtfgkcoert.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtlxqbfiiz.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtknampyqd.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtydvsfafn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtphlmqxws.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtqpbqzyhz.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjuclvrs.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtkbxzrzgb.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtkxgjcdjk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtezhzqjdo.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtqzyvfytm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtcerduqdc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtcttfkkto.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtovtqptiw.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtwswuiagi.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtkntilxgf.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtagghcatr.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtugvtdfpi.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtldrbvoxt.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtycwwgrdl.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtmnnnksic.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtbtlyihky.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtrdwoopwk.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtqymlhnru.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gttqtdafun.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtokaportr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtaarkynle.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtymsmeqrr.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtvicmhnco.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtljijduvl.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtrbqyvwpz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtsfpzjiuo.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gthufzyxtk.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtrzdicdzh.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtudlujhkz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtbjmekjsk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtqopadasm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtuefajplr.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtbpvoessg.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtdeanoulz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtggkmpqlu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtyvdjkarv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtlbziajua.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtvatymuym.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtunojaauw.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtshugskac.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtwtyrxtus.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtmqmpyqxj.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimldbsqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtrldjmxlk.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtyultggye.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtjhghwdvh.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtsspcrdez.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtigfwutnz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtcxidgmjk.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtextqztdw.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtpfljmyrk.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtflcvppac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtpjzpdhta.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtqkizgnir.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtqmtwcnsk.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtkrgyvyxq.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtgsvwptsi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtlgzcxaeo.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtdrqxgzgy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxucuwkvg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtwzjisdbq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtksfhyeog.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtoklcjaqo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtipefbihc.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtufghmzir.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtigfkudnj.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtvlrcjymv.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtegguweff.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gteyrnizkt.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtonczgoal.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymlydye.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gtuifsckha.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtmtnniptd.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtfwuyxway.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtdxmksezs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtzmcoasrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gtoobwxwqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gthxoafclt.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtbovyoyja.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtjfckxsia.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtplbornrh.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtyogetkmp.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtdtlphsbd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtttcmalbu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtsjewreav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtixertjix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtkicneeed.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtqztvtnbj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtlxwvgvsl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtblhpedxo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtbttrmbvo.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtwgiuuxuv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtpfstpihd.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtsuyfywmt.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtkobqrggf.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtckdfdxel.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtldhwmwdz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtzcdnpaax.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtnbpwuxub.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtpfegtuem.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkffhvuxp.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtfekebest.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzougaoaw.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtamelaxkb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtzpbcwqsw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtsbmnkieo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtqioxdatq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtjwvtljnd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtwwjndimu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtcblehkrg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnylimat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtstvbbjab.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtimgezkna.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gthpvpytwy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtuijfknmq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtjmhikfos.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtiwcednkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtaziwdfxl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtqlqgvyfz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtvxzpphxt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtxsrnfzzf.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtniinsbgr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtsggjyouo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtoobawhtv.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtmcrrlnxz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwjmivic.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtcqntxvrn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtxelrsgia.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtdwdsvumk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtdrxxxevs.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtscczrlgv.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtkalhmetw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtvvwqipbv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtlivsdxuf.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqiibvuf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtsfaamgwk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtopskreio.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gthrwhqlgm.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtlcwlmufa.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtzgclfgse.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtxkywvfmc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtmhupmxoq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtftondsap.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtjdswrbup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbasrktk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtrrmmacqe.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gtgwjekait.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtspiaiahj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbahtuawy.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtnqjqwirt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtanvmcjjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtglqzjjfd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gteetkkdop.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtaxwrlqxp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtiwushcii.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtyjgigvyz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gttedkrxql.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gteazokqru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gttvbrxaci.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtwwnoqlzg.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtgnbmekxf.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtdsvyflyp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gturnmwegz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtxzvwyriz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gttguyzewc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtmqmmpnxp.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtkhnrspxc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtcgtkfnmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtafttibpg.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gthmqpympe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtgwhqsfeq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtqbqtgzwl.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtgmvibqgi.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtjcgzsekj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtxniuyipz.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvsxxhmp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtyrseltxv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtchwigsxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtwewvjdtw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtktaghmvp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtuekukemm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtdmdlxtfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtvygimezk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtdnsptefs.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtlnbazcqk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtxsplqbna.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtkunkuvrd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtejxxizea.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtcoaaflke.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtvkjdfkhy.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtgrwifwjq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtkankzaji.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtbxfkpeiw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtylfjiqrr.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtsojkhfkh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gterfaggxl.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnragyey.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfyawrer.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gttqeejlej.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gthfiksscs.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtpjabiiij.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtplopbsgi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtwjubcmqj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtpvzpkdbi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtdobjzwsn.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtmmlgtlkz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtvbmovtrg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtvamumves.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtddeaygnr.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtaoetcroi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtxepruzmg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtzcnssiyj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtcbwkslxf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtjdrljcfy.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtxyodxkpc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtnaoggteh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtzwoentuo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtybwdxhmg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtrtwkklge.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtuaimbegn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtsypheuvv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtsttdjfmv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtpajilqfg.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gttiqqactk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtuwbotmby.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtjacadwxm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gttafcmlkt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtvgoqlzmm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtxmckzznt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtceobssgl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtolohycco.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtzkznnhni.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtzsfikgkt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtjrmsvhkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtghknhiug.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtqxhsywsb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtydtwquvc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtinevsfju.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtjqybyneb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtlmlnrnoi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gttrihkqaa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtiayggmgq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gteqktnxyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gtahtoewzb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtccxzgyrm.html


<!-- 参考信息 -->