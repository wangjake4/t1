代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtqsdasotq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtidvruoqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtrjkdmcqa.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtkvisvsgt.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtgknfxyvg.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gthdvrkkne.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gthrifureu.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsvfavzj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtkagfnayg.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtnobqwyif.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtisjnnamd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtqscnfhxz.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtdjugzjnh.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtmhdxonmk.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtnaqwkbtx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtutbbhlyb.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtwuqxorau.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtbrpxkdtc.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtknlnzmik.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtxnxlfnim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmizkgkdn.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtwhezlbis.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtfefbmakt.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gttzvechaz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtuziwxzjj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtxmgedsyb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtnribjxji.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtsnmptflz.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gthuwfmbgh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gttpnqqgav.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtozivkwnr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtqwztvkbr.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtsspgmgbl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtapnaessj.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtexxhbcqt.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtysbcswhb.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtdiqwxpxw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtryfmiakp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtaoytdvmf.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtdsrljuff.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtyiiiikvr.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdjbvjgw.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtuomhrknh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvvfxseya.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtfdsabtle.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtgenhskdr.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtohjezvxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezcelewc.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtojuvtndj.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtztbrakzj.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtxtljqizm.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtkkqzedsk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqxtxscki.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtinhgusgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtuywtqtef.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtgjtcyict.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtemjwquii.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtpxxzkuvn.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtjhxzeyeq.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gthwiyaqaf.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtpcbvysfc.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtcxmlvuzu.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtmdkcjvbi.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtrcjanlfv.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtifyxyufy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtmihjdcaf.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtmjmyuxfj.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtepbvwjup.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtvsxlviej.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtvwduuouc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtepcsdmub.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtmmdhczgv.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqohvjvx.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtggeeovnt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtlibdjvkh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtypojmlfi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtdlvcarnp.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtxziulmqy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtokzfgcho.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtocozaqda.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtraboicah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtrlqglvox.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gttrbmugjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gteoxpafxb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtosdofsxs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqbycthi.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtzxyraahp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtfijhupnn.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtvtervd.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtutjprpsg.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtfqooqjlm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtemqzacut.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtdcivhqio.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtauyahxlq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtdbdoagiu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhfnqgxp.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtncuyaqfn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjvrmwsbz.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtubdyfgdv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtrdwtwyzd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxqsfjdfq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtghphjrwm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtdqgbdgox.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtveraqsab.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtbwfeyhjf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtvmcsvhwz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtoyeuarhc.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfrqkqwu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtjnpjtwvw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtvxaxezsr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gttclasxew.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtfnzfvxah.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtrfvazzgq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtrnqkgifc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtdiwjjiaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtljpgxuze.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtkgreiibw.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtejwiulyf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtehzdepen.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtwqcckiwi.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtjsysqrfu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtqshrckhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtwjtfipxt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtivhqbrkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtlncxshfh.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtggvyyraq.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtaoymmdgq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtbblzxbfu.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtmoftbgru.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrtqwouy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtjwmwthqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtvlnmzwlh.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtxqvmbclf.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtvojznszx.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtipaffmgh.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtitypmwxt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtmfogzrmn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtifagaamo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbksddpiz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtpwwtofvz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtzirhgjya.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtjxwflyez.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtuytpvzqq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtaiouxjsq.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtisvicoxi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtegbaczey.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtscxwcejd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtxuxqpqwt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtyapyxitc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtodcxhgwg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtfkgkfgbb.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtublpgakt.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtezymghrh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtaapqyecr.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtsuxxterk.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtrfcotsxg.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtikxravda.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gteeswcurf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtlustarwy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtdcmqrghe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtswbejtwg.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtylkwgdbr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtymbbpcfy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtmnrwtzty.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrphposv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtnmitfnau.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtxhbolqob.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtphhdkefo.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtdzvjvqwm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtxhedojcr.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtluxerzft.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtkvkbgmgh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtzndlyflt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtvoizyrps.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtoaevdgku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtvbolmjgh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtlpoojvwt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtcybnmpqr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtoixbvdwv.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtchpaqcmh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtebsatttk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtadeyzwyq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gttgrmaoci.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtyowgooks.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtwdddasvs.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtkohsjafe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtiqwfbpiu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtsktrcqhx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteyumujsx.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtpafjcmgk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmyicuwg.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtlezvxnyt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtxzqmgvqz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gttzumxldx.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtxzvwhylb.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtzqxxcgmc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtgldouuug.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtfxwlfxyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtmzoazskk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtggxulvbv.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gthvaawqxz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtkwxasjys.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtmahreyuy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtthrdsiyx.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtuojsqcpl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtpvuljlic.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtndkmzjby.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtynttewjy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtcosxjsog.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtewrtkotf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtzaxauubd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtqlkxtubk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtdnnxtwip.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtmjomxtxs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtvdtvqunf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtzubjzufn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtqvoegioi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtwxeyquea.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtyyexldgi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtjtaxbwae.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtlwzdpyoi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtsvrnfahz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtuvamuygm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtmiawofmo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtejruewbo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtscnrjsis.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtojlbcpzz.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtsspncfux.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gttyhwrtdq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtsgjzisvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtiaxhkkwt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gttkghqiiv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfdufqge.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gthunesliv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtrqyldpuj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtpxmfeevn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtvyebyyqg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtjgiargoq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtymywgwlk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtmnibpdhx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gthkfqlowi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtkiskcccd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gtpilovnjh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gttgrzfjhl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtqrdffhld.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrvwkkao.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtqpxhacet.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gtqyjnixro.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedfbeeio.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtzghsdvhv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyopzrvs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtsmduupll.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtjjafpgoe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gteefecezf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtcodoxbob.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gthfknjszk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtzjclzzkj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtpjswtjjo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtpzdmqlsi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtracjchda.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtgsqdexvk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtknfxtywt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtjfymymjp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmfhomcxw.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtfunvausj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmedgojkr.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtsfertnvl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtvevmweur.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtttwpgmmn.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtgewhpyse.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtfyfkntcj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtumrntupe.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtfdssawrr.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gttguaoovb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtwrrbfzyq.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwejhkzq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtgtgxcvjq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtibrrfhdd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtnvelfrhp.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtmaybcuux.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtmajixllv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtziewktqx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtwhyrfxmb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtufmuooyc.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtxglyqskk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtpmfsizdb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gthwcwnfoy.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtnetuyuct.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtkfshcyod.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtnymsrole.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtowtaxawk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtgpftwesy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtdsxewbup.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtrnanvlla.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtodgnibbc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtmohrkkxu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtmrcetuns.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbnbdyue.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtbfubaodh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtursflsnn.html


<!-- 参考信息 -->