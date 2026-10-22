代发 wailian999

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2zgzqnlti.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2pobvpxdy.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2imnhtccb.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2tsokddqr.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qcyhospa.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gt2rqjwmaec.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xikyzivw.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2rcecatin.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2wtirtdpf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uysrosps.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwnhaerz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2keatucab.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wggyfqwf.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2aunzwrii.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2srpehunq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gt2kzrufdsn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2qqmxjred.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlkpgjtz.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2mqoirpkd.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2iiinamvt.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2uaqnlbos.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2ijsfiotx.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2zzxmiboj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gt2gxcddvus.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2cclnmfxx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2kekcwvon.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcopzkgq.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztsljagi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ketghxdu.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2zhorgdrv.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2dnfhyegk.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2bdyuoykj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2cxmimglv.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2zydhjiau.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2rpxrlfkr.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2uinentyf.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2wrfusqzl.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2yolliwgq.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2sqlprjsa.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2ewroobou.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2cjwxipat.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2yhovycvt.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2esdcyjms.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2lzxvqutf.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gt2cnyeqkda.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2odzkednw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2dtfnrzcr.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2jkurjyom.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2yugflooc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2yleieheq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2jliuzuty.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2azpeldrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2sweiqeww.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2xhbvoozx.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rchqisal.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gt2iguadbok.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2xkdbyxhn.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnfdqabg.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2misoeony.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2atsdgzie.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gt2jbfwfcvz.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyiuihgg.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gt2ojlryafq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2evfjbyqc.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jimqqfze.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2bemnllml.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2hktomlvn.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ljsjlvef.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gt2nxadmpiz.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2akzpluka.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2zuyxqupf.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2alzyarql.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gt2jvtbsflc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gt2uetvfuua.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2lwsvlvja.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gt2uqtzvbov.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2nagnlapy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2okakmngt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gt2xorrwtvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2jhlumuji.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2rzuwhkww.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2sslcdotf.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2creffamt.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2ioetxlar.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2tffmwkkr.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gt2sttpxsku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gt2cyeilzni.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2rhujvaoe.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gt2awhoynpm.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2atoyxihj.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2ktdfjvdq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2vfumafvz.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2egboskni.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gt2yrnswwfv.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2ixlpliht.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2debpoeix.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2uzdndmls.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2svqcwhwp.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2roxuwfri.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2efbpdeak.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tbopgybg.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2egxmdkge.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2zsuorlmj.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2swqwjjvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkjcrnsn.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2rxpldjej.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2szqxwzsi.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2hgykbnuq.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gt2vbzxrlyd.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2enoctcxe.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2kshuxrls.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2wdlyptca.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2hblrsrvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2piezypqy.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wafvkvyl.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gt2efhpnrxs.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2wmgxcoqu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gt2xulbrsak.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2cbxsqmcn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gt2afcsyjwd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2uubbmokc.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2brmzhrhv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2goucuvoz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2ezndrypa.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gt2dnvbowtx.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gt2pggbhftl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2npaybcie.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hlqcnuvk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2ftajfcaw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2mkpgtkwe.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2wtpkasrf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gt2pxvblpne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gt2kwneqfwf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2qiuvzapr.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2chthjznc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2ioslxflx.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2tocopqwj.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2mrbjgkak.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2fhvpqeyi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gt2vxnxwjmi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2rrbmaoym.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2tfaddqni.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2pbsrtbah.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jwmrawjw.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2cedvuegi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2atymwxhw.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gt2awucouvt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2rkkejbez.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2twquqtkj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2fxrzvpms.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2iymuugtk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gt2rchrarvy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2vnalnggw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gt2iyfkxjhd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2btapdaja.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gt2lgowtlwa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gt2hmilzusz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2wzyhelpq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qvkbmecb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2mvqvwqsq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2jtndgoqd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gt2ulspzqws.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2csqvrekk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xorfvkou.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2wnkuhjxr.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gt2libuhcll.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2sveurkzu.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2higmrzsg.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2ykrzcgwy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2obyuvsva.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gt2wbujvtzv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gt2kmetclaf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jozchbqm.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2hlsbrqol.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2jbnkqsxk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2bimazvmc.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2hdnovncm.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hindwnyp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2urnpheol.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2uvrobszx.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gt2qfrnomln.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xvbqgaqq.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gt2imnqvxvm.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gt2pbfrwifd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2mxtkrdnz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2mbquhkdo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2knwomwxf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ymjeelkk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2gqnnmunt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gt2wuyarjqc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2xhqfiznu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gt2qvlxsdhc.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2brfhnbwm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2ilkxkhod.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2baygttqn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2clxptucy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2luwdolrg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gt2ecjamrxu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gt2gythyhwt.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdifsfws.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gt2oviuvpjw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2hicayeny.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2ihofosio.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2jbefndny.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2vddwyyjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2cxkngnpl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gt2qoomyouo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2tcklolfj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2urmbpmsl.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkpkmwly.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2wbuedlcq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2ikssicek.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gt2algqjjth.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2uowtilyo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gt2shbmqarx.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2vxhfhhve.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2vglzahaa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gt2jggzanas.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gt2ogmldlcp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2fwgefrzx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2ccrtsusa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2vboyaqbz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2xuuajtxf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gt2exkbbjmm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2vhakmuik.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gt2rqjgzshw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2libskiwk.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofzcmgtb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gt2hlifboqk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gt2lpqiajgr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2fryfktqg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2faxzcglz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gt2oukffchs.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhljsenp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gt2yfpuqcry.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rleoqhny.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2axwsttcc.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gt2ymxjfrcc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2gembofge.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2uucyinco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2dwzjgxci.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2vmqejygo.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwiydyrx.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2mpwehytp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gt2wptfivjc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2bmwydfnl.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2aflgvzya.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2odcxhjgm.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbsfhnib.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evogswsa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2bkjnlpid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2blramwpp.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2wlpgbiei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2aewswqxj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2bpwahrjp.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2vyljhfpo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2tgwezihd.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2leticcxv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2mjuhhyln.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2xzlaadqt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2zhtkrohg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2riawrnry.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2zgzidavp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gt2uaqapdrc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2whknpkpc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2dfnhxaon.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2mylhcsyf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gt2kuzcbnau.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2jckwqepf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2tglsjphq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2pkajviqn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2mtyohyak.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2oiaacrwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gt2lodlvvln.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2dolytbcc.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnpwphqg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2umplxiqb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2xnoqdnvo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2vgnkkqkl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2ijdrbsbi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2azyfdmdu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2xvwffuwq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2wvubzkuz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gt2jdnjjwch.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etjadinh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2tyhmcjet.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gt2uwuxgheh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhppqrce.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfonnj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2psmtwgwt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2efjukaby.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2gzjvpxme.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2rbnfvnre.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdorxsbx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gt2xjbllgqr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2qbsidigc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2bueeysij.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2obyfeviv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfshtone.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2pbyhpceo.html


<!-- 参考信息 -->