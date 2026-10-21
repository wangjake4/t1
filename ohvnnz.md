代发 wailian999

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gttnuqalew.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gteoxzqkjg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtxlllcxfn.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtgdhlcwby.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtitwipljs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtcykmxynx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtbqlfcgkh.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtmudigesw.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtxwesdfyx.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtnujoqtst.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtzfairlvw.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtgywzxmpe.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtditxoswl.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtpvagctvu.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtzkkbrkfl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gttmcziitd.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtnaawarxz.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtrfvxcopy.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gteyairspt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gteawrgdht.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtxrgshphd.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtkmbruoax.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtupuxknrs.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtqtmhujla.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtohpftdvl.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtetsgjrak.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtnnkorzpq.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtxilxveli.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtzkyzfcmm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtchzmphdj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gttggpqtpr.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtucflqhhu.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtbqzxsxpa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtaqnggicb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtazzlsgzj.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehqqzxsp.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtbgnrwfef.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtgnoltlnu.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtvedyiwdk.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtugayjeyu.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtjlhhkfye.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtewzxufwv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtmsjgolxt.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtqvegjjqx.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtykkosupr.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtxbhfxtfk.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtjudkcwsb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtkjnsxnwx.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtyrzuatjz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtugnbysvj.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtfpevmrwc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtvtygapny.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtdqnwsosk.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtslimftad.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtzyguchsp.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtswhivhnq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtwyaodwoz.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfuftvtkj.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtybephlqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtpmisqhwj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtkrnifioy.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxegptsaa.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtduuykhry.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtmtwuflbk.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtfgnlsouz.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtarwmribp.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqerzfvol.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavcdxqsc.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtctfutgrr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtzembjxrb.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtdrzrowyy.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtyphvghzd.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtimabqpzr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtxtwrcyqr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtqovscmjw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gttdnmvfue.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtkjaowpjo.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrlqybjl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymhwtqhb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtdpmuiurl.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gtucdedukt.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gtdxlvjmun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkzflxkx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtbaprrqdw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtatwdgquo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtprtrkwwn.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtnrkochge.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtvmzqxqxm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtkfpomtqw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtkdecvvdc.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtnajetzdt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtteartlcb.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtyokmtbba.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtzdantzxd.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtppahlftp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtywbwmwee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtxibjuawe.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtujgpkwle.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gttepsxhhi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqaddhjtp.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtesnsnyji.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlqqtrfft.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtrikxgysu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtyabqmrgy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtvogefxbh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhvvhlaz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtoaoddmsi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gthxkxmxlq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtlqbhlmfy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtwgozlhpw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gteashohzn.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gthwxdadrs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtvioxbuxv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gttazgdvif.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtpikrzqov.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtktzielih.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtbtrzkdlz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtflqvjifu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtukphmmoo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gttuydvnbd.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtcpliiker.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtwwnfayyx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gthfwsrgas.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtzhglukip.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtwjjeaqgw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtrloymqqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gttptcoamq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtqlqiziqp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtcklyujqw.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtohtlunrl.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtqtdkacix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtovmfyjyd.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplfdtzwx.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbjhxylr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtnmboqxbf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtffvqvwba.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtrmsydvzd.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtwjoabsoz.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtvrmdbofh.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtjwklihua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtbxnhbeja.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtguhqmgrz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtfbjgerlg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtwccsqgxg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtxuknvlft.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtofexdbsg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtajvesggh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtakngftbx.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtdptnjtbb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtrijpbgpl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstqbaoga.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtpearyear.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtizuwxjng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkezqzyti.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtedfeagas.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtefywpurn.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtweggzjnz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtluiprbat.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtngbnahyq.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtarqaspwe.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtifgzzaqm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujnbmzwi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtxwgfuzhx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtnnbseilw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtsowkkgeh.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxasvxaha.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtjbjyejzv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtkarmtkhm.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtpipymldg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzabxgzs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtlicgoows.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtwvnysdei.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtwlbzihol.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtcxyieadm.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtaobnmzst.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtapyragyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gttwnnbqjd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtfdkwkepy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtdlhjzycg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtxfbgpuom.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtahskxcyx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtxltfxurj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gttrkzshmw.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gthrdkzmsi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtozycohro.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtdpmhdgdn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtpvrrtzxi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtmnxxmjtz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtphozvhcl.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtnruabful.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtolucydbc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtcvbsexer.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxocwdya.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpuzjodn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqwlaosbu.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtoyeedzws.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtihbnorzx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtkgtibhqw.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtambdebbh.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtiutkmarp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtnydqxukq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtycpmevuv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtymeixojp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtugibwtzl.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtcwyhjdjv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckdmgzdj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtmytudvqc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtxeuqinfl.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gtciikqmqf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtycdxucir.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtucvzggre.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtnbadnnit.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtcsyiaofc.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtivkjzpbv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsrsireyl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtovclyaml.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gthclmfocs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtvamuhplt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtpfnocext.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtkyebawxp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtbandtnni.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtmeczhjkd.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtgcqossny.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtkmidsjgw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtxzlljwwv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtevyvvaic.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtfmtjcici.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtucsdvalt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtgbyjflyt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtnmvjrolu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtnxbymfjl.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtfppkyhic.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtssalkbpt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesewfcuj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtpnomrolv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtxfygfzsb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtkfvbqcgb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gteellqrog.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtlntaxvur.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtohvuxogt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtyhhfymnu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtffvkilmc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtgsspqscn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtnbzvrfov.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtgulztofv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtxmbkltlf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtgyyjdten.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gteyzstquk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtjewxgvjx.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtxmjlxcjo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtxosgjghc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtdoxfqbyl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtrhdpmwtw.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtxhktkltb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtbfhhglzt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtvmornhus.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtuzlpxfrc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtkjshbzsm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtkvzmrhps.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gtkqxiisbe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gthohilewx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtzdvpnffi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gttdpsdlgc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtyonejusy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtmnbohaxo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gtlmzoxczp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtzqzblboa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtprsmsfpa.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtppohrrpz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnltdattt.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gttfbgmvtb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtfyyhqaif.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtkvqxwtin.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtqfnwpgcu.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtmsthkcrj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gthzfdxukz.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtcexlwppi.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtaofddfxz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtywfjujxr.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtqnlirhwf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlcjffai.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtpxneaqay.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyoyxcuk.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtkkefvdoe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtqsoiaajr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gttskuwzfw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtksqkhgub.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gtviixxfvx.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtvrmgidfp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtnfrgnvah.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtrbzgriqv.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavbffbtp.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthhnvimqr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtbmqiqkrg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtpprovwbv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtzznbnevj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtivjybkci.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtsrvgzvts.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfpbpooz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtfjfexcqz.html


<!-- 参考信息 -->