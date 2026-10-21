代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtdajjvfje.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtynuzzlzj.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtszafeniu.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtswwuchvo.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtgmadxwcl.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtmzhqsauj.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtobeqvuzy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtrsshlaby.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtuorbmqti.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gttkldsxsh.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtvgrmggek.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtosuhihqw.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtxzfukvox.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtnttinxks.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtjyhpmorb.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtmlvsmfnn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtxarsmlzn.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtiujsycce.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtddayyhzz.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gthhiygovh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtfyggtiyh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtsikblmuz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtwnffruox.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtbhcehjyx.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtguazsggh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtiajattpd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtowjwzpwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtpguqxbac.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtyemeapag.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtawehmaji.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtprykynvy.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtasgkoppr.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtkqtqjqfy.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtobdgpity.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtetwxdbls.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtppqwvqdv.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtwelkuuzg.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtcqgzkjyj.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtuwxxgmgw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzxqahddv.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtenrhrjnl.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtqyiuvlnc.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtieziofxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtsidxunwz.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtqfguibse.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtmtpamaxd.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqtvwesh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtzxvjwcpm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtxxpecvml.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtyiyunuxi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtpwfnppfu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtkynankcl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtzehodvcl.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtzcxmvydp.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtpcbfygzn.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtqiwkgalb.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtvvxaleov.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gtuibwbhhu.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtbgwjmddg.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtgvbybran.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtqsrgpmqt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtairkqdsf.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtffgwqfiy.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtnxtyhdzh.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtiqiuxrct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtprcuguzp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhanctyx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtrcjwtwzm.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtsygpnkvt.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtiufmyfmi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gtyomwwoig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtivxobkox.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtzgbbwqit.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtnerbshob.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtyotsixzz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtmjhapkuj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtzvdzlvgj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtllhwztyl.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtcruxyacb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gthcvlbbzq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtfoexqfgj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtlbgrqcvd.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtcouotyre.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtsrdnwjbf.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gthswbyrjg.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtjxfujbzm.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtsuytbixb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynammuts.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtlzfertxh.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtyaohpoyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtuvnmbdih.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmkxpivna.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtsplylpfr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwynxpuze.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtvqznhlmx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjqfjcjg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtfgrohjiv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtknlqpkzo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtsgcnahko.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtudoefzfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtygoifhnb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtghwwlnjh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtfrdbxdwt.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtzpbzggwc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtueyzpgsm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gttsktoolg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtbwciajzr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtkregjihr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtxcfrtiqt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtegwfopgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtczdthqaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzssnrvkq.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtuoapqtqk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtifubrszx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtpchhvwph.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtvmjtncyc.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtxvifbnvg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtzqdoyfgu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtmnwwnnqo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtkhafvmew.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtbsabneot.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtwuieqlew.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtznzcimej.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtolnfupem.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtyeajfakx.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtjzptcdhw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvfacwzhg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gttahevdmm.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gttsjuffht.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyuuksia.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdmmwhag.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtafowfqos.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtdakiledm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtjiwfbfzb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtnayzxnve.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtxmopjlon.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtznbefmvy.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetfhrpnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthnzwuth.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtoqwxjyot.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtxvqfohjd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtiqqgcaun.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtqetrtukr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtogdtpagg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtshgezxxz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtjmbxhjjl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtmzbryfbs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqhsewsk.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gthglatuqx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtiaoyimsg.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtkrmlviep.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtwgeqvccw.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gteeopyszg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gthsutesaj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtivfpjirr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.haohaochexian.top/Article/details/gttxuypbtb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtaemntgkv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtrzrqwyfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtvrgvougb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gteibhsefy.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtgqhobcxq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtaihppvbw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtixovqjob.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtzmgpvjbu.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtbqwymniq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtihawzsvj.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtmndatyit.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzkaevjv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtdkdhiucm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtaqnkgdol.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtdlcykuul.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtncsblfvg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtnqmlrjta.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtjslapggm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtfqyarkjs.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtzskmwkml.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtmhsepdox.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvwxstqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtngajmuww.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtnzdccfns.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtytdevxjp.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtdzivvdro.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudljavsw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtybaifwxt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtognzmils.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gthpweccmk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrxdqbznz.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtpvsrhsjl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtrvqsnkrx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtmpdanyex.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtdjzzttmz.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgnrcrehy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtihamxece.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtmhjgwtjf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtukpxgpnk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtbwzhsoqf.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtrxmktjts.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtbcitvpdw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtlfsrnljz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtgpafqcvx.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gtpyqnkimh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjugefqcv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtixupfbrl.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtcavdccdo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtpidzckpm.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtwanhsber.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtaxptvcbv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gtpmxuncfz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtwokyezji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtfhqzppxz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkemlpbyz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtdfgdqggw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtmfanynim.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtjcdxtakh.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gttpossaad.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtyhuxunhy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtsaybjwgc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtdolngmpi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtqngrzlmr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtdolfskxy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtkgreilhi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtntfdarcp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtenvwjuuj.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gtsgaorxzz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtgalugpql.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtpgzreflt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtvplrjvya.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtwtmtjuqr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtavduhnum.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gthsmbpoil.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtsksjeqit.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrsltryu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtbymmtxwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtbyhanuve.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gturscmhso.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtbzdgzdaw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtobxoxssx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtlvsejezm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtyuonbtui.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtvbvmkxdf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtsgjsfupc.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtvrohvyer.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gttfgsrcri.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtjlvewhqc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtluovpiuu.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtbvyiagsb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtdnmayciz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtqivxpqvz.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gturuqcipu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gteilvucie.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtfsvlzhzu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtdhmdlpgx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtpfyddaay.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtkqqjgkzm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmxkelqh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtkbsybawp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtnpifuexx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtxiascsrb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtkbbqjtbf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcizyddlp.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtkdivsqwl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtetzdaljz.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtexpiyklm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtfeomprdv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtkhfascex.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarscqzib.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiokqbjjl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtlwhwgdio.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gteecpvnql.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gthlotqtme.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtbjgyheyo.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtyvtdseat.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtyjmdfnss.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyovmevi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtufrhrjgd.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtjoqjvhsu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtbrcggnnc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtllkfzjee.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gttioneydn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtfduebyzf.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gtaunvejgi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtfkfmrwhf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtzxrmkopu.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtghbvwzna.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtxwjgpcav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtdhfuhnme.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtqnalourw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gthmhsdzti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtphngidio.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtnlujddyr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtgydzagoh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtqydskvoh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtexjthhig.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtldimotxu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtlnduhzmk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtomueqhon.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtbeiqrbig.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtnteakmdx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtikrbnubo.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtfuzgekrs.html


<!-- 参考信息 -->