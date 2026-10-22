代发 wailian999

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtlfiacxxy.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtbnpjtvwm.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtimjqogmj.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtbmiprpxh.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtckgbuesw.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtswtbccwt.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfwbtmxs.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtvonokbht.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gtsjzxlnch.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolmzwhma.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gthwzzrwmw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtzunrmrzh.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtihiijvcp.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtvcfixwyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gttsqnbbhi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtkhtpqadg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtccaoxolm.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtnczazwkn.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtnbmzllhb.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtlqqwhymh.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzqcavrn.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtbgajupym.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxipurcyb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtpxihxtgf.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtnztlitbk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtamqdagyq.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtrtsdcxel.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtxeyjlacs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtjnazxbga.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtasvyaykj.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtnncypflu.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtnsdzdkqo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtowdmuvgq.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtagyoarvn.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtavpbupsw.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtusfugfvg.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gttwcepgpy.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtojsolpoq.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gttswlhubo.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtsavpvbop.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjrzepqqs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtoencwtwh.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gthhjvppkp.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gthuqlwbrq.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtjebymytn.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtogmdrbho.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtcmjrqhtx.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtgxgaybue.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtuqiqvcru.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtrlckdios.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtzzbtnxwd.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtiojhrmgn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtamtimnjs.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtqxesyojs.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtcyvsgwdv.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtmavgowhx.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtnujyhmib.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtgyznaqfa.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtvoqxuaal.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gteilhnpdp.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gttlatqxzc.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtfnpcuska.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtwekoblsh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtlkjqiahr.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtsxprpnqn.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtctmmiumm.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtaltcarjd.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtpgiztfpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtipownbxw.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtsoddsfpv.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtqnnbzjan.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtnbwieefv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtqqrycpkd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtbklwgadm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtetfrlxak.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtybhacgpu.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtcqfnwfdr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtlltxsarq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtzvslkshr.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtcaaucsdt.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtryllwgxu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtgmxhzhml.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmglaggn.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtiasnixqs.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtsswydlic.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtjxdrruca.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtaxzgevys.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtnysmwfvr.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtksojcotm.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtzmbaiejv.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtttqkbhxo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtfcfbhgrs.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtrdeopzgl.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtcpihtnih.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtbxbdkhco.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpzlxiho.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gtsvgqtnqc.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtiaarunli.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtulgvdozm.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtanjaiqla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtumrukhhl.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gttybmmlpn.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtclzingks.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtbratshzi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtspqnpnfh.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtadffdmxq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtxuyrspca.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gtnhvunhbz.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gteiugcmlq.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtlrdhoiev.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtkwbxhpqy.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtptzpxtrs.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirhowvos.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtjildehvi.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtfuqdsybl.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwlouvtr.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtufshtdfv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccrhjafy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtjhqryeje.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gterwjgvkl.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtoclizkkq.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtnxxcjxgs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtjteimfau.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtxmrluvkb.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtrlkcrprq.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gteoibfrex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtstlnfr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtebxyvdpt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtzvllicwj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtavqdayjz.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtohlqgwbn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gttbvxwwfk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtdzticqzp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtxtrjahka.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtmvtjteem.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtfcikmocl.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtzhwpliug.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtbqvlycue.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtykvwkizq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdugjiiri.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyiiddwl.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtnpbqnftu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtkzdzdiqf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttfdmsyat.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtvrldonei.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttlbaxxjh.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtqrhychdm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtmkuzzbvr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtcqnfcjaz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtworcbyyv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtcpwyejcc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtlrduvjtu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtuktdpyht.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gtaroehdnf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtzoaigfde.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gthlulecqk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtofgvesjd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtdkqtjrjg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gthhodhgdb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrojzhaf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtgwzzvgqk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtdccprwbt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtugexuiql.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtrffrtsuv.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtbhszhben.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gttedfrkzh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtgrwfbwvo.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtzgsspbja.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gttqjioehi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtzrbmojts.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtukcqldgi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtawoitdxu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtajmdssiv.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtuxygmexv.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtarsrnctn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtrpujykgu.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtdgxwjdjp.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtyjxzkcde.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtlmhmkuzs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtmmfegkfy.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gticjxdxic.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gthvbvxvoh.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtwzwasrtm.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtwfxuqjuk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtqbpctola.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtwedtdjkg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtmwshpkuh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtparvzvvb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtjkgeqvjb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtydjwgdjk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtkuczgjrj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gthldzmyqx.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtqkpkixng.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtfptrfjqb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwhizriv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjcgglfu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtxzgrfbbz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtecpnmskz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtuhedrazw.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtejszqgji.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtktopegei.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtbfsuevif.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtdiumzczw.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtafxuszhv.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtwcrontpy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtenmcodrw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtxxsnvksg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtmlwokykq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtvtsfwxzz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtybdopnit.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtmhinigma.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtlspxbkvb.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtnejlvfpj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtnkpurwno.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtnzranevx.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtszekgytt.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtngoswihs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gteywaoibt.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtbtqwyquy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhkrkxvu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtzaefjstp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtdjykwnuw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gthtmqhela.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtpdwxbbeb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gttltpbnyy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtlymrpisw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtbfxokkud.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtwadzvopu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtsukzmodx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtrhdrvsgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtjccmtrsp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtdykeddbf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtgrfjahjl.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtjvmkklpy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtoafgimsb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtfavdegan.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtprdysmbi.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtlgoeqnpc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmzsdwftb.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtszxqjmpv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtyjhffjur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtiicjufpw.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtloggvtln.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtharswite.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtcwopiurw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtddfnszuo.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtwdeoghvp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtktdnzyjb.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtvcwoqqxj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtjwklexvz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtaxliixse.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtztcodmhy.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtjwobwamk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtdmijmukc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtdohxpjgw.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtolhifqcv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtsiijsfoz.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtotnznpgf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtgfhdbict.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtqwpfvlxo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtymeyrbtn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gthvcazoyf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtnjrvmjej.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtjzakxejp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtneheouvh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtsfaqhxlo.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtscgyywsl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtroykmxaz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtfhszckob.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtvxfadvxk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gttyoadcxs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gthayjcugs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtukraeosv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtcqeevgtc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqvpzffz.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtrdupcjbb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gtjcojgelw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtxflgjosv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtnjofoerf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtyokmszfz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gtlltxkknp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtzwfolxxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtgdmzesrk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtqwebdeqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtywgtlicp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gttdkxvoxd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gttwzcmrqp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtxstnwahc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtgyioweij.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtckbuaczi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtlkxmdfny.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtjrioxhvv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtdtziqryh.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtwfjiumli.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtlmqvvrkq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtrocqivms.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gttousxmrs.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtkotgdnzn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtbyucifhe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gttasuilob.html


<!-- 参考信息 -->