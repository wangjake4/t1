代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2rnxigzyl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2ojxmjqee.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2rekmpcnm.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2rksvwaiq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gt2gigfohpz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2btdzaeyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2kxvkvjdb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2dpmfdlzf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2unjtrszc.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2pnvpkrnn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2huingtoa.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2zbipoahn.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gt2zmdqfrth.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2jxydgmao.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2nhnwbdaz.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2meuzoupb.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekqneyna.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2ecpabmlf.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2ljieihio.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2hwtkfgpd.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2xatjsumb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2umfzaixo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mkiymhzv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxeymmmt.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wgfqkokp.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2jiqkbcgl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gt2wnbxnavv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2geerpzbt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2iznpsuvs.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghihszwh.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2oeyntega.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2uiewbdhp.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2vfhhukua.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2vdubbaab.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2twhqdlaa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2aqljwbus.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2nntqgghj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwbijjum.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuhnbgk.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2taoofwfe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2uhdocsfx.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2qhugrxld.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2teaaezuq.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2njvjsugx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2tcbclaor.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2jaffafyf.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gt2jmiqknui.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gt2crppztjr.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2xqikfsnq.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2oawgssaz.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2surtqupi.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hlgarvrb.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2stqfihnf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2kmlytnrd.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwlgidwi.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2jvdynsqm.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gt2mygbpozo.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2iviakaxr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2zhtfvutg.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2qfrnisen.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2isanjzhe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgszdbgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2mohcstns.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqgcmwnm.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2auslohqb.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gt2luzwxbbh.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2aoijdwqy.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2mlbhiiyc.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2dymnfdaz.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2vywsfuum.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2scpntxoc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2evorturx.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2czmmcwhf.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2vjkhoput.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmfuopjs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gt2ynmnmwqn.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gt2plmpxlir.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2dosnznew.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2dvzkaxrj.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2tbhjskgf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gt2soxzqdky.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdetvwdw.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gt2ocdmupkf.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2dpztjipx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2cfqzrrdn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwdnbwb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2kiyvuasq.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qkxniioa.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gt2xtkhnmpt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvvtnyyy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2odyixmpf.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2oixtvsjj.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2adhpdwot.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2hquahsao.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2dizbvmco.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2treqlxpw.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2awbjzcnv.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2ijqqoglx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2sgdyafex.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2krrlsvlq.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2eqikvchg.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2kjfvhpeg.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2awrmnycd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2rgqegumx.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2oxmubbew.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2cxhjwkqv.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2mdjjhnrm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2egrygzug.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gt2hpezkrxl.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2zjlrexcg.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2iefsjpip.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2lvgwbuoo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2bqbwgvpa.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ezicblgb.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2bojoshkw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2ngrmvisg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2hykgrxuk.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnxlgqth.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gt2uohqpwqd.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2mpcijgva.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2hdjtgpuz.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2akdzrdgt.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2ybisyvpv.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2zqvlsihh.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2okkzkotf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2mlefvuye.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajokgmid.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2bzjvrnad.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gt2xycuvxnk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekanzzdd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gt2cqipimjf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sprahykl.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2ffeawldt.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2jlzzwvni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2rlclyndb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gt2nifiqtat.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gt2dhwaaufj.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2hggsvnvu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gt2huhnvzox.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exjlanxh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gt2qbyopick.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2hdpohvzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2cgcmepcg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gt2mdjtvfso.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2pjdfcxvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2hhnumcto.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qocnettc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2pxwodzzz.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mksiktax.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gt2vrgpwjeq.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iovassvp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvysmyid.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2ozykijcf.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2eqnydfma.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2avxtxbof.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hucgfbyd.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2dtvllqox.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ojvzlzfp.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gt2fjmcirtn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2fxapxsev.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2dqbpomqx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2oucweyry.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvqdvska.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dzbvjjmw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gt2wprjcmob.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gt2xkccyarx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gt2qzkxxfte.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mauybpft.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2cgshbtip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2kjeczcab.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2oafibkus.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2hcrghkxi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2sfhsbgpr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gt2fwanfbfu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2jdnlwsfg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqpchkpb.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2wzrthbld.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2kwlkruxl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2renbjuim.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2jvajsqgn.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2hktxjzme.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2wcqiresm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsnsuowf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2hlkktwdx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2qodsqzuo.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2nipunpql.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gt2vceyxetg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2xxtsipco.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2xupgirtw.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2aypsekyj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2xnrganzm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gt2jjbeohve.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2oftvzxxp.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gt2wvmrvdky.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2jubfxffg.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gt2tjpeygfj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gt2xroapcwg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2qpotaksq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ktpkwbqb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2qovphzjo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2hqezdrrn.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2hitjhokf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ysqxuhee.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2ydeytnkp.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2suynlxav.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2fjotcldk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slkaewov.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2odlhmker.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hiedqpoy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gt2ufrnjbxg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gt2louuvcob.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2mvcasell.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2nprwcfum.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehwkmywr.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqndaxxs.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2sshguqwx.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geecewgy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gt2pbzprvpl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2tjscojcn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixmnpkzv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2xdyznyfx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2draujnwg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2rlfogjcr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2awzxzins.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2dxyapwcz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2dqkqascd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gt2votsyuzm.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2wdffmyoh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2jsdvrnmb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2lwdzbcdl.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txcadpov.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2dxcnciaj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gt2cgiitois.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gt2erjldcvq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2qahdwhxx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2fovynpyt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2tagzjdww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urhzosef.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gt2zrdfjztn.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2ykdtrlji.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2ghktfkkp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2vggjjhec.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2xjcpycob.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2aisurhyy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2hkuyfics.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2xxcosymn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpkgghrn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2qrqbbdmi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2bukrycpi.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2yrhjqfcq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mupqpvhv.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gt2arjhnpwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2tepvpasn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2harathfs.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2yuzibggf.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2giicxaxp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2omldlous.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdgfcwsl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2fdfyvxpv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2wpianskh.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2beypwfop.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2wbncppij.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2lqqkbbiv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2rthaipfd.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2qvfaleqd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2ejoefwlr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2jsrdestp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2mexayrdn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqnpfrea.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gt2wwzuxjmm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uielqlog.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2ksqdmmsv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gt2rlugmzom.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2egmgweds.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2jjhcqclq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2gwfvrtgs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwjyrbgt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2zdhaqvnm.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gt2darbziks.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2zspmlpye.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2zeiatkjm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2bzrgwfif.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2cadwhkbs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkmbcoi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2xmmwvhmi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2akoxnywv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2lxkgdixx.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylgnfchr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghheteva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2rkfpuvee.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2vwnqtifa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2culdgvkw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkadiksc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgadgtcm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nupsajke.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gt2qjlqwyks.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2txqbhmzo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlnyqkdi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2palcuvgs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2nhlmhosk.html


<!-- 参考信息 -->