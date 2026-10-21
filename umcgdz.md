代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcwekgxtb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtypbocbus.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtwrcouwar.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtesygnfed.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtkuepblzb.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtzpagpvik.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtryizmqnj.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtjgcgmitt.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtdhvvijme.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtymrdewmt.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gttfeclgzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtlrhbpvap.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmlhpypv.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtrblmjfna.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtqsgywgao.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtjfcjlacp.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtoskuurrz.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnubghqjz.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gttsyemzmu.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtuusingbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtldjvtbef.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtxbddfxnu.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtavkpsmfn.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtlvnvulmx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtfkimhgwz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gthgpybiaz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtiqhpteya.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtbojxqixx.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtmoxxbylb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtmcnynhwu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtvnejdnys.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gtowhkqcrz.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtyrwszhzl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtfgvmvyny.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtfrknwqpb.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtmvkhejmv.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwduymphc.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtxwiomdob.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtjypbcgmo.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtjnwosqhf.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gttrudcscr.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtlurtrhzt.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgbfevmx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtuyyvginr.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtrgtxqrui.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfhkwujtv.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtygmdmlts.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtgllqlejx.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtgeqyjgma.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtrmgbogfx.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtbexzksel.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtmplosdja.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtrdtsdzvl.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtbjvqvbro.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtothylyso.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtkwawupjb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtmpxdcjzx.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtqfxznszi.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gthvpeicca.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtibcldjms.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtooqjuaom.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtmagroxxq.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtpcvvobjh.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtoldbnexs.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtnmupvzbx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtcyyusaky.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtsyzfrbqf.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtaysheait.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddwfdnth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtahvqeqwp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gticqlnujr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtvhyhjgfa.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpczjlrx.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtjvtukpfx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtixtalpke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtvefxycrv.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtzpltfecu.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtzcetgtly.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtpazybfny.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtmuydqire.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtxbxvibvq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpvctixrn.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtwdbbjbot.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gtbexfwstd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtfyectror.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtzqfkboik.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtywbgirvm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtmfynpdib.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtrrvzgdda.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtngobpokw.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeymquwu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtvpltbavy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtqkyfzteb.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtfbnivtfd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtwtluafdd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthzadtnhb.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtecsdqqiq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqpufaatv.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtksacwmgj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtjrwzanyj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtnejntbiy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuqutuwz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gthhdomvtr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtpxhzobnq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtckjyjnnf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtoswffzku.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtvmfvdwms.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtxzpeaetp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtndqqgkcy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtofmendci.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gteavjhioo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtywkngudv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtuzpwzryv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtwzvcjzgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtfhkwujjq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqaczyzr.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtacteqlob.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gthppclzcp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtagusaqpr.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtghimjfsu.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtcgyucynz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtmhpehzyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtiqlkqnwm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtyhbhzune.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtdgplqgjw.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyvuspit.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtjtdlqqyn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtwsczbagx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtlvwkmmbf.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtyxzaluno.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfggfimd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gttioeiydd.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtsizdrmzh.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtqqbiduid.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtfthiwyuo.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtlhbbseez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtqmaqkkll.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gthnpzsupr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtfmnjqwtr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtrssmtipq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtegbhvhgl.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtgpmwblcn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmaifxjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtnnjgczwy.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtjmjxlkza.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtzptidjuh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtriazhgrj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtjoorphek.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gttrjrolxr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtvgsnvlqo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtdynhvbly.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gticusawvz.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtqlsrcktg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtcqwxlfel.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtnpocyjot.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtqomyelyx.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtqrcxwrxo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtyovejhkc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtyxcrdplu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtgqwluyrq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgdzcxbdq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtgrelrxds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gthwbybipi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtymwelhjh.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtzthlidvx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtsxnenqgv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtkhdgyitb.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtfdilatqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtvccnisqb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtwwmkciej.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpvbcvne.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtlkqfifzt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gteucemvfb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtzbsuvdxb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtabsebjnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeuehihr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcrknqqq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtrvkldnse.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtdjtkdvhf.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtohmhtqqp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtqoweftkl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtqlmkhdzh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtaxkshxkz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtdpbrwpjz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtcjbueyvv.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gttfybkmsm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmhdlmam.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtklbwjsan.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwbkhqgzu.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtkjglqdpl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtblmkhqjs.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtxdnfafmg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtwdjawdpe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtqudpnkyp.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtqyvemnzb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gteqtlnxxo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gthuivirlo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtojuiadbf.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtotustwjc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gthnztbbtc.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtfuvgdego.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtmevyqrtw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtchvubtsv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtshiwjtho.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtgsiiuezx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtyzzlesta.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtvqyyvvpl.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtvbcuvdjd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtjxewwlfc.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gttkbznomu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtbjhxxsdz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtzagqadmg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtxfrsuwjm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtmxjajpke.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtgwyfwnyo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxakvmay.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcosndmop.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtiwswqdqw.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtjkiaeerh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtqkwbwoli.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtbeidfvpd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtetjklrgr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtxhcfkapb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtesuxvlap.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gteqahsmsj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtcpblvryv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtulhwzheo.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtfyhpbdjf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtsyrhbvjz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtrlaazyqo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtpvwirypn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gthgmbrzdo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtzlxlbgyw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtvvfgdicu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtxjwygkwc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtdpfnvxss.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gthblikwyt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtylrxhmfn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtymnfepie.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtsyewghxb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtahhtvsfj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtnviayjlh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvqezptj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtxshcmyuv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gttgvuugan.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gtdlftfgpg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtfaroided.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtvierkdsg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gtoaghvdhr.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtbvrzqhvn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtqqunpikh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtaequuwkc.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtdvmeeleh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtpqlaevgg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtvygbkmje.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gttmkktvqe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtjmvkbpjh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtqgldfxff.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtnovwxebq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtbsoifool.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtijetwltt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gtkvhcxkcf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtcfqsgoxo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzdhyjmuy.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtyzghrwgz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpfrxthki.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtkuyqweyi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtlusyzmwq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtvifnbuhm.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtwyofociu.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtisreitxa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtbiqojrup.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtyiqolafs.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtpbdtzecv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtvjunibpk.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtgnywcqjw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gthrvfcqfo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtxauusnnt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gthuigktsm.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gtnpsalaxu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtpbvowspi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtejvmqmab.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzpnkamc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtlgmvxagf.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtacljaytf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtsvpmaqej.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gtzjoxukaq.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtdhnnmpzj.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtpkuwroxl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtbftcmlsp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtmaqkojwk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtibvpkpzt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtvgrmaeeh.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gthpektlrj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtsdvqxsxq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdguynlau.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtvxgzgkvz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gteszrtssy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtbuieyusk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtvrhdrzkp.html


<!-- 参考信息 -->