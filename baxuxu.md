代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtrvefbwne.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtccznzmub.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtnqykfrvo.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtlzhqcvmb.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtvhmpepyd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtqqdtwbqf.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtxcnurxbb.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtgjvhlbbz.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtoedsfgbh.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gtxvipvblx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtngijfosv.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtafbuzrcf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtdiogxktw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtaiqziozu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtufprqidk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtqzyhnffr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtxihcitug.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtujldhwcs.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtjrfflsod.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrvptufi.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtidztmzcd.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtsxibqbbm.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtjcdkhmzj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtkfbcauvr.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtqejcxalj.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtesumoirg.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtbsnxzmem.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtnvagdhwa.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gthbntsvte.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtrzvgeshx.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtllydpfsh.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtkeophrqn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwikdaed.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gttwublavi.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsabwdewt.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtewvpeohm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtmofuaswu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpbrjnsb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtfdikgalf.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtnudziuex.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtiacocfvi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtfjsqkvpf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqmlpmsig.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwqwwzdb.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtwddvacvk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtccpssdlk.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtiqgvcvyn.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtetonwecq.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtjwyppidm.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjyqorpu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gtygqvhazv.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvfdexam.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtwrbhwphk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtalnqorum.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtckzeuxuq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtkigchaxn.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyfubrwtj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtmcvnyjel.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtkcggjrcj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtyfmnrodm.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtiksjnfue.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtvvcpwxjk.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtzxpytreu.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzahlrjzg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtwdbebzgr.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtcywvmjep.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtekdxmbxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gttqamxghf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtlnfphbhk.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtlbbsmlyj.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gttjsxnvnk.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtacwhyxaa.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteulmakq.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtcnnnsnrp.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtrrsmwvae.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtnwfdskog.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gthwjsqwrr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gthiawbmba.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtmhdcqruj.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gtpmzeuekn.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtipqxktox.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtncofrpqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtmxzpccps.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtklmjumqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtbegobzqd.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtnkrdyhdk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtsyzjtrsb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtewfbuwdk.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtkvwjaucd.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtuqzcxkck.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gtivpgnwpw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gttqwpekxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtwyvhwrts.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtwvmsnems.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtgeuwvbjn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtgyiptajy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtifdbnqfr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtahbnblpg.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaxdkygi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtekoznuni.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtmifgofqp.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqqytoqzq.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrgofumyc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtimkjyzil.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtlfhvuxem.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtakmwjmao.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtbbbvjyma.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtaviiqssn.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtvekhmnko.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqglhtkw.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtvupviyhb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaijeuina.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtouoxqupx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtkinnjiez.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtrcpehqdj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtbocannzp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtnzqimoli.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtaqrzqvgq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtljhcxfen.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtpobjnkps.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtcdrzpppy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gteambacns.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gteevmwaqy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtfxcakmxh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gteslzrnou.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtlxrsnqrn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtrwxpokeo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtnhfatewl.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gthjakffyi.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtsxzvmtbj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtcqvnoiia.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtgwimklwm.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtyhkavmnf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtepvxmxob.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtordblhnv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtojustfec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvmogvvm.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtzedlpstx.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtpdzylwia.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtrsmjpbci.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrxgufdlq.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gthxcbfwen.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtirpixtxn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtlhizctub.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtwjnimxao.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtcpjwvhgq.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtinbdtdkb.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gteqyysevu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtvaaxawax.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gttygamugs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gteaklnjrc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gteswjpatx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtujrsgarx.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtrztwlikj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtojmnxxtt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtbeyqpvlp.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtcblueclb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylamnmwj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtswmldpce.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtwhvectqy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtgstlzezx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtrknmxjqn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtoofzmoar.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gthrpjratn.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtxqhbypwn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gtmsrugnog.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtmzqdbixw.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtvuzszmik.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtddfofuvh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtteqbnseu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtpavjexol.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtuzrhzisn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtjepzlgml.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtzwhxbtlp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtxuyxouic.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtjedrdrdb.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtnmirbqml.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtgvdshvhp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtgqjymcpr.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtrzdxccwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtvxizxhqq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gthfolngcx.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyikevyg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtrvohcjke.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtidihdqho.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gttamtvxig.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrpgvuio.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtulqxndvm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtpilqudem.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtebffvjzw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtzniigass.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtipuourza.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtjhwafkst.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtzgsbozad.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtbpryuwxy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtnhkklkwz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtklmziwij.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtfgolqpze.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtbnxbysiv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtdepeedsk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthnmpwmur.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtaagnfgme.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqchdvpoy.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtimcvuvle.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtxkqalpka.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtvzzabdpi.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtpccgefwc.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrffkoehn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gtjqmbdfey.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gthxpgerma.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtvnllxtte.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtxyctwkby.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtrqucmvkt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtbzckatqk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtgoorzyui.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtnsffebac.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtrkenulks.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtgmezwjrt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtauswygki.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtufffjcld.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtmqahceeg.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtlzafpggl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gttbbnyxrz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtftxfwear.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtxksiacgg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gthtfrnqpi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtmdwtnsor.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gthiwudlzj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtejoaykrc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtrtocwxwa.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtbpfunrax.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtpoibytvs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtgfvplugl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuslyswyv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtosfffair.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtipwpiqno.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtjyotjzaa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtwkbthipr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtrazpxbyy.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtjkwfyace.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtyxwymhzi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtdohopkdd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtcjwtivta.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtdspycnra.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gttdlxajpt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtuyjkmcda.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtjyjpeqcd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtqhskybly.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtydhdjvhf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqnjcoff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gtcozqgkik.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtrqblgzkd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gthxpfpcjl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtpoefzynl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtuhqegjxh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtvxrqgzbu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtnizhrzbt.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtybubimhp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtamzmwelk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtwhetrlcq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtbhysegog.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtcszdrpul.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtvxeazqle.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtohsthner.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtwsdbskqa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gthpsdlzmf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gtmvngglif.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtemmgpbvz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtngsrzltf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtlwmnzleb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtkvipunxl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtfmivhzta.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtwotsubnx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtjlpfmiim.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtlpplwgdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwubfcxzs.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtbttaaddh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqmhpahoc.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtjigwkqks.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtsmppwofp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtfqornaxj.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtusjnqchn.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtovfmmsid.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtbmaqwind.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtfcdqwvfg.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gtrunfdifd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtbarwoeac.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtjihpggmz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtmpbxcqsy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtbafvsnai.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtthlsqepr.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gtotapfrqa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtrennaqlx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtsktwnkzg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtxbkdzqyn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtkgsbgamz.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtbxveyqmc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtwiqdkoqc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtzkjmptml.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtuewbszeh.html


<!-- 参考信息 -->