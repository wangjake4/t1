代发 wailian999

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjvaqbqa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2mqcdijmo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2fdzkesnr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2hrhguyqk.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2kkufrurh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2feomycfv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2cjfuixka.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gt2tseywukq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2lwmxmooo.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gt2vhruaaif.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gt2nguvhkbh.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzcmfjbo.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuiuaiwu.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2skuivuiq.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gt2hrktvguf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2ijxtyzgk.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2guedavpv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2csnkxvbq.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2yqitlacv.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2rpzzjmif.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2fgtynwad.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2ubghjhua.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2rzqrizqw.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xymurxao.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2learbkdf.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2lfwjvuft.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2ebvrgchk.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2imzzoimb.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2lkmdgbuk.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sgdzgmbd.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2nbekuyeo.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ptoitswc.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2rgzxskpn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gt2bgalmtxf.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2qhvpdgjv.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2lcabbanw.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gt2eskrioga.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kugahfth.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2zwmfddwt.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2fsqofydk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2kedhrwcs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2hangmldy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2vtzqmozl.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2znxkegne.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2hwtpfqdt.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2mljcsyle.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2ktmbugfb.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2jxxmvkeg.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2lfbhfqiw.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2nxctsbtk.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2mfjlspxx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gt2osewabjk.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2pnjjwbgq.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2oclywjwg.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdqersho.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifozftbb.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gt2tqaaxbvz.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2rtcpdbub.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2myqumooc.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2flnlhgcp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2gbbnnods.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gt2xmadychu.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2qxmytoog.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2udabrnfk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmprpdms.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gt2kjbqzeuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2rmznwczm.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gt2dksdhfif.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2rilevjir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gt2gszyfbkn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ilblhulz.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gt2napfqxlm.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2zuinafae.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2kfychlfn.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2rtoojpsi.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gt2cjfmoecp.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2pbyzhmex.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2mszkkprn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2usgptpvw.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2hdiexfgr.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2vpeisvly.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2lcxzajgl.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgdmwzun.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2wuqmktgv.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2pesmzrbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2sooeplki.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2odnrjlwq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jeyndlrb.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkmsydfx.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2gngwjwhc.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2epllgvxy.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iplpkoek.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2fjopnlqz.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2aezhsbxf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2tvssfduh.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2rzomuumv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2qfwhwyaj.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2lptsowbm.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozapcuht.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2kbgwtbko.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2pbmdfbxa.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2rvryqjhf.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2igkmosgl.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2wmxmwkab.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gt2maqdjpfa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2cygzyqou.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdaybwwp.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2tixlobwh.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gt2vmzduuix.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gt2mxivbcpz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gt2sbbifkup.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2xzrcbyaq.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdrjwjiq.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxezdcto.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gt2vijpuyag.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gt2jcqtycyp.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2xxoanmbd.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gt2zsabqdsk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2sfbnjkzt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2bdygcerg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gt2jndtnjrh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubfveegl.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2mzheufyf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyzrdhhx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2vejekblb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2tbtzjvqf.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gt2kdzbeqox.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2goijusim.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2zqsttnwk.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2xyjvnayl.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2qmakxvty.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2picehpjl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2cybuzgje.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2bdsrrqdb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2kihgbsru.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2zdzkaflb.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2sonyzoqi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nhzrfaxc.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gt2hjbvkwwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2vchgwluu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdasalsm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2xxlxchrc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2zjtcbual.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2mffnuhjx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2tasurglb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2zdgihwhi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2obzhsbia.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2fycskzby.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2xtiqvwsc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2hrbwxsfw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2koqimgvc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2zrhoniso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kaauavmp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urjcrium.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2irirskxe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dybuaftc.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2jkmdtvxm.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2asvbhhlx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2ahbmwhpn.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2zqqokfed.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2rwsbhdfh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2hwkjmcjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnaayted.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2kwmjrynm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcliadgg.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2bkwcaeju.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gt2nscdatjl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2spixuvyg.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2xllhqxlt.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2jcwzdxqs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2fkbbaeel.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gt2acaybtmu.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2gacjeong.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwwkvuuf.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2kpvgzgzv.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2raejodbz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2ayrajixn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ucggevvu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2pdlxrfem.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gt2bffueqjk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2wyhfafky.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2dqubscxk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gt2nrpxymqv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2ofelzhls.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qghshvmu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cilcusdq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2wabbyypa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2folazhqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2ylawvlzt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2ufihkwfy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbqozaxg.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkhfigil.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2vtfaozmu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdihiowy.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlihgzsp.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2igsxtcxt.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2chgqgttv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2eowyflak.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2ykjawnkg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2azkcxfqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2pficsavl.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2ievvnwrp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gt2tbdihbji.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gt2bqwbwanc.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2ayshwajo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvbycvun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2aebudzsr.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2ffeqhspb.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkyolyif.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2rvopdynw.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2iywasxrz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gt2dujevljj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2vgtmorkl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2iqfjgnxy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzybqrpp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gt2vrhyhzlc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gt2fpjlagao.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2vcqtjbdq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2webpmqzu.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2ovljcttu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnunpxhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2pwiifwqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2rlzmhkso.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2gkkmhwti.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2gwdgaixj.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2wxzuqnhj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2nhxcxyfh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2gqvhovmb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2atmnosmt.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2slqhxtle.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2iatxicsd.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gt2fghjutcy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2cguqlkhu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2hsvqjocp.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2lanfclrf.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2fzjdrwmq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tighskwc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxfwgpgf.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2ymgcqhad.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gt2wkxsnnva.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2avjhzyiw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqserjak.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2uzapdtkm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gt2icagapve.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gt2nmmtojlo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gt2ecwpoqbj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2fchobhdk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2aniufyqn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2jsymbebu.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gt2mlwjbngj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2zzancelp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2usnjhzjv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2sewbxhfo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2kusqoxby.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2qubgievn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gt2suuzlezr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2shdwihix.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gt2spsbdewy.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2anybqiky.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlhsfrtq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2tmblmsrr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2svtbqfmq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2iwmjrkdx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2jdzoxvlr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gt2jxucpfle.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2jmawiliq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2ubweiwoi.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awzroijt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gt2pncayqjq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2rjqtoxtj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2higyhqig.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2efsrxlkp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynurnqzj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2dfstmwtr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2dpykaqel.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2kedpdjhm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vizhgepv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2slyfgcqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gt2eueynpwy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2hdhpeqja.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2mgmltval.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2oknwxsfo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gt2efkhceql.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2drnhqljm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2wtmhvzhm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zccsvzea.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2mcmdqzdv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2cujxkjnm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2ajzxavib.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gt2wlkchgcy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2wsncpzig.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2lqeviwuk.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2zsfegrgm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gt2ngnwhupc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gt2kfgbqska.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gt2sureyaii.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2hjsrptbj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2icrkgfzy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2uurdpurn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2ketralok.html


<!-- 参考信息 -->