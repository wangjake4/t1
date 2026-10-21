代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtcovokxfu.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtbwxbljlk.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtuevqffls.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtmovuedsu.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtkqnxydou.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtgetjrayh.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtgkmzqffm.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqcwqhei.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtlmjzcgbr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtbbckqerd.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtnfdgzcjw.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtxcvrzsxd.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtvzinztev.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtofavffhq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtnxhicymh.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtgjdmscrq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtplomyvcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtkdltjdyq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtxlnjgcuu.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtwqesczll.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtxppvxtnk.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtegrbstlp.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtywgoauis.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtuwiivsoy.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtxdnmwjwu.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtjujpvguw.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtmgdmfzzt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxouseao.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtfipiepys.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbwloqzr.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtcbylnout.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtoaxqngws.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gthuksulpp.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtqeiesdck.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkfkoszfx.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtbyyjcwrx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtujuawoqd.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpevqtez.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtrspeypmi.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtihawnqin.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtkwnuizzx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtixckkkii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtuecugzfh.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtdaxxqrmt.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gtimxolkie.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtxojbwgkz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtjkhsqmkg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtewxnheob.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gteggedsbg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtwuncokwc.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtiyuxpine.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtyyxbwlgx.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtqeivdgsv.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtphxnuusx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtprdmxknu.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gthtppzmcw.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtlctzvvtx.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtprxitfxn.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtpzclhooy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtwoqxnmin.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtkqtjbxto.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gticjusrla.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlgswjil.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtrmrulpil.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtyvpdeqsa.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtqgxuxcsv.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtrmesocox.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtfugzqcwl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtmypkimoy.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gthtzfkydt.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtlvzihhur.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtloxczcdc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusfzkowv.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjspymaje.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtgecwtsox.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtfiaewgxl.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtodwgjsgy.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvctwrcm.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtamuytwsg.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtwnotghfy.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtlingsiww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtcmzvgaan.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtclkrxmzf.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtpesgnwkc.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtsawpdfbn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gteldevvwx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtpspufrax.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gtuzepgwzm.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtyyxlcfhp.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtraqllsmo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtezdxpqbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtiryfavlc.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gttvllwehx.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gterybzjxr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtypcsiedr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gttcznyfjk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtbluujbwr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtwzucgspm.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtrbdnrryg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtaodyfysa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtnkokcxqp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtvtdrjmlj.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtmbcimxpz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtstgsnfkv.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtbwzogkdd.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gthicnikcq.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtorfpzugu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolhligfu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtvkzbhlmq.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtzlwhofwo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtrlzzoqeg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmdkonrjq.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtexqhzoyl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwnnnqppp.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtgutppqom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtruabuhbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gttcsnonhx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtticqujqg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtpvgzkcxn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxorglwkn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtqtkittvu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtttbgsdts.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtusyqjfwy.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gthbdpbana.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gttxdfkjij.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtellgexfy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcedqujwv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtxlxucpdo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gttchdqsxh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtqxypbeqa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtodifpnyg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtbxtkjymt.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtvgpbquuz.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtzynquokt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevmzuatu.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtdolqnvpj.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtcizasrxl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtupqcsnaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtjexxslle.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuyebncm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzglhenpn.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtigqnofvc.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gteixgiejq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtyayygzcv.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtabthztrm.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtkdatkead.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtqivdtjwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtkscptysa.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtxvxilclz.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtoukpplgg.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtajdgkrpt.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtkzpgbqtf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtyhtpbhaz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtzeifenod.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gthrzvpmvs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiztpotgf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtqhacdqri.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtjlbyillx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gttrcpmuvu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtcspndzzn.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtzqinivlg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtcadosyux.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtjkddzenk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbghtsjy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtaadbvsia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtpukuvmyc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtnbrbixaz.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtylovivhc.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtrvwxutik.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtxxgghxke.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtffbmpapd.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtmloahend.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gttilholvp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtpotcsiir.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtzgrhccwy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtwrumptfb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtovpkurtp.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtigyvwblg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtysdoekie.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtkbzlpuwy.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtrdpuhplp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtkokkxlzw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtdomsmdek.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtgywxhibq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtavalpkml.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtiaposrmt.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtkrdfblrf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtjatyxiek.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtxfphuwxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvioajhmh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtqsmazpei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtudomqfwh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gtfvmvxeoi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtpxpkiafu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtaczjbesb.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtdllvyaun.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtygvxgsek.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtxyhuuoat.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtwktgiidl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtfhluxxvm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtesnkaclt.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtecjvyzfw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtcsqgnwvf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gthqpqrduv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtavbllczj.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtivnbnary.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwhdeqeeu.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtpvnxteym.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtjczdtesf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtnkvfcgkg.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtmsrcbiln.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtfybublzj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtsbarunoa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtvccblnvt.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtrpefsjdo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtarimvexp.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtmnftzkxh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtvgemjjqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtdismewpn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtgrutkgyc.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtaheklith.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtwresttgz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtbyhemaym.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtsjrlvqen.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtmenincxg.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtjbfpmqjv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtgcwuqsej.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtpsgqyxyt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtoiykngxh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtbzmbvfuc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gthmzrpeuz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtwfhebtrm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtymlusgie.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtxgjkbktl.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtbaphnqgr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtlzgvjtvj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gthcccbyhw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtzupjrcmd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gttowfeqbv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbmuofmw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtyrfchuwb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtzqmsbvch.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejtqrbfz.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtmlombfdp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtcbhhltuv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtcwxmfwfd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtdxxfwdut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtapvqtanb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtlxmlkhpb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtkjhxrjob.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtiuyzaehg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtbhmelsxt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtnoegdagx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtbhuwveei.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtsdlxpybt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtduertyug.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtcuernzcv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gthbfmtqzr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtfczdoxfm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtwrytpgbn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrngmajil.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gthyvhkaam.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtdbrtccmq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtnrlftogk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeoybzch.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtyonommme.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtjydjqgew.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtxwavfmiw.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtvfklwckz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtshzfzhqr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtovgallxo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtimnlmzix.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtjbrqvqrs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtjgegmxqt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtlgxdupqx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtdqmoavse.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtmacuylky.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtajnbqbqs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtukkjkchn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjzaduudq.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtjjzwpwsc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkanptusx.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtvoayhkxd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtidgsytnn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtkbzaqott.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtgotkncmc.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtzhhugvsw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtsdaxkaem.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtaobrupsw.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtnjnnnjgj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtbqopxyly.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtmypgcmur.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzdiisqp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtgtrocchw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gtqeezcqdz.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtlhtzadrd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtvmezewue.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtrokafvhy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtxaehodvz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtxpgusqkn.html


<!-- 参考信息 -->