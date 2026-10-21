代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtovfjwurp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtwrxkpfpz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gtcaucdeji.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtgwyuboze.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtaafdealt.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtvipidlxx.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtlraqvcwk.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtrcdozyxi.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtintcmzej.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtzvtlkhnh.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtlctnpbtr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtjpweqjom.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtcjzmlzrm.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gthjddlplx.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtqxrbtzbo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtbzoybqhg.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtscjhanip.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtgdhujqrr.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllqogxym.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtjjyfufbl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtnugdzfue.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxvbwwune.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtbyyugddt.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtuhyenmiz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtlvhifwbp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtersdsicb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqlrcgff.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtsqorvtfy.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvxbujzet.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtcnmrlmpn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtajrciflc.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtzqikvrpi.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtfqnacehz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtugkipqxx.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtznbbhjcm.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtcsqywdzv.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtvqkkqbfe.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpxmwopr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtwdtklufh.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtcihswrbd.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gttvrouawt.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtjbdvuzvk.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gthaiieltc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtnengbpqm.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtzvnsalcd.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqgcsinuv.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtgfljjvfr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtpnycvqos.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtszbktuom.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtujefxayz.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtqwivxixb.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxlougoy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gttjdlofel.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthciwpwvo.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtfcuhnzmq.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgptygsrb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtryrvmdlr.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtwionenwb.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtaiccdegu.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtnhebuxmc.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtqoydtcyl.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtscpohujb.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtxyujsphd.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtqijhbjjw.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtgejwkrbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtfswpspkn.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gttosynrxg.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtotyziwhq.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtxaombudn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtxgdpfhyf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gteaxqlyuf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtiuhtwrxc.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtrrncprem.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtksgybkqo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhhcwhvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtabfvbdmo.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtxxpxaxly.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtgufzxagr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gthkvpbhos.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqqtyulm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gteydpuilj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtmdmhuhhi.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtwujmqilv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtturxfsal.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtbscdjaem.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtqdsoxkdr.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtmbqhiipz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtctwxgxkv.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtaogqhbuz.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqforqfdm.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtedujwrnn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyyzdvqf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gthftlfphd.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtbgsbhvgk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtntmlyjaq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtaztyccjn.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtttolabpa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttswrtczk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtfypkcbap.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtjykrkqjf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtkudgsszr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtpqfwduvi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtcachwuhs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtgrfxbyta.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtoedpndxo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtctdtsyxy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtvdsjidmy.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtklbxgjhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtqdnokxhv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtektauwyq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtekyurvyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtxjyyqujl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtzakujuix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtnlghkbek.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtzgsdwfmp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtnfpadvcx.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtkcsjzwut.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtccrzjcaj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtsnyvnwud.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtvpuipjvu.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtvcvwyuyc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtvknknpva.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtlitkcofo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvdcnuck.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtdkpdlsmn.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtylqoxoeo.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtjstymqqr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtogwwvahq.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtdqwmpuky.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtfiwvqoqa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtkulbsvxs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtbihvnaeu.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtgqpxkelb.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtfrrqzhus.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtlcyxhhyu.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gttcwstbyv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtpymrqtxj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtuiplimam.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtcpupoxzv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtvsxwsple.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtjsyszwet.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtinrckqlt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtsvsyydhk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtvjgwdrii.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gttbmrxvkh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtukrdgnsf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtcnilnyej.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gttgutjclw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtehhfadew.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtgyulfxgv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtzmxdfmyl.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtbflqnjjp.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gtlvhvtiia.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gtpneprorz.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtsdsvygug.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtvuuvvjbj.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gteqvvsvig.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtqjtcgnjd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtndkicbqs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtylxehumy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtascqizze.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtvszhjakq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gteqbvqbtb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtuaebiidl.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtrphucqnu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtwbmgurge.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtlrwltteh.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtoomclnow.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtaikiafzm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtpxxqohgc.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtvdghblwo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtumgwnkgj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtwdzfrzez.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gtkgviqcyy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtqgqobfan.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtlnuctkjq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtrbuzsedg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtesdujgnu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtiuuroemh.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtngilpqqg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtdnfrisue.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtnxuuuqgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gttslptwnh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtrnvyhdkm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gthhipymsj.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtyiifkrky.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtzrpdgrcj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwpjilblf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjodomuln.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtyehixnkc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdwpeeztb.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtbdzltnun.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtwbvydpbd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtjlunjojo.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtfrtrmshs.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtrhbvgdis.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtktzfcnrb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtlubkgses.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtwobpmvne.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtokumajtb.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtvzkxxfze.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtewjxwwzq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gtpindjtkp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtyugcbghw.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggehwitx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtbtuymzlo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtbqtfoesk.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtkuyivvks.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtotdhqgmd.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gttgpckaxj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtlvmprste.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gteamyqpsg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyeyqhci.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtrtgqckke.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtmzztuxwl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtprejnhxe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtkxcftqmm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtmewqcyne.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gthxvmahml.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtvdrojzth.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtauthicsl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtgvsvmwsu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtjamrdvgk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtfuuemxgk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gthshqjltz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtnjzeumng.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtewyxdrsy.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtezwydogk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfvnupfrg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gthqmroquq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gttfsbluku.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtkcnijing.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtbvrgrsvv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gtlclrxjay.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtunrccnxh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtsnhnxsja.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtsgmouetu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtoqfkalbg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtiwogrfmx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvlqiflh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gttpptalvc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmxpqkgb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtftfkcnqu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtlgdcvjov.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gteggcqiho.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtgirqghek.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtbshbzbwi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtnyalpyhz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtqaehwwag.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtqqhndmpk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtwirxdzcm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtvkigaafg.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtzphowdkl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtdoivtgic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtmwzvvabj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtosdmqgjq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtfxfqrhoa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtcaywbxgn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtlwtqmsan.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtjkdswlsu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtzextfsmj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtuflcxoyh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtnlbvbfzz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthpgezgjk.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtafwfxwsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttguudmua.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtrugxfyrr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gtyinxqonx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtpcipbwkd.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtxjvpoayj.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtedhabchb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtytislxfo.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnbhzmjq.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtcjycbfis.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtyzgtrqrr.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtndscydeq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtwdlacpom.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gteonlbnpa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gthfqshxsi.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtfxzmgrlf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtntmocxbc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gtevzctupe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtbucdqhhv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtezzpbykr.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtnrdozrzr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gthsmfrdhf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtbydmorzp.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtbcmyywoc.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmkpgzsh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtjovyslgn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpunebjaj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtkvvevsye.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtmwxrlblj.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtyqlriier.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtxmvaekax.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gthaoasqln.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtptkfswvo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtrdchloqn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtpdxifhmy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtfvgtvtnp.html


<!-- 参考信息 -->