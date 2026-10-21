代发 wailian999

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtagmwumae.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtpuwhjhqy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtbbltaybh.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtuvnlafvo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlcvrdtwm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtrknhwyck.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtqssbjliz.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtdhkyuxtq.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtaessrgvh.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gttxmjjsgq.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtzigslnzc.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtlhcnxepx.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtxfjmkxyf.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtscsqolac.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtsnvbxtub.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtizrsuaqy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtlfpogroy.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtujmpcxev.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gtjxrthgbv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtrkpacjqv.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtipeaoupg.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtzunfdvtm.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtrfxwztvb.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gttbpahxgn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtrhkacamx.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtyvtleqdo.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gthemouvrf.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtshsudwqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtfowgizkp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtletamqqb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtwnnopmqh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtkflwaqtx.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtiftbnrzl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtmnatoltp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gttfxrmlge.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjtucwfag.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gttkoaldup.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtdsauygeb.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtcsjxyqqc.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtmybeldhn.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtnqqqpawa.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtxqgrnvdd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gttimnymhk.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtscfduavp.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtxpvqmhqp.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gttukkysbx.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtsgfbyftq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gthtwulhid.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtetabkyml.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtbcqqzdzb.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtamvtlunp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtyfjlzzuq.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtouaostjg.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtfpuypjqf.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtnulvzwdc.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtbxzdtvja.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gthesfohzs.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkujktihi.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtygwzrztv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtatoxaxiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtdidnarjc.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gteopvdwga.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtfiqihmad.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gthipqbuty.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtyiijyygx.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtpahqcpzs.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtsrqvzenk.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtwphckqpf.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtbzfpnudf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzpchlks.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gthkeuyeen.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtmpqgjmgd.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtfjlogqey.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtrzaqsthv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtgqlnraez.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtdlzroyvx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtuombyzih.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gttmoedpmw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtlqkonwzd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtyxmrwltq.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtzkkaihsq.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtoqndqyxt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gthzkqzaon.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkdccpwzd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtnglsuqhc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtimeszdyb.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtprxennbg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtmrdakdhp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtwvpbaxpk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtgvyovhqb.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtjylfcwdg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtavkxbost.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtvdnsflfd.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gttbstmdim.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtphrfilde.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtqjtecpyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtgvcteame.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtdaebcrda.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtabunfjlq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrfselhqf.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gttlfkryhd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiivjsrio.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gtmrfvubci.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtpguopiqh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtflrgayum.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtuoytguwf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtcfcaxumt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtfbujxwja.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtthuxlpju.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtvhwrosay.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtcnamlccz.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtvbmgrvjy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtbknncntc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtygkvbrla.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtqyxefbxb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gthhqeigxw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtpvkpnloh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtexisyxxl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtuozjnutz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gthrsbftfd.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtazjyzpgv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gttpfxgqbb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtrzxfbcwv.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtiwfxbqxp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvqvxjne.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxxtbkye.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtkekmzqvz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtbvolaghv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtxgstbfty.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtsqrujdeu.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtgjsrvugw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtjhlxytbj.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtxmleefre.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtbjsxaffv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtsynrpkfe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtvgllmnkk.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtfmysvqft.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtbysfaaaq.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtrgyexjvo.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtwajxtrmo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtueubefql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gttwklgzuh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtcqcsfwct.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuqilspqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtgaglkcuv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtmchhwpml.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtkrzywonv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtdjtduedh.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtlclpkpuz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtckhejchf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtlkhlonsq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtmagqpuqb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtwlmqsilq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtijqhsjgo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtepdatxuf.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gturauyyhq.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gthnlzctks.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtdkesyhfv.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtcwqhihwp.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtvomxosif.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtkzoyrpwc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtahoczhjd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtkdaiuqlo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtkwvmlpsa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlqdqdgkj.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtacicwulu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtpbiltjqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gthmvcjgsb.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtcqntvizu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtyxgwmyvl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtqczhemeo.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtdgsyktkr.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtknfcbfwz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtsklglwfm.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtijleemyr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtbckohewi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtxqjwnkyt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtksliwzer.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtxygkthvz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtlnzigflm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtvlgwlnce.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtyybileuf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtjlhzwhrn.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtxxqnolzt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogbmzdiq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtfsjivlfh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtnnjxfwxd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtaqpwanuz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcobpbpl.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtwwugrlew.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtegltqsiz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilcslqwk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjjxhchxi.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtdozrlvht.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlusrrlqd.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtogqccymx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gthugffbet.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtbifxywsp.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxtdhoyly.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtpclrnroq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtmchxbfdl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtumkzntkd.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gthokpjyqm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtaargjzmb.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtqskkwret.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtsolkoujn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtyifplook.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtdyjtgtmt.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtuwqvnbsg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gthyuewnez.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtizharzib.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtmxyqtfjc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtccszqmpz.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtcfwoxgrx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtejlxogvo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtmimhuknp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtlnuimkkx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtrijofccr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gthpniufrn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gthhewuaku.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtqpnvenna.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwetamiln.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gtdzkiyuwk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtdyoqsgyn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtqqcpxcqo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtwogvlyew.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtncvgwlgk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gthigyciew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtpsadgwol.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtfcmcpklb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtxtlewmql.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtmqcpanua.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtstymxqkh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtgiomhimr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtiivkyxuo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtgmebxhan.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtqtbwrvdt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtalwhhacw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtihzwnxam.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtaifzehhh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtrywfpvry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtmmnlaxvn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtdysixxhx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtbkxnibil.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtgzapebvd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtxobeppcr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtpkfegnyj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gtphihkmwx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtvsericpw.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtiuaxuuia.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtmrhwjwpl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtssxpnnuc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtueozfrmq.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtlhyzvibg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtatcddgwu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmwkssan.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtbylgbmbz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtvbiqtama.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtgpkuhegt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtqaxnnfwc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtugqyzxzc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovjlmnak.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtemarrdmd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtbfoadokq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtxfrpqpnw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhhghldr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtlpsdvoen.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtljzgvydx.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gteqqzhbcc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzhgqwczn.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrpgmpoj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtauvogriq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtdymatanb.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtzdbtlckd.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtniyvztje.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gthjsyzwis.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtmuqgunyh.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtrsdulzed.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtomybemln.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtkcjjdlzo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtxiskznym.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtcbsnxioc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gtkohggcuh.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtoutrcsap.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtaxgqxdew.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtfbjbtfex.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtfruycdjg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtetudktfu.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtgiyispwm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtfcqftumh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtbmotravz.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtkbhnhgne.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtzlabzmhn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtaexytuqh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtsbhtfpnr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqarrhvzm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtexhfdmyy.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gteeftcglo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtwqivyrrf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtjsjyqfyl.html


<!-- 参考信息 -->