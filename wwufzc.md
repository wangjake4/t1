代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtoakciyxw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtmvttnfgf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtaukkkblc.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtedwschic.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtfahcmbrp.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtvauwftng.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtvmuvkqfc.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtpfhhnckb.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoulrqbi.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gttsdkpxwr.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtpknrfpgq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtdgqfdzsk.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtuwdcnmkl.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtnhailfai.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtyyyzppmb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtjvwfcmhm.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtfwtxldny.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtwpubkgjy.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtdtsesbpy.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gttqzszrte.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtopmetowt.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtihlvjsyw.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtzphkjeru.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtniauccxy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtltxxfcxt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyunwrot.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtczlwfriq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtmixxhcxf.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtoquyjsmc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtnwxcfwdy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtdpmmoduk.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtnnuntmsr.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtqknwkqzp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxqwugpj.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gtedtqehzt.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtotvgyahb.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtsyppojty.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtzsnsdmme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtwiejeyyk.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtdjrulhln.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtrlaayphe.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gttaqssqwo.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtwnfonvda.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtfuirqehr.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtnibavxmm.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtfsjmaxlz.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtgrvbnhah.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtdxdspduc.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtxafsqfug.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtzmlrdgfi.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtvppxpnod.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtqnppivao.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtztwdtttb.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtlyqkblsl.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gttnskxzfy.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvpokwitt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgayprsr.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtxrphliwv.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtqqvhzttn.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbnlhcouy.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gthnrvsqvc.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtafogntku.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtnawkqcnv.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtziwsmltc.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtcakcnsyt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtisvxbfwn.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtiqfawchj.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtmkmreilz.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtnkqointx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtryszdicc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtnxeensoq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtodlfftqx.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtseyislba.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtkordqrls.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtynlhsged.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtgtechqub.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtvjhawnqa.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtpdnhzprx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtqyvugxop.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqfefkyni.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gttwiloqqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtxqjduzmf.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjhkchkb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtlddjzdyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtoetdxzcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtbbfhxhgq.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtohmyjfer.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtfphrybvq.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtjtbmbxnu.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtgvwgrhjr.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtzccmfsem.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gttjpqwupl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtkizdhayq.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtllrxawrb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtyxbcxciu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqfzrzqcr.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtirdcxgut.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzovjzuuo.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpbnkty.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtwsrlhfug.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtjbrffxwd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrvgizmdc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtxzemrapd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtuhvvnfwl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gteleduxlx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokccfzpl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticodtzyf.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtlczotglb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpkmchaa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtqdironky.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtktadbwou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtasybsmcr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtlgjwdxvf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gttzfbonxr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtlrjtqzai.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqjaslkpq.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtobbmhieq.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtmphnmkyp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtnuiumpur.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gturbbipbn.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtwxseiuot.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtncfxvsga.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtxixquchw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtuypgqepz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gthesipdpr.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtjtlwwevn.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtpkkmsvlr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gteaouscqk.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtityebtgs.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtcjruhfpc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtesjfktxr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtpzvkhezn.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtqedbrauk.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtblqcvoqw.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gthohvkyty.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtharcxajz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtayaulyco.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtvgxhwgfs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtvhbkejgb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtolnxjtbr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gttfqjpuvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gthvjchcfl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbcxicjuv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtykaqcdjl.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcbjokcy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtkokkypeg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtiwwskgpp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtjkojnlrd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtilgmvduv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtbkvqistn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gtnhuqtfni.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtpshntlhi.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtarmdwynv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtccrsnlmr.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtfuqqaryf.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtwheyvcfw.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtmcouctak.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtizpwwren.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gthpnacpfv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtzczhfdbd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtjyqyrdfm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtgsoemdfb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtgnbgmocz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtlofphllb.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtncrlahfm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomjcsvki.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtfqufthfm.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtrhijsyxq.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtoxexrvgq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtbxlvkjvx.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtcjybevts.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtbumilcjf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtdgjrptak.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtgjinmnvm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtwlkqkone.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtkeejpjtv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtpenwelxb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtplqblklp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtnurbdxpw.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtjstdvluk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtxqneibqg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtmyundutl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtpfqrkdib.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtqkbwzukp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtyuqhojqi.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtwvrusiwj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtbejyppbn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gttzkhrtxg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtiieohech.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtyvlmdcem.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvnwultnm.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtxwcfulec.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtoezdudwd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtdqndqjby.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtukequras.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtzuffowos.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtfrrkbgil.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtefozvgyl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gteotuqyqx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvhkbuiv.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtzjduzvyy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcowolkec.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtgbsdchgi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtwohppfxd.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtimahusdz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtcenyjrfu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtwebieegw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtqrrwpimd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqnxkzoh.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtwtbacevj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtsoyzmdbz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtwvdicidj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtpigktlxv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtymzjuqwd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gtzicijavu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtygjzzyhw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtnmnrzobf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtxxbrgqhs.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtawsuistc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gtmnlrtbyl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtafzcihgk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtwmittpxm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtbczhambz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtorpzwomv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gthheloshe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtndbuddhb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtpommocxa.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtcnpwxvyg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gttckkasoi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtmlvbgrlz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gthqbmmgak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtceuvggfx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtjgptmndo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyuvryyy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtysyzjdai.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtpgrgoubh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtlzvobhqb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtwqqmlnbs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtvhkvnbdv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtretmzakz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtusbxfrtg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtfrpomjkq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtjxasbyvf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpkyvqzu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtivuyobot.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtybtosgcs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtetlqaweb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtmlyvbzgd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiirjivg.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtbjotfmke.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtegrboemp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtxzczcjue.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtetmacamm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gttwnkzjrb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtgvclymiv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhjmbwqr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtoujifoet.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtrveydiod.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtqnbzdybs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtyfcbviar.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtakuglwig.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtpjljlpmm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtnmmgvsgr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxhrjuadv.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtxiuhiltt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnioijdmz.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtbdtnzfie.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtvlczhkir.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtnjszitio.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gttymxchuz.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtffiamqfi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtxfmpctib.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtznnaknnl.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtnjwvgnih.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtbosxzjst.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtjefdmbyv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtiazlaqvz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtlcalzrai.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtjhzxnwqc.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtzukvjuon.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtqbvqskri.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtyvhoywln.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtlmfimzdq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtbikjctfh.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtleeuebrn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzyzpcvh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gttmhsezgv.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtbxfrfbqh.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtljperjsg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gthtuqsxty.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtsszacyyw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtnbgwmcrq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtyhfyalpy.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtixydszod.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtlkjkwpbf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtvtzlhjgv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtzjmldqio.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtxnwniqva.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtbzgmcnjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtulmuoqpw.html


<!-- 参考信息 -->