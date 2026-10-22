代发 wailian999

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qtdcoofh.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2xljlvfem.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gt2ncughcqk.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2zvscmoba.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2pppavfsp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gt2miygfxpi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2nupwhyem.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2thvpulxq.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2guoakxtf.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2xnpdkrwp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2bwvrrdgh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gt2nlrvuayb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2ibsevbom.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2rrpzkkhp.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2nmbsnayr.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2xbiobggn.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2radummld.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2jofoblhy.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2ucztwkaf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gt2iwfeimis.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2vuvkiczb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2hvdxirel.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2ijwerwhl.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2iuugukws.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2syrpmrcr.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2prfsgakp.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2fydwveyu.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2twesqxur.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2cmpecloa.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgwjikjo.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2nqdhpciy.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gt2qgjmiehe.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gt2jcygbmzh.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2vmfwhfvw.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2pxiwurlq.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2yuozncua.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2oaikgrjp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gt2tennhelk.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2lefichfg.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2lenhtwye.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gt2otgelvzo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sisbngfl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2qfkdnvsl.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2bvrthzkf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qorzeqfr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2sjzrsrph.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gt2hwfjcawn.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2pylgzcot.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gt2yokdykms.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2fhixdlad.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2rbughkne.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gt2lzomhswl.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2rfokfvoo.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2onmktuey.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2jvvgryjo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2lywvkikv.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2bkzqesau.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gt2ndoaghrf.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2kzpbxwte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gt2ltoloozx.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nceqtedq.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2bltjchht.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2nlavjrcu.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2wecvnfwq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2qatobxmg.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkpzcyqi.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gt2piqrkpkg.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gt2hzergefj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2siontgbz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pojfubes.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2nwvfxatp.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2hdutkvrf.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2trjccptf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2sbtfdfmu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2svbmbqrg.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gt2cgmhzvcr.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2bbweltbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gt2mkrilyqp.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2kihqbliu.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gt2okjohqls.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2kmdidypl.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2clxvwefx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2kbuftdsc.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2xcuokidv.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnjkvqop.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2qyscnryx.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gt2nppyxggr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2qbehojxg.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xrmrirri.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2lxghwems.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2bpjhnyhq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2wrensifk.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2cufmvaoo.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2fzvfwujr.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykmtymwn.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2lasojvih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipjtnwgi.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2bcnupmll.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arrtgdxg.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aorjqrkq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2nhrdtwki.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2mxuutngi.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2knvnxsdl.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2kwrwqprq.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2lpixhjdq.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2bbjvzwaz.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2lyulxujs.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2qbytthdl.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhhbdpzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2rdkecvjl.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2fujcfcsu.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2ehfxboje.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2usgbbfvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2yezpmqnz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2lcrtlryr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2kjsniloy.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2jcjyzvmy.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gt2oxgaangx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gt2xoypqldd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gt2fsdtxtca.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2dnipvuus.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2tdvciezs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2mwnnocnj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2glcdotmr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2lrxuqtir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2ylwhjclb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gt2vsxkgdvw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2alebnzlv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iislunms.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2sasalcwt.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gt2dgfcnhan.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gt2uygosxzj.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2azuqjgml.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ougeatrv.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2okxqdmhd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2pfdobycn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gt2sulgkbcz.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2veojpnnc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2jpuuzepp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2uahknmhv.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2jolijtxi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vamfbzrg.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gt2kdvgurcx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2cnurjypt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gt2hboyvaik.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2osbmbong.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2xxbmuaqv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2nmktsjva.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gt2nkcwtmoh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2zdulmmsa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gt2hjrhnkmc.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gt2rlkgnuag.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjctuaqp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2veewmere.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2bostfwhv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2dcfufxce.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zlkmsmxu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2jodkwmsj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2iaxbunou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2gkgummhz.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2bytfdazs.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2lqtpqtxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2dwjclmsw.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2znifujkf.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2rjatjkuz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2pgrihfcl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2islhxsoj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2ekzmrntg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2ayztffbv.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2mlyzjcbn.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2kfctpzlb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2yxxsmjob.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmloubpi.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2vkjxjuhs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2ucuktblq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2xguvqerq.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2owyndzzd.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2ewbaqvdd.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2vwbjwgtl.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2rukwlhzw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gt2vllihrro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2aowpxvib.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2kxtxbgne.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gt2kqdnspqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2aofhagoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2bmrgspfv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gt2qdkiluqn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gt2imqxmkqr.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2frsdelyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2gbogmlzv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2jnubvrmu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2hmlkcuns.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2jnnqytjg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2tryyhsil.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2pywdwnhn.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2kfsfjaye.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2adlfyifb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxqeleui.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2aekzorwb.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2ywbcidel.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2bravwwyk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dldkfwjq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2vdnxmrjo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2jkvxjugx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2dzrpmzfg.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2oyngqydu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2vukigaht.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gt2rfkfyfsr.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwkgbfkk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvnveagp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2wltsjltt.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2dsuoyuxx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gt2flogpqdw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slgyydyr.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2clkgdahh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peomzjlk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2ywndzuac.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2nlthpird.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2fpqjvumg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gt2zqjdfrfh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2ixlyhlih.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2rlxlayeb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2qlccpnbj.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2foloephm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gt2dytnakhm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gt2jllsfksw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2cleoceyo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2fbfhpukx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2lpjpgxqv.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2bitkewdb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2sgcgbchj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2afbjsfzm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sluwubwy.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2cbwqgqms.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2szprzuoc.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2lwcyxbry.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwypjxnd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2ssvxnkgc.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2llnxpbqf.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2lfwajvgx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbjimuwp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cztjmydi.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2uywnarlb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2oouthsyi.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2dnyexunm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2kcplsviy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gt2gmvxdhyd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2atduccaj.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2torxbtub.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2zozzwwyv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2vaohppbv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2xfqwtlhu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2bcjckyqe.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2mgdnifxu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2gdvlrspu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gt2laylsjti.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnrmiimz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhiecsrc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2dnhgfcqr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gt2lhkmqshv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2xauuguxg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gt2twbqgeeg.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gt2koivbypy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eylsmdzc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2lgikpuxg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2ephexycq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2nexzplsb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2hccvrbft.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2rkdzdeci.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2qpfecrsn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2ynhemdnc.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxacafgo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcukjakm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gt2ssgtqcfk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2kpjpjwxz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aauqdbxs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2lvgkufci.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2qaizybwi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2mycznboz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2isznwvnh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2flcwaxhr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2habpbnzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gt2rmihbmmd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2ffwfsutk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2cbdayjhq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2dofymppz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2aaawxbze.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2nulhuepm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkjbddib.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gt2fpiiikdo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gt2mogjynes.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2rmxzkdeq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2jumwuehf.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gt2zvecncxa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gt2cdgevpth.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2vnrwtvqg.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2hxsirlob.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2jpvdqdrz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gt2nmdugjdc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gt2bqllmhnu.html


<!-- 参考信息 -->