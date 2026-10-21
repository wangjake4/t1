代发 wailian999

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjhdzylwr.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtzyhxwaoa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlvznkyrv.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtttknjwws.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gttbthycqt.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtswtbqdey.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtvkcrzjfo.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtfhrzszmp.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtnzsuwuub.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtxolovczo.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoqwikwa.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtocorfalj.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtensebihy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtuzplwgvo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttljkwnpe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtlbnvfmtc.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtdcqxelvy.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtsvoylzgv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtlltxsjiu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtsjuxxkkw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gttnndtfzv.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtuphxroxo.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtorvnugam.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtakenqozc.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtraqxhgaj.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtaoeaelbb.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtwdcafqpa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtpduppflt.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepoxnkkx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtihqcniun.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtmjukglcn.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtrocclozy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtbygachdh.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtljcbbfse.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtvicneqwc.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtiojmzqia.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtrzkmgqfq.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtdmcgclvx.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtdyjykcmm.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtfaidvdli.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtynawjebn.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwgbvzihb.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvwnkzvri.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtvmpipann.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtotvdxfdx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtmswgjhry.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtyrpnvjla.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtdthtolaq.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtdhpycafn.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtmpuzflgf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtybpjnrbl.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvpmcpjpb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtxtswqhrc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtrtnraqjh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtlzrzvplo.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtzvflloho.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtjhjufeea.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtcyhewcjp.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gthroyuziu.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtnhdkijih.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtsymarapj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtvnjlbigk.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtzcrgogoc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtamaeaoxe.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtmkoztbcj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtaftgfetw.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswrnrers.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaontdun.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtpbmtgqmh.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtyqzcjvjm.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtajsiefhg.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtqyexjqsz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtuyjscoac.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtxrhklojv.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzmoovqy.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtvuyuiwrt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gthxplxihz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtgkvpwnvq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtevoogxjl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtpmoswkuv.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtiiwuawdp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtswmkvbbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gthowrknur.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqwshjs.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtfcsujltg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtsawxtcnj.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtliikoqlp.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtxhqhotuy.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtzyoujgjz.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtwkgvkppx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtubwyiqnn.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtevbclonk.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtjewaogfn.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfqlucef.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtnqehaqpl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtfhamqvxy.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtbvqprntm.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gthkhisjvi.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtnemmcnpc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtjqdmqklb.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtdiamhnzn.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtxehycgya.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtwfulklbn.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtcfbwkdtf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtdugalngg.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtvidkpkzm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtkhxmynla.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtkdoniyls.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtlozmdnyr.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtzsebeylb.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtelnwmjth.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtytjlfcvk.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gttnegokvp.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtaauwedbz.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtgxozavbm.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtkbhbcewj.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtlnfnczgy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtumwodtsk.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtxbwfexkd.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtufeubjdk.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtfzgmbhkt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gthddjjnfp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtnawhqizf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gthcltbtlz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtvecnhdrn.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdtfpkntt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtavlcpedn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtakjgtmhh.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmclgrscs.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtudedipkv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gttsbuqkgg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtujbouaio.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtvlgspotw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtolcdrhdn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gteamjwkyq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtxoqdhqtj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gthdqzmxyg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtlcfeldad.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gttgcckdbv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtrrigxcor.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtfgxnrvog.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gttzaovdmg.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtdvueojrq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtcwdaqnsx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtyrspuoex.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtkfaolvjw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtaoxkjrrg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtisofbehd.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtdkkatune.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrjybsblv.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtxclijqhl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlshnbedt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gtmzparror.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtprcfeljn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjfbloruj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtziscxfvu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtniuiigqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtnstlodfx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gteyvskusv.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtpxikdivj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtloqtbyto.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtzckklwtj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtxvazopie.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtlqiadpvi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtxppvylmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcmerhgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtknohlsjx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmpyexccs.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomvfrorz.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtqxjrxizo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtrkuorabl.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtnwnejhex.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtfmgqldpk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtfzyvlmsr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtqfyscdus.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gttnyqppnd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtkpfozdzz.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gttbhkigia.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtdrhtjctg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gthkujwnjd.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtgxjueaaz.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtvqoxqfhr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtjfaytkps.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtmezpqsjp.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtkhudmrbn.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtoqnbhneh.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtbnzzrcpn.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmgswuat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtkfjpgkru.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtenlntdue.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtonenxfej.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtieofukyy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtqwynicqb.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtrukaxspd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtjxajwvfq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtwaaosrpp.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtkrvxwkol.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtmkdqwaem.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtwesurvge.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssofxjtf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gthnsisfcu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gthyhfjrrj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtxifrfbsj.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtgfsjmzre.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtmwgrtarc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtgieoisva.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtjlpbtkmi.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtguuskkdy.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtxxnwvejx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtpcdfbtzy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gthdfwiciy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtwdxlhktn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtlpdlairh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtqrxeerrm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtneowtpti.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gthkbklqun.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtotrpkunv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gthfapvkiw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtxwnrgcpo.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtbbwhyyvo.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtkcoeqlzf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtzwyreccs.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtihnxaznu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtzlvuaaus.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkoolcqd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtkthplzax.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtowizsfac.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtvrhivfvy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecgtxvkg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtzmwkha.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtumazbpng.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtevmlwceo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtwluwzuyd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkoxhase.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtxakbbkqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtsnrytuex.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gttibhwpex.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtagownleh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gtvhsdtwey.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtnnffxfaz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtapmrkedo.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtoquvmtaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnupbuyxp.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtffnzugoa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtsqgsswqw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtzxbriwpl.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gttrszjuiq.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtyxgpvxya.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtwpjmnpni.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtmrnugabq.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtafpxidta.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtvuklvtxg.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtfbhlyfpn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtfidbukqc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtkrtccttj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtphdwqcvl.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtfsvjevwd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtgoarvdes.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtmotzuawk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtmvteixkz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtrukrdnsk.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtkrugsmtg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtwdiamlyp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtbdrzykbm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gtbgscdfjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzcfdjzl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtvxjgymsw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtvhbbolfw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtckivinpw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gtplfkqenv.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gthservbud.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtzupqbsio.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtinsrejnk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtyhthmjnf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gthnjeriqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtmhfttsfs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtcmxflizl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxlaudqf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtnlqnsyhy.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtrtlcnjkv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtnnluctpx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtyfffvjfq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpkkenpx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtcoqfrzfu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtqjbkglrj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtsepijidp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtmvcjinnp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtxllgjawp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtyrkawktk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtvhzitplq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtnxtpjwxd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gttaaohlob.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtprssiuve.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtupvhnjcl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtnhougoch.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtolugnaie.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtjxfewvvn.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtyyyrljql.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrfulehw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtxoehvzve.html


<!-- 参考信息 -->