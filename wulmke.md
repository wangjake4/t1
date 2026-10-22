代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gt2vnbpltzg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fafgjkfc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2wppglbok.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2pnqqxeam.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2wjubljag.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2vtbdkqir.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2meehytsl.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2pirihcer.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqojzktc.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2wjsjdlet.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2iahptgcv.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cdrmrlzp.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gt2rxjkeaqd.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gt2jyzavfgr.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2iedorbvu.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2eckytrra.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2yvbbjmrr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2fgmgkisb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2kjkxkoxn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2grvnfkoa.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nlstaxvi.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qllicqnv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjizpxsl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gt2ujioyixr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2frvxulxi.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2wegkinhy.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gt2yossyfqo.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2urqpcafj.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2pawegfdw.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2dkupuago.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2qhlzszbg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2qywzfcri.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2mopfekus.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2uotuowap.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2kequakjg.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2rcazunth.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qptlfpgl.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hmqbdpxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2roybmzzb.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xmhfsvsv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2fgdlpttf.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2jdoiavsr.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2ekwikokw.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gt2rdclzasr.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2wywjabyu.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bycxygpa.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsvsxfzj.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2kjttcail.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fdikazpl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gt2aybfpzup.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2ftoubley.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2elasijnm.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2lapbopxp.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2hpdatlxx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2lrmyupdi.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2ifdlyyqv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mznsypgb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvniipqn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2eqyykhwm.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gt2pqcnpkid.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2nijrmeqb.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2xgdrdybz.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2lyxnbefe.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gt2piomzzdt.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2ctznejvg.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2bdmzbicy.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2bjiqfjni.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gt2hlulrerm.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2xudxxexj.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxzfsead.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gt2bhwezqzq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2ppyyfrqb.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2mzvxijfm.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2taaarfna.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gt2etstofoc.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2iyewpdem.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2lvjpocam.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2cefxmoht.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uezcoold.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2wzmmnoxy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2lmyvkall.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2rrkndaqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2pesnpwxq.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gt2flcqglxk.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gt2voybwsak.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gt2ysqqllra.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ohsotcru.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2nxnooazu.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2sxulpvwt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yakmdlka.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2bfeuzdbt.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gt2oedbhoaj.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2erydhhce.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2xayfmvpn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gt2xswwfqlb.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2tihjgubm.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2gmxyhqcd.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gt2zzpgzykp.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2trsadxbc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2fabwcjcl.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2pugyhyps.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2vbdvjfzo.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytpfapcq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2myahweeg.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gt2wcattbfs.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gt2ulrihqdk.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoticzwu.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2cwwjkodc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2qfarvkwp.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2tliejahr.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2olcsppvs.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2nbuglcpv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2kcbmkmov.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2kehvikch.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqhvzcof.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2eykkdzgj.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2zizruvgr.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2ifeueeos.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2yavaqgtv.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2gxwpvvrs.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2cfythwkx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuswneyt.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gt2anfsuqlh.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2wgxcygom.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gt2vgbbdzar.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gt2ivniuqmj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2dkmkgznu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2isunhbyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2dcgoyzaf.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2lotryjbn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2lodvczgu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2grrmguiz.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2beswbcbn.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2xzlwyrad.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gt2ihiptbht.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2bmttrdgn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gt2deviqojq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2qqnirqgq.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gt2tjzjbhqa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gt2jauootud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gt2ljcbhijy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2oeydjizd.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2agyeilue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gt2xjnlhcaa.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2icjxmvtn.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2jtcdzjkh.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2syhjidbc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2rogksvdv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gt2znrqdnku.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gt2bgtjxpxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2alxxeyql.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tghlzlyt.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2hpjrszur.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pbiqvuxk.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2orduxezm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gt2bswtzvip.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2aztlzkqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qcfwvsac.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2yaljvqls.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2ojotltoy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2tqeachlg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2ysdeqnak.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdvjcvgd.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gt2equsevun.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gt2qfgmkizg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2xjqobkcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2arwrwana.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2iklcedtj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2xvltwzsd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkvwjvul.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gt2ycsvhyim.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2itkelvoz.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2ukmpvsam.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2oyqoaykr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2pokensva.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2sgczjvrr.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2gyouajui.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2sqrtswhr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptbrvabq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gt2oywvjtvx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2zxhvhvem.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2undrolot.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gt2mgvgzfwz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2kddjoxqe.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2iullcbfn.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2foppyosr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oslokyaf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gt2vkrcqrmj.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2fpjltnip.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2tsxludun.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2zhjzwvzs.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2isbrjmrv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2yigwojhp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2jrplqpsn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2vrpdtyys.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2npifxtui.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2pfcsdtgy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txpmrtff.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2acikprkh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gt2dzneetvx.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2bzkdkvnu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2flobpsqz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2reqjvqao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2pjtmchda.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2cyavkikt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2ghiqydah.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2jdufkeoa.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2xwmzvtsq.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gt2jcuzgayj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gt2qvhugrdw.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2qxjmbmpr.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2xibbvrhi.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2otddnupj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2jkizsydx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2sbvqyjhv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2rwajcxkz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmszbnvb.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxwczqkg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2gkfncdwb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gt2mhvgnswz.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2rvpzolfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gt2asbwmfkx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2birqyaff.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnplroip.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2lgnguwvg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2zmfsackb.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gt2mreqavcp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2qeinucfi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2wstsdivf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gt2xhqmplke.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gt2pqfpgmzz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2nqulplcl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2ckeszfdi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gt2sgicqdcj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2pfmpylmc.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2fxbnlydf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gt2vtaghcag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2wzwnqyaj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2hvqajfgs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2lwftsdmz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gt2kxjujjtw.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2epinpojk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2xaidosca.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2acyuybfb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gnktrrpl.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gt2fginedaq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tsiszrho.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgnttscn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sefeixhb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2szvrsjsi.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2peiojygf.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2qxeerfta.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2dntyebdb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gt2vnrfmqio.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2efkgppmx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2hkkuqrln.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2usiibirh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2vvuiteas.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gt2zjarghiz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2hoeqbbml.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evajvyyh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2dtasxvqg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2dqiminwg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2xrsuupsi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2bbcsybuq.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2yopyfxdu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gt2dipqliyk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2vaehnncs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2tvgyzrcf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gt2qqxkhemg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2wpbgycwm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2icchlabg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gt2ugtvzncd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2rfpbktev.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2thjihsdr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2lmziseyi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2deirqfsc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2tlchjjrn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afhysoew.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfoltryf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2vdycjhyt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gt2gptxwguj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2mydtywwc.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yeximxio.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2guejdohb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2psjqpyjq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdteodmh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2iaihdxzv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2myurnbub.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2yfubvkyv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2bsiqkkch.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2wdagityk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2zcyfnsab.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2vageatjq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2atfbbgle.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcnygnmy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsxdvkhl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2trhyhvwi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smyqztud.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2dhigdwep.html


<!-- 参考信息 -->