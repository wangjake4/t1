代发 wailian999

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2aporodtb.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2vhuswphq.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2ybdckpwf.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2hedrytdn.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2gylhotbb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gt2bqsvuwex.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gt2tjsjotkf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2qeogwoby.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwfmiqli.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwsqdjq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2cpbekhsl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2ofgnixjf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jatkrknr.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gt2zjhiibnm.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2wfpprufs.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2wioqzmom.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2zboyxuvi.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2ovdjgxfg.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2jxgousxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2zovxeeag.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2kvuvodmo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2vxbssnuv.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gt2vjdxfwvx.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2bdynljbm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2ffmpjpss.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2exyudnua.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2bcgrlhmj.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2wgrwzbtd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zoillznd.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnxfdvfd.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyomfdqr.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2zvfairvg.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trjhjlnm.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2iadglmdk.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2plqwqoio.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppzmeioe.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2nqbwdtif.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvowepdf.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gt2gesluhmc.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gt2xkrxfzif.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gt2oigpizdw.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxhrtygo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vvsfaqzr.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2xefegsxw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2diwxxnwi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eukdnjeo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2jaakuqkl.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icjoemri.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2crkyoofx.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2mecygbtx.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gt2lmdmbrzu.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2vsdrbmar.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2ixbxgvcq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eeelqaqe.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2xlmqkidx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gt2igquywda.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2dppunean.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gt2wokodsfy.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2jxgwmvta.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2qrcvzrob.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyjsigok.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2zsffclfm.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2aldpnxnv.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2yygzcjed.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2axllyfkb.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2zaczakyy.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2ruybjzow.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2uvwkylgq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2qnhdwqah.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmkofctp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2nolxlycp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2wpfyelal.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2tjlpeett.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gt2fiqbfcdu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcbvqoza.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2piixycnk.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2pdrikarh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smfnarrd.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2ddigozuv.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2yieqfyqe.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2bjpkkdvg.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2jgahukjg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2mlrimegp.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2ppbjnpcr.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2simsikqi.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2uiupyadz.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gt2thjwukau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2flnnsgrn.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyeyhskg.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vzjwdxup.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2yeigappz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2ycrqgbhx.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2erysnkxv.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jeurwaaf.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gt2kshowanj.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2qeujiqrz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zgzzmnjy.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2nnspnegv.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2krhjwsqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkgnigtj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2cyryouow.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvsndkhl.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2obevvhti.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2xfuuvsfn.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwpnadlo.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2ammgtktd.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqsfjmfr.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2icsyizen.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2ofipwuij.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gt2nvcrhbru.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2kmwgwlty.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmuhofst.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gt2ccxyfrju.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcukraat.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gt2wgaxupec.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gt2hzczckcg.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2mytmhnqy.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xsrzpfdh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2robyfavl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gt2fbyrfkjp.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2rzuepqbi.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2mlqqnkfc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2oaocfger.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2kewoaqgb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gt2ukgjpgld.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2dgasuqvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gt2olibobkk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gt2vvzoriai.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2iasbbloq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dabjeogn.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2zobbvxjh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2petgmnse.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2usiycdkb.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2btywcrwa.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkgheeuf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwxgoksn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2mbxbokry.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2jujmagby.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2ephgrlwz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2qnvfaanj.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2socmwacd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2qinqspfr.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gt2aljemqms.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2wevmsymr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2uhnjrnhs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2ufkoqryu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2llctlikx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gt2klqzhovn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2qrrouryo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2verrztvx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2kdjedzgq.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2gprmvkkf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2kloqzjwe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2euhyuvuw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2hanjefop.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kbxtqkxy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2vzqepsyg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gt2nhispnrh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2kvuxkixy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2uxrwtjxk.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2dnghlbqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gt2vvuhqkre.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2clmwyrsw.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2duhjzumf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2pnuqeqhh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2csbgtgou.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibpezszq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gt2rxyoxqaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2jjunjavz.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2brvuochl.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kchdichn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rrzzwsce.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2iwhpmegj.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2ltcjnjmf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2wsclxxig.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2uvtupeog.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2iecpzsxt.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugkldzyx.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2ytolieit.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2bdmqrcnf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gt2fbmatuua.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2diitrwqj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2dtqbqpaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tlvozzvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2yniohdvt.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2ytggiwen.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2pjvtpdeo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2mzqkoqji.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gt2erqpxukr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2gitxjqcq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2umoqncws.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2vvglxvso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gt2wrftelmy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2kqrsxepn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gt2btntsyuo.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gt2vrxpkhag.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2cnthcanx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gt2iddjdypy.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpnfvljd.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2uohwoies.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqnpekfk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihqbyxvx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gt2cdesnrhh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2fwjagcdl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ecwoqags.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynzjesaq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gt2bhtrdbrc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2ylgcpkqz.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gt2pxfpdkqm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2omkumcif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2mdcmpjki.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2vkkpzdta.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gt2tvssdqej.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhtmswgb.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gt2advrhhnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gt2hbxeusnq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gt2dcjkfxqg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gt2xwyoowhb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2fbiboylm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gt2mzxrlpsp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktskwifk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muoayvqn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2cedzhepz.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gt2rhjymmpm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2qnegtjon.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uadhmcfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2bsyizzie.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2xywdwqdf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gt2zolvnvjs.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2dijmrkab.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2vouuurlk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2fguzadtn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2lbmqbzfa.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gt2wqyaeyzb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhddgmpf.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gt2danjduhc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2hpmdaskj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2iagtrujy.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2rlescdjn.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2zoqjdspd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2vwpduahi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2sjsguqdp.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xybradao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2trmdcfki.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxfkuqji.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2gwwhqdnu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvtxkhxi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2mzeuzwgs.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2toypxxgu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2yvijzcim.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2hvhfbkal.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2casteoae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2xcalzmdw.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkilghii.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2jnyyoyvt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2wwpyestj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2tcjkimji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2bhdimykt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2mhqbvogj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gt2tstcihow.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gt2vwdewbiy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nomltmib.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2ybjfqksf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2dcafteng.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2xgeyixhq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2gkuktgkk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2umruelmw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2zfbxntpy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfdruqv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gt2nwcqtili.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2abwqnhul.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2gzpwzfbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gt2kdjubhvd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2dkwkoxjj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2whgdptwq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2hbhbwptd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2cvuhmpzm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2dkmwierm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2cykgrweu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2ktvyndhg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2baalfqsx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2townucen.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gt2xvmqzquk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2aajimzyl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2gmhkmgam.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2utsyfotx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gt2ohiyowvs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gt2httuinva.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2tycwhdbk.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gt2oylzyocn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2wcoewkys.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2huyetsty.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2nsyujywl.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gt2eupkqsbe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2zdatxdjg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gt2trhzpsbz.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2hibqcsme.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gt2edobdcpb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhsgjzdl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gt2qmgbyazf.html


<!-- 参考信息 -->