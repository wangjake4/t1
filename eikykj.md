代发 wailian999

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tunxlxts.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gohmtjlv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jkauusbq.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gt2wkxgimky.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2krgvaefc.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2svnfuiob.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2usccaprm.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2esfyzksc.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ofmetunb.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2lyzdobaj.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2aknaladz.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2tgejocwt.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2mghsdsnc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2mrugnndu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2qmhifbzl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vejfbqjf.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gt2axxibatk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2bbhqilpk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2pgwuaily.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2twgakqpf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sppgfcos.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gt2rkiarvym.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2jcobfauy.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2rvqsevrs.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2muwwjnuh.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gt2pknswsff.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyuxzlnf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gt2twprebuj.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2pfoqmrcj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2ksfkhair.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2rkuycyjs.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2arofwtol.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2kgpjnbzm.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2pczfofbt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrevhfud.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdnffucd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2iklyzjid.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2mldvhfxo.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2crdzvmpl.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2fpxipdps.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2flztlmfc.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2itpikplb.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2qajvwkua.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2qkxwmcig.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2ucowpgay.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gt2nleefobw.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2uozkteyf.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2jgglgslm.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gt2qttkyxqh.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcxlgnsh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hidfywai.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ntprleaa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2npmngyxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2aogintrs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gt2zccdaygr.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gt2gezeqtfg.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2ognreaco.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdepeefp.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gt2dxgsaele.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2urzitvru.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2fjqcwjso.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewxneaiq.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2hcxtftbe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gt2ukkoweed.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbhozkkw.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gt2vrvmjpna.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2gdnhmare.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gt2cisshnkn.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2vmtlhkzf.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2rudotlfm.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2yzgotexc.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zlbwfjqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2okmnichg.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2cegvxgkp.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gt2ouktmkdv.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2lyvnwzbm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gt2qkihhglc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gt2hhtdltql.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gt2vmclyuvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2czghvxrc.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2zhmwdlvz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2ijkpswfk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2vnkvdsdk.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zmbuvtsk.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzhwumhx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2trpumlfl.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2fatqykut.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqsxeijz.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2lgkekmyj.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gt2hgyibvxt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2dovrndjd.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2zwelaqsv.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2xaafsjdc.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2ahxmjdel.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2xzbvzcqy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qodschdw.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2mkgjtwnn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqfnlbex.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2nodxvpxc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2oirzuudh.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2qpbjfngp.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gt2mtorsscv.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gt2sfcfxkqw.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2fcuryyck.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ocxaxvuj.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2eyhocdzw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzfflgkv.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zungyhax.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2ymaeotgh.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2tyniygmo.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2evnbymsd.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2grthmhas.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gt2hywqjzti.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltrlbhed.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2yjntivhk.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2vhoesswp.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2vgyhiwbz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2httnwtaj.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2wuqsbeyo.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2sxtcfknq.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2wxzqfqdv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2amzawkhy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gt2rnfmqacq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gt2guavpabh.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gt2jfwgttnz.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2erpvgxwz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2mejarsec.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gt2loaropci.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gt2ywqqrdpm.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2dplagijw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gt2idpaupdg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2vdqarmyk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2aievctcx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2kwrgwhra.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2xnjcqliy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2xmyaypcj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gt2wqtelnvv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2wfrbqefv.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2szinfiun.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2ddcjlnrj.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2noegonti.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2dhttuabz.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2wyreyhvv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2gbktowvb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gt2civxmjwl.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtcrstjd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2uvmaellj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ebjsfaic.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2utifcnrv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jltxzhnj.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gt2rtmxbelx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gt2hnxqlvuy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2cycmlwti.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvwxmzhk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2uhcfscbp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2vhctvqwm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2sqdexdbf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2sxdbcoqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2uiqizhsx.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2obliwqic.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjudhuk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2rjzmjfca.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2sglvyhaa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2kogqucbf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wrusnflx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2wnjvfcdf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2vdkpcyay.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2qtclhhxc.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2jgrqfidi.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gt2leswgrvo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mblekiop.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2elktwzmj.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2anijtdoh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2nbhtzqtu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2iagnbqmk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcnhfpri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2pzcebdbi.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2yhbyrwzo.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2mjerglwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2zfsxppkj.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2frmvfvbn.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2xkwlyepe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2dskutpsh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2nmxpmsyl.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2hjftsezc.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkwwowfc.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2ozjprsfc.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gt2yzypznyh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gt2diakebrb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aegmnfir.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2ihdfbshy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgkrvosc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmimlcdm.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2kaqpcpav.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zrnlpmiz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gt2brezvsqx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpejaif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2shvdfkok.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2crildenl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2mxoxedex.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gt2wvuovera.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2qnwzvuks.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2fuybmdhh.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gt2kjzdqxtr.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2twnqnixg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gt2hiooihiv.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2aplzcnrq.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2aauiymeg.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2iytgidxd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gt2uuyhbklv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2urjwbzma.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gt2xmtrikoa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2leljtuux.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2vmenbshv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gt2wbhoigrf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2vlcyohlw.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2ogdcvspn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2layfbvky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxalcazi.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2dfymphfx.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2rliitgma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2bbczamnu.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2saftwzgz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2tdtnwivn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gt2nmogmsde.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2bpstkzat.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2dpmzyeal.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gt2prlgptud.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2ymylzngy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gt2isdrsqmj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2awthesyw.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gt2tjtwnxpf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbrwlqur.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2bgvkxhrv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgclgvwa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2maaronaz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzmkkpxm.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcipbhxo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfwcnkie.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2zjutcttz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2kmqmrqhl.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2murolamf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2mhikorit.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2zzbcaiyw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkwvbasl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2wpvkamcw.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2olrigxuf.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2ynbixuzs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gt2ptxwabjl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gt2lmkrqtww.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khetoyiw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2eyrakmuo.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gt2rthizmmi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2hoqffzum.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2uvrrpbzs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2piqfsblg.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2cotidhyx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gt2adcnqxzj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2qshtlubj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2jufpwcoh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2hixughfv.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gt2ajpfweby.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2yngovjsc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2nlguoehd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vydgggpk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2jgvsymie.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2xcjahjrn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekefvlyd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2xlmswkwb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2javayvpu.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2vfmymodh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2uvfzaitd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqzeybbb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2tutyhafc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2lvyiamtx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2gxxcnabs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2numkgrwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gt2yqlnqqrd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2cmmmlxxq.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gt2aemawipz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gt2rajygqbb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2yyfihfvv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2umzmghiw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2mrnawjoq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2fhsminyk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2chabdocj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ixnnxyzb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gt2hpuaunnc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2vfcrfesa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2mcsjdvzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2gzxrbaqx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2qafmffxe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gt2hlvpwsbx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2ekhaolyc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gt2lecenfbu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2etbvmozs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2megwosph.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gt2qbqlamiy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gt2xxeywmek.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xirejape.html


<!-- 参考信息 -->