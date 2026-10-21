代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtbwtyaipj.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtkgqrocji.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtvurcfqzh.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtvhljvzpy.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtvbtrnupn.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtpjwvcqmk.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gthtallfmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtfiwocrey.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtdjvpoioo.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gthfcgfpeb.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtaszziltc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtcoeigygt.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyxvxjsaw.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtfwbtqepc.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtlsfakxry.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtuhaqqyst.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtsialvstp.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtwvliunel.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gteijihuwb.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtyuefmnbr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtwcvefcsf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtpfmgblcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtndsxqwsq.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtevguzpsd.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtkoxgdjqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtuhaxjswi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtdntuoeqq.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtilejihhc.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtgycccabh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtnuvsomee.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtgswpalxm.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtrbnuldum.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtrlqduyro.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtfxujjqhg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gttnhrzzcx.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtkglfsxwd.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtwbpiyhmd.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtebqrzvte.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtewrxyvjo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtmonemeyw.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtymjzxriz.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtrlcfpgcr.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtjyubcvlk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtkslqprqt.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtfwyntowh.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjosdkfha.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtxurshusy.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtfdyruqjf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcysrvbad.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdukdbdba.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtfauqymja.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtdddtvdtn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtzvsyergn.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcytjbido.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyobfwys.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtwnweixxy.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttypbbbnc.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtwzpxwyyr.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtihskexjt.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtgoqmisfw.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtegjlxcmk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtgtxcmraj.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gthjxqgfad.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtkrgiyrne.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtvythanfr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtgvaszwth.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtsohpzpam.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtabaglmnp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwtfunwq.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtkcqfatbv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtvvwyuaig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcamchvn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtghetoktj.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtplvdlfpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtpmfcocim.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxkfausp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcadxwiie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtgjtawiuu.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtmermdkgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtleftjajo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtjrkmuoxx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtqfthhdhw.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtzpfeqigl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtiigwejye.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbfccedn.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtbezgkmbe.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtsadsuccy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtclckgtlr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtxlsluqdr.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnasleua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtfsxmbafn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfscpzoh.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtvjktbwxk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwkygcxkl.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtqeeozquv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtrmblkbfz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkijzefap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtdsfrznav.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtruwalmww.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtsisuqafu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtdmyyqgfk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtrjakvyjt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gttbafeohj.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtkxxofpoj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtliwwpfta.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtqkezbjum.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzumbuauk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtirvrjpgs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtmxbyyadw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gthgzgqiup.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtulvefgtk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxqmdpulg.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtowststpe.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtefxnuueb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhjqpsyg.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtuhtloewr.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtjhwkxacm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtbgrmgshi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtqjsloiqn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtxabaamjx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtsjyqakzt.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtaqffxcxy.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtgdhazzcw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtfwwaznti.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtxadcarvi.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtqespdjvg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtvjrwasdp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtdekosewn.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtzcakpbcl.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtbmrghpgl.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtsdfijkdq.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtrlrnhbcv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtfpbvrfqm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvuzrhanb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtywwnzejj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpuiaief.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtmpwcgqnd.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtqudyrrql.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtvoebdmlm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtjjvoebhu.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtkgtxffqq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtqrfbshms.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtgdnzwprp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtzacowfab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtfyyzohmd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtjmcqmdhx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtsmkhaqlo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtqycxdonu.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngrvwzid.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtmoztremw.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtlftivdgf.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtapypdfxv.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtmiytktpu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtbmvtqfah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtrpuzhxnv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtolmykozv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtposjdwkt.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtinzatydb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtnntnmrsd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtcllefhgn.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtbmcjqqnp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtzhbballi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtodfnpjap.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrztohhw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtypqtazyb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtvhdlxkyv.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gthtwsubxn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtgyirgbef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtsxuskhru.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtlvymvrup.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtfrkpwhen.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtdxeveggq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gtmkeblfqk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtknqeycrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtwaqcgckx.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtufrctpuu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtyslnmpck.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtltvgiumd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtwbvyrdsn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtrhmmayjt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtvepsydmc.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtwafcpmzj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtzkuvjlml.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtajntwyja.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteyjhyfay.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtxowbjvsw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfkgrfisu.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtybxylixb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtiwfgxdyy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gthqvzublj.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtqpbvtycg.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtcrldcbkj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtzabwvkex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtrjmpoqya.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtatqghslb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtvxcsjasd.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gthtfzqunp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtcsdwejca.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gthvzncsua.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqxdcidj.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtznxvnugx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtrukfhgtf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtzkcmnavp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtvdyqdhtd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtxnftjtfi.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtnxmogamn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtqemxnujr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gthorjcsxk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtuwykwtis.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtfvgtmkye.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gthhhcewzk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtyrikpgpa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtxdqdrqrb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtexltioli.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gtxhchxuoq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcavtjvw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtfpdwmevy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtllaxbxwg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtcoummevx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtuxjpdazs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtoygokoxv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtzpzcuipn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtetvynmck.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtlebbooor.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtqtmkwsmg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtskwdlyiq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtnudcawtb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtxfofntze.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtrfghpikz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtgbqbiiht.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtfjaabhqc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtzpmxmzne.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtynmbyyxi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtxsellhqc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtolnvutcw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtlypaerfz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtanijrdfs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtasvqzpqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtzkepoeto.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtdidyduaw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtoimowols.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtpgfbwssj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtzgmagfbp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtrglmybtp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtrmwkbgzp.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtgoeamjvg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gttamwtvut.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjilcoeqj.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gttjjicole.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtbsaomewr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtmwmxmwdl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtpvnhyizm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfjfxfby.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtrhatfrzc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtspuziult.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgdehtbu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gtzryvmfhk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtvtyujthk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgydxgqpo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttqpykrcf.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtldjffkqy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrrilyzxl.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtipbjombu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfwdpddw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtbwwxgavq.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygevvmdf.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtpdqfnpol.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtlcantvxn.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtjftmkiqe.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gttbboqpqj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtkrxhbgyt.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtoegjnhfm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgkbwrki.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtpzgyrtmo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtxuzpopnl.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtgcrqvzhq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gttsfifogg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtzfrviywi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtbwtclytz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtvrbvvsdq.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtyvygbwqk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtryxjgrna.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtyvxtnzhm.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtnaztnlap.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtdzhdfqab.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtpdhvigxu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtviujfdlq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtxvxwlmcx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtlzmjdgwk.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtlhlewkqs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtrojzfgsx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtvfnllful.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtbmjberps.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtfsrambro.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtkvcyqjkn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtscibjlxk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtorawotyj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtgjpijkwn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtzpaxejxy.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gttsgkaibt.html


<!-- 参考信息 -->