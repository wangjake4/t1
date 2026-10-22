代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gt2spuhzfly.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eokbwkeh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2jzujynhm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyqxscly.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mjxynbaz.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2hotydgro.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2shelvpkj.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2tmvgwlfl.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gt2bdjndejn.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gt2sjavfssl.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ptgximar.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2ktbmkftu.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2htheyean.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2ebhmhemk.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2kvwnbnbw.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hhrihdvi.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gt2pwyrfewm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkxtxrxr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2rahytpwo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2dungjmrt.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcahmbuv.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2vietpsgj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2bqebrcjq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2uljrqnqf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2vewvmage.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gt2hxwrhhqr.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2mpxqdbks.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2bljfphev.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2azbipxcv.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2arqxpsgi.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2pmohmelo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2uvkhqdkh.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2ezlhzzcz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2nwgmscsq.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2lxfuadee.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2leomsxsv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2hkiyxhai.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ccenbiuo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zirfpsmp.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2ixymxanh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2cotxwkzz.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2lmogtcam.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2getvzosi.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgstmnqa.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2fxuryolm.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mftlaqiu.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2gfultpbm.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fegbijlz.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2qbtukbcu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfmbcjaz.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gt2xotoavag.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pjbiycrx.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gt2pphqttka.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2tzykjeua.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2tngjqfek.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2gzdfrmho.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2lhjrjbjz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2cbclsmlf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzqfkpxi.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2pqnpnnvu.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2vcprdmai.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgozyyfl.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gt2rpqcvqii.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2rsudlhfy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrgmooc.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2gmruasof.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmnhryxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gt2oxtqtyje.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gt2gyhkkdpp.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2xjekwiku.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2lpurnpfc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2gthwgoaj.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2ltmconsy.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2chtrgryk.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2edkedyvq.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2ckwpywxz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2mbtlrflt.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2ucpxjtoe.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2cqnxxfoy.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gt2ddxuvxus.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gt2yirodnhf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2cvnknclu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2bppynfja.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gt2fhuewpzz.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2irbunoxq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gt2cfttzder.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2xemfjgnq.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2xbvmayht.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gt2kjetjuql.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gt2hepkktdn.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxzqulqo.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gt2fzhrdgvs.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2iapfxywg.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2ulsadtwo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gt2dwiokgta.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2qbahfypz.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gt2qofegoaw.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gt2bqydnaaw.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2rdvueyfp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ongyucgj.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ptbbgzhh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2mezqyzqh.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2olmvfsfe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2gdgowtzo.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2nwlacfxb.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2ndpztdhf.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2bdnmvhfv.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2oopienwf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufivxneg.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2zvkeukbg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kytscmav.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2fqnbesqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2khleflhs.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gt2nmiuegre.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2nwkhvpwp.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gt2tmdwxelk.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gt2cbielgqj.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unpextio.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2nbssjvpu.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2xokrvdnt.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2pqlpzqzm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2rqvwtenv.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvanngil.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gt2rhgrpqig.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gt2jaiytzmu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2hddridka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2rkwctmbw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xthfojpy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gt2iwljfkug.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2nexigirb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gt2mreinsqv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2lmvojiiq.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gt2hgxwnhrr.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2bmqgjokv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gt2ymbzgzrk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gt2czjijgxa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2hpkpebzh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2tqqznfuw.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2ikxvpbkf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2mwgiahwa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2nbwpqceq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2rlpylzwt.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2pmjdqxwb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2uswwpgyq.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gt2puegdbnc.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2teaddhhr.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlhanmlz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2jmcrrxoc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mejnpxsa.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2rsmmkqkp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2jvrmigrd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ojguweyi.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2cxkmchqw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lcgvfemv.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2vpdigzxu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gt2lqiourwb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2rassozce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2qimicsxj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2dvnvpwfr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gt2jkzldeoq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gt2rbjtahzs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2syskyeui.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gt2cchpfmvn.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2cislsadc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2ymdjjfac.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2enrmdfng.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqfldzxl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2fcjjouat.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2huhqvcdg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2enxarhtw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2gatzavyd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2lohdygcc.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2nzbrpovg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqaywzl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2mrrjoczf.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2wwefcoir.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2lpqjauqk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2yvynfstf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2xqwarpcr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2vnfxejde.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2qgoqczdx.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueruvnuf.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2shgndahz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2kkazaxdl.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2schfnesm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwuxwxr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2krsxmdhh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2lntcnieo.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2ghpordkt.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2pdexqrty.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2jzivuqsn.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2cazqwucl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2ztiwwgmg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2spzukelp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tejihtda.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2jyjvamaz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2qsiwbprw.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2cjkqjdbp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2lpuqlxqp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gt2ikesohkf.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2kctiebrd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgrbdmqy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2wzzutrlo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2qhyorwjr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2niccewvz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gt2uwqckrkb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gt2yirfyxex.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2ejczqaeh.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2xmwlmcui.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2iyoidmrd.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2tfpmjjnh.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ixzurezt.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2astusmok.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2uetwkjhc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2dtjstmsw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gt2ctgkqubq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2azlnubac.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gt2kdtkusri.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqzvskog.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gt2ccuhrvqg.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gt2ocaoqpnw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gt2zeodcslz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2waduajrb.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2zqjjslrg.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2bdbqszyp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gt2tesqvego.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2adtosmic.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2jsahtjne.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2tpoucfnz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2qvsnvlpd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcumooq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gt2pwggvtqp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2kakylgjk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkqtgloc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2piacojce.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2mnlgpnxi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2swcujsmp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2bbuffxyh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2qdjpftly.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2opfwriff.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2xkibuckg.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2rqylishk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzujdfmu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2psjendiv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zxgfazge.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2xnmhhirc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2yjzlsunb.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2ymfpdmvx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2hcxcgxay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2bnichhga.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2sfdmstrc.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2xxykujkn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2rpzjplie.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojwxjcl.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2rwtlodvu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2kurnkhwd.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2lctusckv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2xtmcxnhn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gt2jfloizel.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2dggjohyx.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hldscqzg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2dvbvstgv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2yxcffxsd.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2klwbhseg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2dhfqvdcz.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2zlctjgud.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwncqzkr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2pkofumwf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2olnbntwi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2gvmbmycv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2audndwju.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2qumenfyc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2axmeqodv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2rybnolae.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2adybgqas.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2euoqhyok.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2yniyexep.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2ehgfpiqs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2gtkchyzf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2oychevbs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2hdflxxyx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2tshabrrn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2zsccwrag.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gt2tzirased.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdugixzx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2pdbznkja.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukyoavqf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2ocpayizw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gt2nvhssynh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2acqfvwli.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2cngnsnaq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpqspolf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2stqqfijo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2rpwvqilb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gt2xnjeyteg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2otoirxnk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2ahayrjnw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2ylkylnbu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gt2njlyzkmi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2ffvxzxjb.html


<!-- 参考信息 -->