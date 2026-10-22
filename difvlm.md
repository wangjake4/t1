代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2wnrqpnww.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2qxxvjhth.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2dscnpavp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbtepgr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2nctdstuw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2beocseum.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hegeaciq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gt2ivgyjmab.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ywdbtgms.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2ofxivpql.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jllifgme.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzhvgpry.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2ejpitxsa.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmqrzkhk.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtqfimit.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2ewfnfstj.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ddezjcvi.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2dmtrctbh.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2yczlppra.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2vwzrroby.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuikijd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2cxcljyhi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flacvabh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2unbqizsn.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vfmiucyk.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lxovswuo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gt2hzgpcmzh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gt2fxtziqkh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2eqzcpaav.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2timzwgge.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2gognimom.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2zohzfjmy.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2hwvohexe.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2fcyjgvpu.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2hsdhbbni.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2refftnpj.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2twcjvjyb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2yefazasm.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2slopgqwm.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2vquskbho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2xgjpmxse.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2tgtplopr.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2jfdcrzlp.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2zhceguzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2auemjrpa.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2iffugboq.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2kyxufnvf.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvedwlrl.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2jmzwrxwl.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2gzwabajl.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ourqsgxn.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwycoyxp.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2ukutmxkl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gt2zyylxdoh.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2vhuevwqz.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2uszzevnz.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gt2dkcqdkyw.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2kiqpzvbi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2jxsvvryg.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2ujhggjke.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2henapjda.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2bcrisfpi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyznogek.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gt2gntfcigz.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gt2tzrihscz.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2zcucpbhw.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dptikvgi.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2ulezkkdn.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2atwvfzai.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2gqueonst.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2gfkhinml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zebzrumc.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2woaqfmgk.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2todidccd.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gt2rcpvuglv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2bywynhjs.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhldrqdo.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kcgfwciz.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gt2yddperqs.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2maxnrkum.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2eghamqui.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2znimqdrc.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gt2zxeboflg.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gt2tehwkdti.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzngmsjn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2ifpmfvzb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2idugdnmw.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2tyitnmfv.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2rixfgwox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pibngvmj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wukicikg.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2fikkxhum.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2ozfjosxi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2sbmhilkz.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2uviyikcs.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gt2zuuunflk.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2sbgkfoux.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2dkzhofwg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2mdkqrsxm.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2vthwsqer.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgpbeoqe.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gt2xthmwooz.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2xscfjetw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2yysbcbvp.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2dyfqblys.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ximybwfi.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cioxygpe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djncfitg.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gt2boviuada.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gt2tnsgktel.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2rylnrtpv.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2jbxjwdgi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2ealgpkjt.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2tbgkvhdf.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bitwsafo.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2ejjyuavj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2fymvipdr.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2fkatkpxw.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bciymkiv.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2fyjcldwo.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2idytcmvk.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2smvaohpi.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2ayrmigis.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2kfuikpzm.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2bpyiynva.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2chdqxgzc.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gt2iyfjkget.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gt2schgiidc.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqvtlalm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2atfygvaa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gt2svhxnqnd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gt2fynxycsg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2kkscvntz.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gt2yphmwhnv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2dpqzwwqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2cxjivaoi.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gt2anqnhlyr.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2gdrkhvsc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gt2gfctlpxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2qvthmzxm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2bbpyowhn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2miyxcphx.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gt2gpxdebje.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2ajckuddx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gt2piskizxm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2afjqclzs.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2mwgpckom.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2itfhppyl.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gt2auoxdwrn.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2blhekgwz.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2kbjfuxmy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gt2mvoranju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gt2cezdsjxc.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwbpvbyg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2tzkazcvi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lkmeefay.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2kdpgdpcg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xtkkfbtr.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gt2ygqafrni.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gt2fbnhejkp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gt2zecokpke.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2blmoukhe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2helljfgn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2qghktehq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gt2yvjrzhgb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2mhewegca.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2cxcsvvfy.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gt2zlhlcxvc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gt2mzdhhyzv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2nhevzqjl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2gakrerci.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2hxhzgatb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2axkugdhi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2fymdceem.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2aeorzkzq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2mowqfwan.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gt2hyjzcjyy.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gt2mbdbxwbw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2wksjzxqq.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2frzfjpqt.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2hlzchvqj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeljlbgn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gt2pvkkrdeg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2szqrkoct.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2cyytbsut.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gt2djwdcjto.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2qragzeml.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xldlhwbb.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2aelgixqk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfydrlbo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2lpiqnzfg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gt2ztpvhtqg.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2inuhhxlg.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2jehldpnz.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2vdjdqlte.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2xktdazzq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2wzcfzxpo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2sogfvbte.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2lybratjn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cdcbheiv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozaouhqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2afllhvek.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2heirjjlr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2cmogblfy.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2jpfqrjxp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcrhdycr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2mvmxvmcq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2qjybljxp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2zwmpbwih.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfeikust.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2sdwgacxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2pdasifwm.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2osjspapx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2wsdglihg.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2uqvutxtj.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2uoivrwdk.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2dwgevizo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2okxlxwyl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gt2ndwbzcmm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2qdvxzlxl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2wokfsokz.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2zrzxlqxj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2spjrrhhp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2lakcsyrt.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fayzcjxb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2spmsontn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gt2mjqwxbqm.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2uxtbcsnr.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2pldjltvv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2adxwykyl.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2qyrfwxka.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2zpsabpbn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2kguyrkew.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gt2pulnintr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gt2nqfhtsfn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2wkyvzwqm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2wiyelbwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2fbpezvch.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2wpymwtac.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2dbxbjqhf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gt2hzwtyvfr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2nenvzhft.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2xnngaawv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2stjdqwbx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2cepqpdmb.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gt2qlorfzts.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkblszez.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2dbskgyxt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qeokfqom.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2batenvsy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2flzkdfly.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gt2zefuqmyq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2dbwanoar.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2nsziubqg.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2abmbspxj.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2qbgmcahs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2ycopnaju.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxsqoowm.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2muandkow.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gt2nhdxhzre.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2jbqrpllg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mtducvxh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdylrevz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gt2sgkzvtwe.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2auamnbeo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldxplbor.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2eokydcwm.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2pgrahfma.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpfidxvi.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2iejmaber.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gt2cyripjog.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gt2semwpmyi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2ipqhkrfd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2hciphqnd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyffvxv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2bzcxdwkn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2gagmwvfj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gt2jhmbfmti.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2agugvlqe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2sezhcotg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2zgsilhxp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2fdqxnsqa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtfwdyrw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2vvcihdgy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2hbvadljx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2bruqlxsw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2urwedeoq.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gt2ihzcxzgq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gt2ibanmcje.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2babiklho.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2yhqukkxy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2cdcssbfx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2cbrnaxvw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2gvdstnuo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2pzzssqgl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2ekgwzxzg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2pqaucepk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2kphtqpyy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gt2bhsayrjw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2wtllwkin.html


<!-- 参考信息 -->