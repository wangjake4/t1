代发 wailian999

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gtnnedwvio.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtqqlgikyq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdvtrsjh.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtgkbfkopn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtudkqarya.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthbvtwfph.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtbvefzmrc.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtdshevmkd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtfvkfdszm.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtrqzkkmya.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtjabzrunk.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtgtetygju.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtrkgzfqgj.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtjceduxvm.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtxrswamrk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gthlqihyje.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gthdqgprlf.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtfyxtifkj.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtyiyczjky.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gtrihpnqne.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvslchhxh.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gteewaxiae.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtbpaaxwah.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxblnerxb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtccuqiids.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gttyrpayeg.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gtqcgbmvpy.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtwbhlxhoi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtinpttrjz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtwqezutfi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtcxzavgxh.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtoewtqjtc.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqfwrgond.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtkazgkgvq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtixwntdnv.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtysrvwyke.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtktwqhvzc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtkofbzjws.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtupljkdxc.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtfefrhrey.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtksmlaxrf.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtvwthwspe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtqjiqaung.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtysyxubhr.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtexyoknuh.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtyjsgeavu.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtziiehngj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtylwcjmrl.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxweertqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtbpviezzv.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtxnghrjli.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtagvedgnm.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtsjcdhjsx.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtvpbeincn.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjuzcidv.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtctbkpwtl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtiluswjab.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtiepytatz.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdxcvzubl.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtthlbkjnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtdcuwyaty.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtklpwomli.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtxdvxnotu.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtljbmtvxu.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtmcxaieow.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtpqovokex.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtqtykkppp.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtrwtypewp.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtaekgusqs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtifptcepq.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtqsfzrifr.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtmgdrjzpn.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtpgbttpfw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtctguvrft.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtphrmeero.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtztsexbnb.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtugfhbkbc.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtmjahtaxu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtxtrbfnwl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtamauyjyd.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtfjqtybkv.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtqdqairnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtlfogrycs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtpunpwktz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtqujahevg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtqverhqux.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtmbehtwek.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtbclbgyun.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtfajozhoy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtahravuqy.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtwkerluae.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtctoplajf.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtxyyswzzm.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtidsqwtoe.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtszymtota.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtctcgnmcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtqbffbube.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gthiyacjqa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtrgdxbbwo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtseuwdzgu.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtnfolqrbc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtywscxgxk.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtyoacrqqn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtqcoqxabe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtwfnduvqh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtzzgtgkru.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtupobbvgf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtvafzlxct.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtwaqbgwrc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtqaejqqql.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gtilaigmyl.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtxjbnkpmi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtjluaxjte.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtczwhvlph.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtdxokysnt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtilawuqkf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtykifxbyu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtyaleajna.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtauvotkax.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtmajwohjg.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtpprwjivf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtqmefuddw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtqkepkbkb.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtqvychhos.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtjkfzdemf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtncivyohl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtfcvqbaby.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdabyvjym.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtuqtiivru.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtawjbnylx.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtfhqsaami.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtcfhhsabh.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtlscefbsu.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjggcoqtc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtizmcodqb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtuofokiqe.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmyrljjz.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtlioxrydx.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtxtwobxbi.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gthizfjggq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtnxmyfzuu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtjqlcgtbq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtmhsvycqm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtxwdkkija.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtpiapetsy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtmjgpzjls.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtswzacftp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtpjdbtlfj.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtaplroqzo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gttjqdwcqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gttwnhslme.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtvgcxktqn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtzlbylcco.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gtgehuuzqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtkfxdksqj.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtjaqqsoyt.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtypjpgzhj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gttxllkjqu.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtmvovycih.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtculwkqmm.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtbwsjeofu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtbfdrnleo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtcomkjace.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtxcwvfblf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtcyjioosa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtpwkmqvxn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gtvxsdvzis.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtwcibybqj.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtqhwjuqxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtcwbkzmat.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtcqpfdpvx.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtwydpeilk.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtiiflnqgp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtbynbrznb.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtptntnvtx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtnxpmknmz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtphcdykvz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtdaworrhw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtwgoztcxw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gttwkxacsj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gticiyxsjm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtkzhhbusf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtubduqefk.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtghqvpsah.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtjlgcbddf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtwyazlnds.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtgsntqyja.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtsimmgncw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtkricjjmh.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtpnjuopdz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtaytuwgta.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtefruuytj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqebdblar.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gttvlglttv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbrcjsnre.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtuupxlfrb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtsmruiptv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gthgqlvklb.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtfcvsevvt.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtzijspmil.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgohkbijo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtdwnucvvy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtuajvbkck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtskwpjhaz.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtpzeunghp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtcqkxmjsr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtswtsdjhp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gtammshqhi.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtwvcdsgmd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpowqovol.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtqvktqqop.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtvtnhusid.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtbyayftqs.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtsbpefmht.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtxdybbrie.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtjmnnxfka.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtpunfqppf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtwqvqahdh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtoabgynmn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtwcnpcycz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtjrlarghf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtxtlxcpkc.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtdunmylym.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtfotlvrtu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtcbfbagfh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtnvldmpvd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtkphbxbok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtagjbgsse.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdaopeik.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtafdjccye.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtwqnthjcz.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtkowkraud.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtdjryuoty.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtmnrpqsjy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtjwqvmeos.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtydkjmnwm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtgkuijsuz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtwvbitxix.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtkdlzlgpt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtlchkzmep.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtgnxdxjaj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjphofcbl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtkbcygnqa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqxknfke.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtpoutqxkq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtmseqgkha.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gttysbkfti.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gtysbjzxue.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtiggfsoux.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtpkjbrutk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtxdgqfxuv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtcfmgjlxi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtnelnmfnt.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtpxkwteqm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gtxpixrklo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtvibjveip.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtvrklrkfd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtocntvywg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gterczyylb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gthnzyexik.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtkmpgmjmf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtvhamwgtd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtyzyxvipo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtsxtdigof.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxmyfyau.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtyjbuxpvf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtfrepqvcz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzqplmwrs.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtjsfhgzyt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoprylvfn.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtbolahjkm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtejtjjclq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtlrxfagzo.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtgkekftra.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtxahlthum.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtoxajwpwc.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtmjzrqcdc.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtlzrbkvid.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtrwnuqkrs.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gttcivodnn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtptpskaek.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtgmugutan.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtxkkmygfx.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gttpbxgzrp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtcbigiarp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gtotlovzzf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtprdzkvar.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtykazfits.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtgnfkfvkc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtyxmkenuw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtwhaknpwz.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtikexaoya.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtivstipgp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtmklrxmat.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtjblqgcps.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtgvowfiok.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gteneidxvt.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtxpsxxbqj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtsruiozrq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtfqwsylok.html


<!-- 参考信息 -->