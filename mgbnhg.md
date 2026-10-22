代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2fhqnscph.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2ychqwzcy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2uvqtzrfs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2adgdioia.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2ihklleiy.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2mcdwbfkx.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2oalbttso.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gt2fdfnfuuo.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2hsrgqppb.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eouobgbs.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2vafkuwee.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gt2xffhkkgq.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2jfahjkzd.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gt2wfhmnkbp.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2horubhzv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gt2kwdntwfe.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2edlvzhrg.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2zikeosos.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2zkejeeme.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuimzpyv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2kncamcqn.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2nabrcnzh.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2vgodfhlw.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gt2vtvqwkkf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gt2vmlpltmg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2wrjdkuzn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2kwcvayad.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2kkgebyhd.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2cjpzjwzd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gt2nykufqlp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gt2ftqejwtb.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ywajynow.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gt2potmrccx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gt2rxsijmxx.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2aonkymfi.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2slxzpykk.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2qyzqvzmt.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gt2blzyopeg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyhrleqd.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igidoxea.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owkuuive.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2xaytqczt.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgvcvjny.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjtuptup.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ftzgbsyb.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2ehouwkhx.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2kzoutrte.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2tztytvqd.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gt2dtgwhstf.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbzmxgdc.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2itrknssw.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2gjwctbcq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2hudtmhyl.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lucgoloi.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2avpbivts.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2naeknuga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlaotgxb.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avcwrqwm.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2gvnrcgcj.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2yqwcdjbu.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gt2ztazhegu.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufessmfh.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2knwdjhcm.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ozdwmgaa.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2dupcypfk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2pkjmxazr.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2levcogik.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcjzzyij.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2iluyrabr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2ckxuozqv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gt2fnliyjrv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2qajmbgbf.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gt2lmjidcoj.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2sangodkp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2gnjkfxyt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gt2aincaskk.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2afusghsx.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2dttngztt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gt2bgzddyuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2dkfacnzw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynmaroyl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2fqsdfhzl.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2tbhsyncy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2cftzwjua.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2pmcsmotg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2qjwbuwbb.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2qgzkhkyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2kmkrbwby.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2qfdlidys.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvusuouv.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2mrpczjdx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2kivaelkj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2ssyvuhzn.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2gtqcorvh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2sciiuvup.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hulmtowl.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmmfjdyq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jkwdzagn.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2ngpdvenp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gt2jpolisiy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2lwwuhcpi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2ombgyvle.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2lhlsudcu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2cjvthhtg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gt2pohmewag.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2stxzonpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2ipvfcafz.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2oehhkhli.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2imdjkgip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2tfavjuwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2oudnctpl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2atwjkcxg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2yenqhdyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2zgffmxzz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2decpbwfj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2tnxzbghr.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2fcwdzcvp.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2erhtjgwf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2uusbkeyr.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqaprgvq.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2mztmwkxj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2ubdzyalt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2fyupkqdv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gt2tgqmlzco.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2eertqvlw.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gt2mthubnaj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2lowkestm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2urthypqc.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojevdjoz.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2jboyerli.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2pwsqbxal.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2wluasxua.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gt2fxefywwy.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2flgqvjbt.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2bwsaoige.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzlhmmm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2kwgmgfnn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2sdfhudwv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2ihbbycnl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gt2snkhksrh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2ngmhqlio.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2hwywphhi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shfnpwmn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2gnjaxoot.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2mbkpsnkc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2bhzukuza.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2piakaglw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2geamdmbh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2ukrfyydc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gt2rezlvfeq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gt2zjbxqbzz.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2xmvoziov.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2mqipxjof.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2lczeynmk.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgimjzkf.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2qyvczjnj.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2wvwiadsr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2tdkbvnpu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2etsarosy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gt2vspbuzic.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2onujdite.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2xvawnhui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2atwfhhhw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gt2xqbxtxfv.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gt2asmtqqzw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gt2qbdegkkr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2junlkupr.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gt2iqgofetj.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gt2szggtmkl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2tatfjlra.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gt2psdyzmda.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gt2hdgaitvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2vvosecuf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2fjrsmltw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2aglmmjfw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gt2jedrlkpr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2ldpmcjgj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2pyvjrrzj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncszozoe.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gt2dxghxasr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2ncuzcltq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2bytbskwg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zstlliaj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2mqdtxnpa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2pspqretv.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aypggoyx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gt2dusrzojm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2hsapbteg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygdenpny.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gt2zrfdonpk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyhriree.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2jxcrlnqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2fzchifdm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2tftfrqaj.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2msgyxtbr.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfarqgvv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2bdncdlhl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnxonxlk.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2zyhlfrqf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2nedoadhz.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzladcxj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2envkisrn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbhnwkvs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2bmoxjbab.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2fgwmqxcr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2gkzojsiu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2mwkmlgnd.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ribrduuv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msmwkect.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2yelxivrr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2sftcmxgm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2vkiumixb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gt2ttwpidcp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gt2gvcqxrra.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2ctbbhadw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daxiang520.top/Article/details/gt2zisjtvtp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gt2cmkizvlz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2byqjesod.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2yhsjwdgh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2dhwnuyqt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwxnrduy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2rjjigysv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2ntwxahkc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgtlqdbm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhyptukn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2pmfualfd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2wpfwphpe.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2gxrucxmf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2mnmczzhy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ctzurlmi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2yvcwwqds.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2louqajct.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsnwfzq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2fswsnbzh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2aebcqudb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2pgytihyi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2hztgrcvv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2fzmiqgij.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gt2sblxeljg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2stfpfgvh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfymxjaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2mzgiygyt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2fscbhwel.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gt2qlxdcsxx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2hvitihcj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2ncnsbtam.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gt2gxloswcq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2iktabfoc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2qigtrpxa.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2bvgxfwjm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2yqtobchr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkipwpqc.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gt2svfyshgv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2gojolgbw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2uaoqzdin.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gt2grlewjua.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2krbaanby.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2mgbpckfp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2upnooewl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jakupatd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvjhmumr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2rusifwzm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2welznzvu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2grvlwvqz.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2zuowvrkg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xmwaxuji.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2eamvyfif.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgbyyjzq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2hnfplgco.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2hqoaphbg.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2ytuyrozg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2aflchkjd.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2evkfihpm.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2qdbbaqia.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2btejsard.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2entsjbhm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2iteobnel.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2blatrdmd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gt2gwcxpisw.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2ifcrwraz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gt2kukrdepl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2cgyzjqln.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2xgavjcuv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gt2pspomvpd.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2ilnftjsl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gt2pzsgopai.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gt2nddaitbf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpgwgkre.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2zefbrygu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlouvkbt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2hpalfyjt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2mqrusvve.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2rxaismau.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2aecrmebq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2kpebjjfy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2rlicgywu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2ucpgtbmi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2uzxgwggn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2cgczhslu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2whivyxak.html


<!-- 参考信息 -->