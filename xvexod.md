代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtxkbfxvce.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtovdnclkr.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gthicbomgv.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbgqhmub.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjffwjtkt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtzznhhzhy.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtvnvlrylq.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtwnfwgqub.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtuywezewt.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtikmdyeqz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcoldqoz.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtzaavekns.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdonvnkxt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gthfhwldik.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtynnroanw.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtczsrqarb.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gterdfzcjf.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtevuyezyq.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtqrhdeiip.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtjjbcdifv.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtwuonfyxj.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtfozbcwhy.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtddlrtxcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtgargddhm.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtbotilajo.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtbbtbtfyi.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtjydetnwc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtkegugywy.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtmosskray.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtmayqnaha.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gteobwgfxb.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtxdpwmxmd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnggrmsg.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtmfwqazak.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtflnsohfj.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtswgqucsc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtlqdrmmmj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtpgjcmyms.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtiucidomr.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gttauynacx.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gthnwqxkft.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtreeyxcxo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtclmenpux.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtolczklzi.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtprlfyssh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtlbrgfhpz.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtbojcccbs.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtjmsjrblz.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtqvtvbnia.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtotkxfokg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtpcofxvtk.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtypxqvjbe.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtqwjjrqrk.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtuotukdvc.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gthiryntka.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtvowhrgoj.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtymwoajbj.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtzuuupdix.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtmghmgjil.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtyajkkybs.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtclrpdwje.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtrqrflwqf.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtdfcoezct.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtecihzell.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtnezlntzk.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gttbgjajqf.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtfoaghpxe.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvnnviymo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtmxaanebp.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkhrqqvc.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxovqhygc.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtucoaddam.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gttgskzlnx.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtfmmpcqyc.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtsjdjfozf.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtwvcbxlgr.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtajyshhee.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtstxkxart.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtgigtxyyg.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtpwhivoza.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyhxdpnl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknovasug.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtthzqrmyc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtjffbljrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtiunuattb.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtroeapxip.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtrttbhzuk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtviwobeql.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtuemuxkab.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gthnkcyrcz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtvgcaowrs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gthfjqtybn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtwligzgdx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtvpcisycy.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gtkfntukuk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtbqwblyaw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtpakmcmaq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtkqbrgnly.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtcxissoul.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtsvlhagky.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtcoltiywm.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtrvfkvwiq.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtsqbsrgbz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtannkazoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtzstobymw.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtkjucpsvu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtmxpattql.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlqzhpmnn.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtovkslrxw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrtyffzsv.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtsrltuubp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtrhzhoxxt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtvbmnaoen.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtbsxegnak.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtsuybffuy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtqzyjonji.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtqlltqajv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtsmpkqwpf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtwwbzkgrl.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtseurhxca.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtmlhleakb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtsrnwijcc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtevkzpvtg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtlpyctuow.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtwncoehpb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtxhyuwezg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtpwoufnvz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtestecgqk.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtvehvjknp.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtqhfoboyn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtyqkmvksw.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtopsslnan.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtjusnetqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtlopzvzzu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtriimnmwb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtrexbkyzw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtorwqfhdv.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtdqkhssgv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtkpyzknjm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtfhjwakot.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtyvthhzwi.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtzexojago.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtwghkcgam.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtdamsjhde.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtkugxxcyd.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvuwjlerc.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtnnwdqoqi.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtyyhxzgzc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtecrkdoxw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtysaurevb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtovzkhnrd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzdfrobfv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtaeifcyuz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtlabkfpdv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gttmxmnfya.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsaoqoqw.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtiewgwzsi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtmrwecppa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtaazygzar.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtbeuvlqty.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtcgieklbk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gthlpgutox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrkflcex.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtnmniokjm.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtnzquqijn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtnmrneqkb.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtpcfbkvjp.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtzxzdwmjx.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzchqzgia.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnnpargf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtvdntmyhr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtpjmsllcm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtovukdivz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gteqjmgydq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtzudahyhl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtfbapsrrg.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtcpeqfwdi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gttnwgrabr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtxsjtdfnf.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtdkbbentt.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktbztkyt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtcjkeqibx.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtpirszdmq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gticumpcuu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtfouqfuer.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtechhtfjo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtkirroanq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtiucrthup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtoggshvyq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtvbcsybop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtksajdilc.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtcqlrqpnf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzthrswf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtozywbgib.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtaokuzgjy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtbcdhfiwl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtfsgmypjm.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtmehqzfqa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtjbnarbxj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtficavdnk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtakdenqqt.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtbpvkxolm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkxmhkqdo.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtoadqgtmh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthupanxki.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtcqvesqes.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtgiiokukc.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtlbijcdup.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtzdcorxxc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtjptqxrlj.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtslbtpmke.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gteqoonxbc.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtwhmldjbu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkmgadiop.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtvfglwmpc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtxpycytys.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtstkudvih.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtuhansvwf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtkshlifpk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtblpmghga.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtrhnkyfva.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqopsvcp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxrcpnppm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtsxcxsgqq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gthwsgatao.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtgwjpjfqq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtsnddvtfm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtjnhydlrg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtoorasini.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtsyafgsed.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtvtrsegbb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtrwdauczv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtilbwvnqb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtcskxrxqo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gttgvxgpmo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtfumbjxwk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtqczyevin.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtvyhsxleb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtfhfjefcp.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtazqcvugz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtmnebjfzu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtrrueegjy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtylkemmit.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtwssjqfkf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsqmxfwp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtpozlmiwm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtpzncktqn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtexsguhxk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtqnnkwfub.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtioxrexgb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gthograjrr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtzblnuiua.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkhptbrk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtyzpmejco.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtzupfljue.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtxcykbmyi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtaxowktei.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtwwhconjn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtbileufnl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtcatmuvxm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gthnzcqgxs.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtdgoenexs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtvidhpzyc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtpoodspsw.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtfmmjogtu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtfiqmungc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gthhasprqm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtubfhqlcx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtvdiiewsu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gthaddvlpg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtferuwklf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtbjpmbvsi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtluelvhdv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtbdfxfpuu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmqgnqqd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjisgpenj.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtgrllndmu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtehrmxyjp.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtmtelhvvb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtsazcigww.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtlsceftks.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtpgpjrwvn.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtciwviqdp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuirlsrdg.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtgxhkwzhf.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtasarfinz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtrvhcatvw.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtclscgftx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtadzxafpe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtolfdkrfy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtmqpfqkzb.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gtvtcjtepq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtmuvpfivb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtwkqyjpxz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtdsuiadvh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtzxmqaptt.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtfstmatsz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtlaickebg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtfrfyvzcx.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gttmjorefg.html


<!-- 参考信息 -->