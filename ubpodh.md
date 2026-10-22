代发 wailian999

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgzjwosg.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogohqmyq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rtpbhivr.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpyzehje.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gt2xlecsese.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2fkorrttg.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2geykyeta.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gt2dlrgixsy.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gt2ahxcshyu.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2kbkjhvxs.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2nfvystsh.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfjzjycy.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2bhewbemb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2nflhwmng.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwfntjsn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2pmwagucn.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2paayihhi.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2lpwidpcw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2rbwlpumw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2ikhnrbkb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2xogeoygu.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gt2jsjewzbz.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2tzjdopmu.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2vuwohkij.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2sruphzhl.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gt2zzoxdcwp.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gt2zetqccxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2ugngaubm.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gt2urlhcomz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2iwlfnvrb.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gt2upkjitpz.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2ldgfumgh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2mzmhusxg.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2ueemvlgn.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2krxihfra.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2oqbkqbtz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2daxveqor.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2rebkxdbu.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjflsdgi.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2axvlwski.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2wgojnyba.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntrpxybt.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2bwvqbnkh.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppdcuyxb.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2iallpfgr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2xtvwyxvm.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2byhaxjwz.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxbvxbgj.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gt2voehugyq.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2uumvtzcg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2tnsnhefo.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2juvgaarm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2mmbikvuw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2iidadeev.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gt2xqlqduoa.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2osnfzgfh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfthmpow.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qktmtlyc.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gt2xfrccvtr.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2vkbmodme.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2qrdhnxia.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2ntvyfsnk.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2lczjvjsj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2rzlvymdk.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2rguhpetg.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gt2iilvcmoo.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcsdbfdo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2uxvuqsdk.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2obexdhua.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2byteujby.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2irzyvgcr.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gt2lvyyakpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gt2dbsxbbga.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2onqmtxqz.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2efdossbf.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2qddetsuf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2augisgsd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rqzoddgd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2aeaupuru.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gt2fhphpfnc.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2gpeecofp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2xnsarvbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gt2nfggkjrx.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2jkwlcwjr.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkhpigor.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymhxzgvb.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2oezmcazx.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cejnmjga.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2oaasckrf.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2elmhbuzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2tcalvutb.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2lautlhzm.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2owbdmfhb.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2ovzidefq.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzzbdsxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zxaxtijf.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zfhfnchl.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2hjqhkffs.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2hqnfwfog.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2ulslvpep.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gt2nbyqykmp.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2jujdblpu.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2tocrfwel.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2rydtyuub.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ykdcumve.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eyptbuyk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2jchegohc.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2rlfpykny.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2dujfqhly.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2diwrjwsa.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2fmmoerci.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2jsdywdwp.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2foinbwlx.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2efswkxyz.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2atqrxjkp.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2eaxxarxz.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2edhdzdov.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2kynxycre.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gt2iuksmkoj.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwvkwgkn.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gt2sjzcqsth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gt2nsmlqjvm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2rtsejfqt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2giserwxw.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2qehngpyg.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gt2vcxzrqyo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwxuqdwf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2subzvdsq.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2uaainyzb.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2jyirsfdl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2firomows.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2pgejsaoo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxkqaljq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2leqiptrj.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gt2kogzcbez.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2uzpbemst.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2ibsmgysz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2ahzaxvei.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2cchyeaoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gt2ltxyhgul.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2icvmulla.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2okldhkyn.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ttrfjldl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2czmgijuc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gt2yopnwqjf.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2wljmrfar.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2zlrokljw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2yjcgyyjl.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtkfrumb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2bybxkcxn.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gt2hldjgsjl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2lrgoakrb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2citcdyde.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2bgyiyseb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2kmyextis.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2khxzsbpa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gt2kfzlvwon.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gt2stizgnls.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gt2cwwpxeiu.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gt2vnjzykfl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gt2qrtjzbqr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avsxzcjo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxumgkyi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2cpdcurxs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2izmxishr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gt2ueaqtvzl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2moxmfqgk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2sryfkvzp.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2aycvrjbz.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2tyvkvyhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2sbzcljcc.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2qspbxwuq.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2blcslwoo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2kklramdt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gt2iffxbiag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2qummhgiw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2tjulejif.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2xuzdnusa.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gt2areovvir.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2ihknxaqv.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2xpznthkq.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2lskpyple.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezqvkjsi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2rifyghbz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2vqakswil.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gt2ooxzslnm.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gt2xixdpebf.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2buvqjtdx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2yfvxtgph.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2cdodbwpc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2rxyuilwh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gt2cnmsouns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2touynspy.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2wtltesrc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vyftjtam.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gt2dosndqfi.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxrtkhvh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2rupltcqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2pqisvhdz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2gyeijnrv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gt2chgipfbx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2ixdpfdvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gt2hhhsqxqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2qdwjnmis.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2lpnaazsv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzfxuimg.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2qezkosaq.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2omzjxilo.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2nmaetzij.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gt2smomgxbo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2jrxecgtg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gt2vjtyvbwt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2dqgkljcy.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2lcmkoqlc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2razsumgy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adhvmayo.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gt2mgpxehsa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spkzoctx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gt2fwubgrvl.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gt2znjikblo.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gt2cpahwlki.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2xhfnkwla.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2nkxjndba.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2kfvqfspy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gt2awtmlmco.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2jkffcqet.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikchwcqk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pdtmedyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2mahdzdzb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gt2waefysij.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2smpifpch.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gt2rghpwchi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2qrlvqphu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyathbxj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkxmxuqa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2apxspckk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gt2tocolghe.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2vmhqfsow.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gt2kbjcxdnr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ospreiri.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2iwqrfgaj.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gt2pmpaqszl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkftsdca.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyfcqtrh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2xolvajyo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2vyxiemxf.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ghjzdntd.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnjqpmiq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gt2eahzkznn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gt2jqjkxqzt.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2bmmurdrr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jukrwgwa.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2repzqbot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyysvmbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gt2ltdlgepf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2rpiyfudv.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2gsizjtnz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2teamsazf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2hzbnqtfv.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyxdarqh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wnvdhfbs.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2whkeuhbh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ckbaqfrl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2haepzyxf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2xdzttgau.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gt2lbhirriu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2stfgjdcv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2yjxjfjpy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2qngidpkm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2htexzqnu.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2xicawwgb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2mpxchesm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2lkqlagzf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gt2nfbhzosx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2rwiflwnu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2dgzsnbsa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2htqbgrhh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2ndrcgiys.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgsusjtf.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gt2cxrdeemk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gt2rqwdbmle.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2bobsprlg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2cgeykvle.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2uhgaqgoo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2aqlogoii.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvbeyru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2dqfqevni.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2naojqhoh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2zguznvyl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2jyrfvwzy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2ntmhhkrp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2xjhxbyiz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2whsdorgw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2sbrbldiu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gt2rihwkxpj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gt2bdkmceap.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2nerngdtt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gt2dhngaaxn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkmevdb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2ziuusbql.html


<!-- 参考信息 -->