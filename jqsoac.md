代发 wailian999

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtgmwygkte.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtvlqcuylq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gthqvtpahu.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtfuhyhlcb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gttndsggpw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtggurcsou.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtqaaqhaee.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtxsdfzhhw.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gtgtgtnyrg.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtuuzggoen.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtciuzddrd.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtezphpzfi.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtomiuqglv.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtqgpmbgcq.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtlvjsxypo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtpdevhmag.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtrvcosdpw.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gttqlzmwef.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtttvmnjwa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtgrqsthkc.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtzibypoai.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtckkfwlkj.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtebrkyltt.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtqyarsxiu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtxijnebri.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtfywepkqc.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtuqeurbss.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtbzydsygu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtrhlfsbcl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtvclyebuj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtfohcrupc.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtzkaoohcc.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtsfxwvzxq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtilhoureo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtbjzabykg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqtkeaajt.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtphstbbll.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtozvygosr.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtbknzvkbl.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gthnjrjdqq.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtsymgidyo.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtvcvjyqep.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepgijwri.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtsqsnaqhj.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtyvehjhlb.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlihqvkq.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtizvxvhsm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuouzchq.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtacdiltpu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtpnwhtojp.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtlhkgmdbt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtxteatmoh.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtcdvuvynh.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtgohljziy.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtcedrnwph.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtudcusjbv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtwaobrwqa.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnhebimuc.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbgdvkbyw.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtctuhbaie.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtsskfuqvl.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtclmlarfr.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtmlvdfplq.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxqhfzsu.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtwpcnwdjc.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtoffsvydc.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtmggrmyhq.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtcftusbra.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtkujzjnyd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtysctbegr.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtzxwmlpji.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqgemsqp.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtsekwdlwi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtupmpbpbf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtukmvayly.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtfeigqxpg.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtdbsyrajf.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtxkwmwwlp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtwzylrxau.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtdikwsysl.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtubxtislm.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtecjzaapn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtwgegqbkk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtwjmxbhuu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtqwnzsgme.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtpsybdpor.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtrxnirzif.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtwemiycfp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gtxitrjnaz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gthvxaapuu.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtvwwojumw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtdiqhsihx.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtpsxntmqi.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwscwjdvw.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gticuxzywk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtpjrinchd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlikoerko.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtbhovfrso.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gteuyffuac.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtksctzaau.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtjjtqbtyb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjlowhbkp.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtqgxwesim.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtltimhbsv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtphmshcia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtunsvvsgv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtdtfckxlw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtjqpllkug.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtmkqtjxnk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtdxlwetao.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtfrrwjxrp.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtwroehxbo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gthntzivqa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtinqwtnak.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtjxwpfjol.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtfrcckfsv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtscpjddkh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtzzfgqntm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtkvhovfhy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtxhyjsnnh.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtvlcvmhlu.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtzihqcqpo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtdfpiwmmz.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtwlsviydb.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtcdyoylzm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtyiurrgpx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtnfplqfbw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtpgllnsek.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtvgtotpqq.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtrldgwovr.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtxkkabpgr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtznwpvbhk.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjslvoha.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gthgirqpwm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gthzutaqmn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtktpbvvkx.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxqewqokw.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtxkehfdsq.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtljcamvoi.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtxwqitrbk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgyxvjki.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtplhwfvby.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gttfdszrwr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtchypewcp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtlskqfzcd.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtodffzvou.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxmnpexg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtqviqnzju.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtcmllledy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gttrnaveto.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtkoywkfhs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtsifrztcg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwtbjkho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtydwinepb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtedxhbzuy.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtmmjfqfyu.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtbftpamri.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gttotvqcgr.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtfcdmweol.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtqswtbxxk.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtseqpslvc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtroklocbw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtemexxlbr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtqvtssqxb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtytpvzitd.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtnafvivmc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtazgopdnr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtaufgiyjq.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtzhxpbiiy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtnbwbeods.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gtrcubrrvv.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtfgiggdux.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtlnpyssvv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtgcrkvnuq.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtoqwyjtyu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtsxwsyibx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtcjkauhiz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtlrgbsppt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtkvnprkqj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtumxcoucl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtbxywrxhg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtqhhizezt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtrfczsoil.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtnaoukazw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gthqeprili.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtpnvkkgha.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtymwvwlnt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtneoponur.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtfldrglyc.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtiuzrxpmi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtriatvyvo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtvhxtcypt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlzvwctcf.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtmkshdkhp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgbwumlvl.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gthejsfves.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtrjyqqujr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtwiubzfth.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtablieuwv.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtupispyoi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtqymrwojy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtyywwqs.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtzcliglkl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtpjvukyxg.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtmwcpkdoq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtlcmuineo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtrrwttpee.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtyluhsgdz.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtvrnzrlqu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtehljgmlu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtynvvndod.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtngcxrhme.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtaxuxnapr.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtqeayijdc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtikqrafrj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gthajdtvje.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtemvuozqq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gthuoavxah.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtshlbflic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtrglsheld.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtwlnpgfav.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gttbfdekef.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gtohhiodkn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtfafairty.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgapvphst.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtskfcwjod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtrrabhrju.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtntngxbhl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtzzcknjzs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtxgoxwrss.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gttatemakd.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtrkklohzw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtcccszpbv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gttrevvvnd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtbcrkobic.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtuydatfga.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtghxauwam.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtzpqzkxsj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtzmkoggcj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gtxsjuveis.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gttbwwzofd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtsordshkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtgmmxkjyb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtufxhebsf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtbmcqirou.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtwcwaubvf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gticogszoq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtcrzyseng.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtiunfatch.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtsirpivvs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gtvqjwqxno.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtpjieprxg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtqrngufuu.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtvaqsxfjn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gthcelvtrs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtsjwyetwu.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtowqrnbrq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtnftfswpu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtqxwnygmo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtnwvrhgbo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gttvhlylvu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtdrjplwyu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtmyxsbkdv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtgbwvxego.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtzplkfqsu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtmgeqsaxg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtqdziphhg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoujvaltz.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtnvfpyupl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnlvosmpn.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtxxgqkgef.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtiozornxy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtepoxgwvq.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhbxjsmd.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtpihzptxr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtuzdxitlz.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtaeijwffy.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gtuhwthjwz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtksfupuot.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixtvjhko.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtrzvwrczb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtkqvycmte.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gthlnlvbtt.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gtlaikdmyf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtlrbnxrpo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtorgpmvtm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtovcvxwan.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtwhcajbnh.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtbpsdeeor.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtoplkgoac.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtvdzwtjyc.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtvkxfyllw.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtwdytmdvw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtqnvdypkt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtadijzvae.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtqatsghsn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtwcfojdfy.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtcefsxbhu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gtwqufgzvk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtsdjfvtro.html


<!-- 参考信息 -->