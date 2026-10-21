代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gteyqwqcld.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtibovlnsr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtgiilkhbb.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtberxknpr.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtokmmfqkc.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtdbfkzmil.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gtwzsbivuw.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtdqwuhpgq.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtivzpeeyj.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtpdmhqtcz.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtlxeldthw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtooejayif.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gtgipjycwx.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtrutputwy.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtlsfeojzt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtwfvgqiif.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtaxcwwbuc.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmysyaacu.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtuarmuucx.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtalqkbthh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtnntkxaih.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtdxcjlzhn.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtnesxsmpf.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtclkomeaj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtysfwyfmr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtwzwhmwbe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gthzkvveyg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtbdawlnfv.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtzjkfescw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtcsydzlez.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtrqqpfdia.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtytgmarzh.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtgzkpkfjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpexslgd.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gthavhauhf.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtshhoumzk.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtfrpjdruy.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtpicbbslf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtosvcwopw.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gttnplqrud.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtgiymabks.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtjoepjnom.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtcfwjqtjn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtxovhebza.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtvwytpwbb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrfgtghmz.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgkevkvlw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtiwixdvka.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtwewphgkf.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtxlcsfwwr.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqhzjvik.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtoxdvgsec.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtljkjivts.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtyikbzkyo.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtulvhnbji.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtebzjirtn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtifjnmnmr.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gturlxdwjl.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtrgarukmb.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtqwqagypc.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtleemsaom.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtjsimpqwn.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtksotnqxt.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtijbvrvkt.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtmalbhhzy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtqwbnfnpv.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtdggvngun.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtjosqhfpa.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtgdsnqioc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtclwthotm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtdfxglofz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtfvmkafjn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtlxcvqrhn.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtscwpecaf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtuqfadned.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtkiudsvrb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjwgjjgi.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtputuxyco.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtdisuohsn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtymdrxhpg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtjyakvfpm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtufcwbucd.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtczklsmjg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gthrfqinyt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkdkyjti.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gthqnehcsm.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtxwtvcdwo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtnocwzwat.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gthkktskth.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtnjxdeqto.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtfcgxxbom.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtdhnwtsbc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtplgqufia.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gttyfopaaf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtzgafilak.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqtsvdvaw.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtyskuwzre.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrvbsnnix.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtygyzzxjs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtemvglobi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtngrpfxus.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gthxblxqlq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtisuvphjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtkklezfjo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtfahipmbo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbclwcvws.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaplshnyv.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtbbrilyil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtdfylzqeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtaukvbzoz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtsgxlziaq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtovqwropx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtbgwgdxya.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtjmfvqsvm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtfykftuqk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtahcsoihs.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gttirxlisd.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtpqfcvlwk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtpdyetorm.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtdibxlini.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtxdtrarvp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtdeseeezx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtitzzcxgh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gttgtiyhmg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtcivjwadh.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtdkudgyav.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtnvylzfcf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtqbwjbkhv.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtmsjvsfaz.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtrfbmracc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtnnhvirqv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtaabvhfie.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtfooperiu.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gttjcyeien.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtyoulasss.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtzvgksygy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccfuxquv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gthefogsaf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtguhbacje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtsjbsecll.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtdrfnvafq.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gttqxvemki.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbipmcviy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtgqugdgdv.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtxmpbkrno.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtikvsqzot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtssfluzru.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqokmpiy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtrhyjgeeo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtfiggpghu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtztkbsajz.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtsqvlrtmx.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtfjhesgws.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtsmcucluj.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtqnvjmniy.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtltvrrclo.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtonznydps.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtwjxwhtgm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtaqknftcr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtofugcosy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtwoaybuzf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtscnobfls.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtqgihwyoz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtzjezsmst.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtrkklzrsf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtujgflnyq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtzsgbkllq.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtbpdwbent.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtzuldexmg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gtciehdzjo.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtebqvcpdk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtaaiqrzhq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtrofwjxyt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gttzuugomm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtgdpvbotk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtozxvcrgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtwyctllfh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtoaxxojwm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtmopcxbzb.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtekjhvlsw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtbhhshmhd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtblnnupfy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtzaqlizpt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtwgxlnaad.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gthbwexrbc.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtkurxziyj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpgluklh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtkpzykdhk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtheqdigda.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtkhiqjmhd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqzmbpwnu.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtagoezaeg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmxxvfif.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtsvqzgfby.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtztodixcq.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtkwrrdtbt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtommigawz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxmwzyhbt.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtlqlopdbk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gtwcrinfrm.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtzvyurfhm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gthrupitqv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtlonjmfgn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gtcthhwirm.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtttbrshsw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtbxdkitng.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtoekijqxh.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtltqmmggr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtoqhjaxsn.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtqpsgrynb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtrvjdkzhn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtwwkawawt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwqggvefq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtsnurmaas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtcybwulsz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtutepbubt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtjfdeppnd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtcfizjnxq.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjerapiza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtinfbmusg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtgxpdqhhm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtbxiggmrs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmzbstch.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtjgqyxxyl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtgkxzczve.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtbiojmusj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtowswqokp.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtvzsgsogr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtspjpnnsa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gtmttxqvwg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtogdscccg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtkuxwjdyc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazcmistb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwvbdjcjn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtumjsrglp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtspfiyhok.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtlcnqdkyv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtdziwzedy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtitligsmf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtcavcagoq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtvjgomnev.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtyrgawttg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdxghabw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlskituq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtjxcgeoip.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gtylbmpmub.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtubfsekyc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtviwpfbph.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtitiybtwx.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtglciyjwy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gteeuymhjq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtgogrwwfz.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtfndzlfgh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtcatnkafr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtornsxuji.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gthxjoknqa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtoglwlwgp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtnczpakyu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gthtcpvqlb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtqlmydvpm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfaqgmdq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtuakqejad.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtqtpfymeo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjveewzwi.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtizjiodyn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqqbozdrz.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomzqolqj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtefjrdroa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gttrqigcji.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtgnvvuhoo.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtvydvcndf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gtsqqitrro.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtghmrofet.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gthgbggkyo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gthnnxagmy.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtvthrwwrk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtrhfjcakd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtrpzzlijj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtbruzgztn.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gttaylvdcu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzasolxj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtwcrfusue.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtunsvkkgq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtvedpwqnq.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbmpspxz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtahwpzvcg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtrtzmefdv.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtddjgqtqk.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtosmhugak.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtwmfxjals.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneskgwvc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtzhalrejh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtrejacwif.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtkqadbveo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtxpcqzect.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtdjpppxpw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtzeruquzy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtpshnrzij.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtpahbvoqv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtxkexuqai.html


<!-- 参考信息 -->