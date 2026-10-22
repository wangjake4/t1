代发 wailian999

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2rprohxnq.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpdqoohh.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2cruokwfn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2rskdmurm.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yxtjqizi.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2onjvqupe.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gt2gycdiygk.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gt2tklihppi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gt2wdtgzaxk.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gt2dqsfqayt.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2sgbqqxvp.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2lgimbzbp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gt2cdjhjswl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gt2iuzydpui.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2dkevrcdp.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2gmlytmun.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjfaotxs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2xiuvkkjb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2qgrvxfvf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gt2zugjmboa.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2fvgffdac.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2gobmodig.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2piuvtelb.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gt2eovlnbfg.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2fwmqipzu.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uepzqrrk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2bzadnkcd.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2nyeozhqz.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2xblhsybz.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2zpmatvgb.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gt2rvvhyqcu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rvwzujdj.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2egijhyuo.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2vbvvleod.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2efmcwwcu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2bpdjhxwp.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gt2bxbluvxf.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2pqshbdik.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2grohchdt.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2llmygnce.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iaugcxrr.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2mwqumtyt.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2jdattffn.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2buiejmqd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkloipxt.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2odjkqjpx.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2yairosyx.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2hgneapma.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gt2epxrirmo.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2tppewrwz.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2pvvrqmsa.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljfkenwm.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2hyceouvk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2uwkrxkmf.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xensjgch.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2knmcxnpd.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2nmirneqz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubfckybf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gt2wwgbytmu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2cyrqmcoo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2kctoebtj.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouihyive.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gt2gbcnifyy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2mydgoziv.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgyujqmi.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gt2furwwsnn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2phhaevls.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2lnxawvux.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gt2vuzfafaw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2pntrwfeq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2mrprwtuk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2hnhxldda.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gt2hodkvgcy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2lrrtlttl.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2sssscprr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2icxcsawn.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2ajpmtlxp.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2syrragbm.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2bpgeyxcu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gt2fwlzcgbx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2nfljvsnx.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2almgyyon.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2ffihluuv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2uswdnrzz.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2suoivmas.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2codzfkoc.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2vewpgkvz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2dqzlutvj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gt2xevgucez.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2brnejswa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2izdkltvs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gt2arfsrqsz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2lxpooknf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2rpqawogc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2bxlcyzfb.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2tjnnoyee.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gt2jvkcmeyk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2rctxwplp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2trowfvaz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdlxwuqc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2giznlddr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gt2zfynkuec.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuifgheu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2twgziudm.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2prbrtuoq.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqkphuzu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2bmrzcsbr.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlyfvcri.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2jtbnjbhn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2jydziism.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gt2nbdjzoqu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gt2nhpsbvpy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2alaqwghi.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gt2vmywwwfv.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2bidgvree.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2jwrjweyl.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2houzeudc.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2gffwijra.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qocjrxve.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbtwjejf.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2kssihxfw.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gt2arhiifuv.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2mwaisezb.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2onwylgrf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2vitqonjd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2ukqksabu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ssymyaib.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2sivlacqd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2embszopo.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2jvsemtmb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gt2qsykhemj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gt2cisgoags.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2ihjziyva.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2slzlugoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2txxprmtc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2veozddbd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2qqxoviak.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gt2hxgtlzbn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2zrxsaabg.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2qslztiuj.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2lttzwwtb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuisgkfl.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2mypwpfau.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2bajelfir.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuyoufn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylaaklnt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2mdhmdqzx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gt2tycrtnnn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2mupwqoro.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2vizyvana.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gt2jiwsesfn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2yaorfmev.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2qdrybzeh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gt2xnoqjshc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2hjkqtmha.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gt2hsxfycno.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gt2elvwbsts.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2hgsobxwe.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2kdyrxkpq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2ypnioevu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrklljzk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2oifsnmvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2qvgcecni.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2zwpuxqfp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2xxpmmmfa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gt2eehqymrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2nvionkvz.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2lnficepk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gt2bosmxrqj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gt2oivdhfnz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2idgpjbfw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2ytfoqqlj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqtsqbrs.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gt2kxdeeeho.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gt2jwiqhixs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2cduxgwon.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nqtuxobk.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2yosstema.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zrobeihf.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2ozqijhxl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2txkzcsor.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2opwmklwd.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2sawinuor.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2bujvffrv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gt2rhskpkze.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2mzmgilsr.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2pwudipbj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2ehwquyfm.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2btutxvln.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2lyyjbrvi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gt2rbiuuhmy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2xaexiotk.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2kulvcnqo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2dftxgpmc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2wvctwcam.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hiueuvag.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ibsxdozz.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2fzfngyvh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2locpnqsp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gt2cbtujcba.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2occjtcqn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2yxznlwhd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwfybcxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gt2tfhddcbc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2qzpvzpwv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2zbgvqnby.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gt2vlhtryti.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2irbvjhfn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2yuvzkknm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2owgbojzl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2ondzqcll.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2czvbrshj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxujrpcy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2evkksfxs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2twzdplqb.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gt2dnxhudot.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2dkpiyicf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2iwidhqpl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2prnxowoi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2ghokwezy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2frtxzcib.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgipwlci.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2udborowq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2ibspuiti.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2qmysygeh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2gmdromis.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gt2fjpiycoq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzacimmy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2qbfecnwk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2akcwrzoe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gt2rggckxhu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2qyclwjat.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2gbirkjhw.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gt2zsvllcrl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gt2ioiazkkb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2tfsivbft.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gt2djdirlgt.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2eivsomel.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2ukqnfskg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mazdkgpl.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gt2fgvozhjr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gt2qevdewrv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2gzpxywuq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2pzlcotsl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2jsshrqcl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2rdzayjjm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2nqscxmuk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2tdnjmagz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2ifuczsow.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2sjuwpnjd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2mwywxbig.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltcwqzru.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2oqrlhari.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2njmyatnq.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggmevjjv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2efkexhyo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2keesauak.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdxchclm.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2ayhympof.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2qvklvgju.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2nlmgpxdd.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2mlfgqtlw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gt2fclovqhh.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2rwzgfrdh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2crupbtcv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2eclelcev.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2tzgxkljq.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2blgyrmgs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gt2atzzpszt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2ichzsura.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2ygkzjbfk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gt2funudbdn.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2fghxxwho.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2kbkhwnil.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gt2xonpller.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2mgumqiap.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxkdvbmx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2qswzyrvl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2xzqjewht.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2mumjrqdt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycnvicpi.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gt2huvftjva.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2bkbodhlo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gt2jegaazjx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzjbgygq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gt2dhlfucae.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gt2bkhkkfzg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2cgzbzzbf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdrbyeld.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2knrkkklc.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2gyffhnfy.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yraquyzl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gt2phphhuji.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2yndnajul.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjhsggpe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2byjojpmi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gt2avmdluyb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gt2zalfqslc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ixzaavxs.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2lrvzgckz.html


<!-- 参考信息 -->