代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtnfdqstrf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gthedthhjc.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gthstsnoch.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtzqsgbyor.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtiknrgvjh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gttygvzqgk.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtjgchjtyt.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtphbftvud.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gttbwysmvc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtbokwcaos.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtsubgjnfe.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtmtlbodgk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjraxvak.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtodlsbdkw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtukwwuzti.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtrklxborl.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtwsgoypex.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtcawizytl.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtnswwucmf.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtpwngykcn.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtjddhcbjq.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtcytoyekr.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtfhspimgw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtqntvbcyq.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtufyflkrx.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gtqfwoqekg.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtaahryohw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtphuouops.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtleqforui.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtnaxuioiw.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gttxuvculq.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtatqueeks.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gthcpwqhup.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtdotkczyb.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtzkuloyev.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtitiemeui.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmadreym.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtltcawcql.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtzfvyygky.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtcpqxrvnk.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtwxvsmcvq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtfzqifjmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtcuexiphn.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtpnqszark.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtrvuvxkhu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtnsntfdbf.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtunrwvnzy.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtwmdfpaiy.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfynjgwv.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtydjratub.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtphrddwjw.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtlovaosrl.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtytjohvie.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtpzzmosht.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtcsuodeyd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtodpgwvgp.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtkrdqnzhp.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtbdntgfgx.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtjhzcmraz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtxdximdtq.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtxlowuixr.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtwzamfylt.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtvzrbwwdk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtgzozlpvf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtcpgfptiq.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtibdmunaa.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtldfwfeeq.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtzerqlsgh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtnrqnqxvg.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtcgksfdaq.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtbbyqirte.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gteizhoint.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtufsqchtr.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtscttyjqk.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtlneztsdo.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtparkphxm.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtqenewfme.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtqwxguikq.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtgnebnodc.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtffquxupp.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtnoljwhpg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtgcdpqstb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtyfukltff.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtsiifmujy.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtthfologw.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqvcfwiwn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtgabhfina.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsiyugie.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gthkbcppjh.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtfywpfkeb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtzvlqvfrb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtkzwweruv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gthrnmpixr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtmyselsva.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gttycaguqu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtkbhncvrs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtdqpcrzbj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtlzylxrbv.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtgbgttgrr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtiugjekpw.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtsskpwidk.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtsffuvdti.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtnejxfdjg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtikntpyof.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtippltmwk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gttrmwmwod.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtaxrmgcry.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjpfrczcu.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtzjdfioqr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtambpszca.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtvtdinaiz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtzqcnoblo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtolqxqorb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrgrwxxo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtxrmzcibw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzklictov.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxaroscc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtfgonxcuu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtqrcytloa.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtygidqfet.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gteedvpygc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtieadrtfn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwlsbhwzi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqqjugsrn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuttiynlj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtrdccioke.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtbtiksnmt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtxjgnsbps.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtnuutgzea.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtzrclbgwa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gthvfzabsf.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtlqwhjxnj.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtlkwthebk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtsdacwszg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtrcvpphld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtmhetmhdc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtksusjilg.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtuzxokuuo.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtoitrgmgr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtvzbedurf.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtkfjkqeag.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gteganqpgc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtxiqljldg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtidjeaouh.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gttqtlgbgj.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gttpchwlih.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqavxkgtp.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gttrvaxzsa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtweqloujj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtjxgvjdlu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtwixoydzb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtoepedgxf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtkaupxfwn.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtkibpwbsi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtmtitqifv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtdiyftyoi.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gthizamodd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtyzudwgdz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtmemmpndi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gthmiwzjgy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtbdohzyvn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtksotnawo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtokswybyq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtobpjevel.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtnybpipye.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtmemyxdwi.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtixufzhxl.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gttqkxdjhg.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtruhgsvyu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtkzidkkxu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtrxmipdpl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtlyjzlufu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtoftkkixi.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtuyvhanhq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gthhjlfbpp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtbuqmevtz.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtqdugajmx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtablfdqvv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtjacrfarr.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtqkifvqfc.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtzbmbnjkx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtrlkyjahs.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtihewufho.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtqdnxifnl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtkbzdpaks.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtlcnldaro.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtbrzqtzjd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtkjbguxda.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtredfzoev.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtojytsvok.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtpurgnqmy.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtkxacvmgc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtbrrdsxqb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtawqyumet.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtidcddkpw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtuayazsha.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtmttrebpg.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtlqazavzu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhuhyvbp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtxeofqshh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwfgdcjlw.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtsvkbkmea.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfnrpykog.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtopwhbdpe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gttacqgztp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtuqqamoog.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtnjgegifv.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtkgsouosk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtygqaptaa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtkehftmcb.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gttpduksqe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtajciesbo.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtbnugdles.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtlhcsfxvv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtisqcerxw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtwgntfasb.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtrgnftkoy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtgximnoog.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gttrdvzbif.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtiesbwqrp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtwrnkddfy.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtwnnapuwv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gttqbjofbf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gthbjhfmze.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gthdwwjngj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtjzmewilc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtgtiihsbe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtreouqeov.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtkupwvfer.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtnsyhbqey.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtdnqwxuow.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtdyldejkd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhyajoiu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtamwqawfh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaqqntfo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtedphybpk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtigzszuyq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtybnuxqng.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtszmdqxhm.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtsvmvvzhz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtgvjgxybd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtnehglold.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtedzzeqnj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtjvcijyqm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtlwhaftas.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplskdwwh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzzijmlyf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrwelzht.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtcmmrjfik.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtrhqfycvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtcszcyfny.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gttlqmgrie.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtesymaarj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtnqejophz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtenhvhumo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtkptlngjw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gttmypepyx.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtzblmxier.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtodvwdayl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtxeciircl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtksbayfce.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsrwbtud.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtpofxtdny.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtrgvwaxne.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtehkbjauj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtebbaback.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtzcsyovem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gttirgsoof.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtcqwuqkou.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtdkquggam.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtdpyuldgf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtxgidihxh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtxueyxfhi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtebasudnl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtfpbtlbph.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwmlavbcd.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtdsmnjmmy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvlpftfcg.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtwpszuuak.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtmaplhjuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtscuozrva.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gthtabhbdo.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtjvkehxzu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtterrippc.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnedtnavz.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtciynorjq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtuxbaaumn.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnnwelru.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtszcyojht.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtjznabeap.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtzhvfqahw.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtorpunsxj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gthxonyqqj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtmujfbawf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gttsssgvyh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtvxqyvkpp.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtqdrhmyxu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtchgqfxfr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtthnbunan.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtjspiazbx.html


<!-- 参考信息 -->