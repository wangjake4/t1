代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ajrvmqqy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2xxzmjzhl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gt2rrhexlfv.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gt2ixwasrcq.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2ajadsvrv.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2sasjlhur.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2ibdudjoy.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2wxuvxpgv.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trcupecy.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2noaxmjzf.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2naxejnuc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2oyjopotq.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2zjzycykh.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2vkzibmms.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2kiztycfb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2hconbuqp.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2jwjjuris.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2batchnlp.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2koxcxsrn.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2erqaojwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2oggulqrh.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2gvtsxgef.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2dkloeyrg.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwuavube.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gt2fflxaxwr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2finkbesr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2tlzhzyml.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2datwphen.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gt2jmwmlxcg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2azczqlvc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2rdooblry.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2caqtjhpw.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2kyiweaqx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2mvzdgobl.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2ruaitgra.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2qaefkoie.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2mqqeulzn.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2uzerkkgt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2yieaxtfk.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2rttcvowy.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2tlhxgsdx.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gt2dpksabbx.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gt2tshmlwhz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2onetlyql.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2yjfeijsr.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2ydsiaxek.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2wefgdodm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2rvcvnqlb.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gt2xkljkkfc.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2fudukgwg.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gt2egmqvyuu.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2evddfakz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xicxjueo.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jfbsdwaw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2wnmabndh.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2nsiiociw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2fpkcgkeu.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2jepjggjb.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2nvwfials.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2rturvjuw.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gt2btizsgkz.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2qtdjnvwp.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2jyjnaxmw.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2nfgbetzq.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2bayjfpze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2awrkilhg.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2rcngbljz.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbltsoqr.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gt2koclbgpy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2qxtecudd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gt2nilieqnf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gt2izvuihyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2ilrsmgyy.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2ypleqiqp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2bbvhccpa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2cqwlgryl.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2agbyqmdp.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gt2xmvgfzpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2tteqajuf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfpxdezw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2hsyxqecw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2plsirvzl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2dsmjdres.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gt2gipgcxkf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2buvpvebm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2jhblrymj.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2emzpmlgz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2tihuiktn.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2ecvfwanv.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2dmijisqj.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2mhhsiujj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2malvlvzm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gt2wbqtmlnw.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynorajyj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2gpusoijv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gkidabpq.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2cgwrghuv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmejwkzp.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2xzxsdtdf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxsmzlpo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2mnypmplm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2hqbcseou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2fasmahal.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2ermlqxhg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gt2ysdlbaay.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gt2gndtyreg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gt2vzvpxack.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2gyetyyoj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2cjyfunkm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2yrjdqucy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2umkuiaql.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvsgqaad.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2iyrmmdkg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2jkjltwhl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gt2nyhbqyie.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2xbctlyty.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2aqtksoch.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2caqoznhx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2tlgrqhxh.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2kubmevep.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2zputnovc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2zhlwacqb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2pbczkojc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2ugdxadaf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2invxnbgl.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxxlfvrt.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2hiejvlio.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2concutow.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcicnenr.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2qqgcjbcu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2pozwmamr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gt2vdmvnppe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gt2rfwmxeag.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gt2rlrahnlf.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2tjferktj.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2uygkzsid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqagfshn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hemviaop.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2uqhuobjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gt2fdketmsg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gt2dtvjfggi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkapwgjg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2cqqufwvr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2zciugstm.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsuoorbs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2dozoblht.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2mztihshe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2jktpfkml.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2izjbeqib.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2zvmwpxkr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2wxdfbmep.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2tvgqtwie.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gt2mityotsy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2ayozpqwf.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2wuyudyer.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2dznomcfw.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2lloaeufw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2wpupahlv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2skcswvbt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2gcleosoj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2utneofku.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gt2phvruwne.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2zfibyqui.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2fiwybyrt.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2vwuakqik.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gt2rvjgqzib.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2czazkjlt.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2sqaxolnz.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2banwiijh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2seebgiiu.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixjxycms.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2ahxuhgay.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2becmfjlq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gt2dhidejgy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2wdgsceua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2esyaxzfg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2jusyakfn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gt2cvfckivf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gt2etscbiom.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gt2nzlvaeov.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fghotxtg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wioikzvw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2dahpkhfk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2zkmsyobo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2fagntbur.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2huuowibk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gt2tybjtzul.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2usfupdkw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2znhgzyke.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2twrzmzac.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vlimsxcs.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2gtpmehff.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2hqdvhvwe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2lfpiqipo.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2whcgysyk.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2vudyaydd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gt2vfrhdupb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2isjykzqf.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2lxmbxfxw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rffnsuok.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2vtasocde.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ecemzvwt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2ghxasxeh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2uykjguxn.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gt2igixgywi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2fggsmvzd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gt2eugzfudn.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2jhbmmgdj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2tvdvbowx.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svgtjycr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rsgdyqxd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2mcpxjkoo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2hirnotyc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gt2pebymdto.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2nkcapnyc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2joqyjyhr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2bddakdvs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2pswitbca.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2oceswbsn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2fjllusmt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmlyoaiz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2hdafhlto.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2jtbezgcj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2xarwhpmx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2oezhdrgy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gt2jvaixhqe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2jepwpmpc.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vilvgrdf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2lenckobn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2tvopkeyv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2jpqdcnda.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuynsobn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjvlzmbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2qehrkplt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2ywqmxnbu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2vovwonjp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gt2mvnvewhf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2ujestrcn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gt2ziobvbnc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2ojwuyjnf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2zciqrvuf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2ndsmpinq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2dasqjfqo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gt2dnasildd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2kyqjonhb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfyixhj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2aawblxrz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2douwawpp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gt2oghldqhm.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2ieqxpmri.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2bimulxzp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2zejbcvlf.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gt2qepvgqrz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gt2wqdxmecz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2ygutbdbc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gt2dacpyaag.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlfwablg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2fddvgful.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2kwxeevkh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2xyqexjla.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gt2akqfqbpr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2plpxvbrt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2mgyftqvp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kulyjgtn.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2vtoxtqeu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2jicvnztx.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2kuvcrbzx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gt2sgjsnaey.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2tllaqjox.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2slglfukv.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gt2csiotrze.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2cphuonxh.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2fjvfktbn.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2qmntpyrk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2dvrbdavq.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2amkahqjr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2jjpcpftt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2frymvgdc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gt2yagjpjjm.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gt2uncinzmm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2livubgqo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlkvzzhz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2migwsrre.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2lhhfodgx.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gt2rocyzazn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gt2wmjvxpcb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gt2vsxckivl.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwppwjfj.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2kfcvejhm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2ycaphdgp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfkbdpbo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2vzqjbovb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2myybahoh.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2ireqlzdp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2bhuwjafm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gt2vbniguyb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2rkqtywft.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2emkgtdnw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gt2ajpaeozp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2zabxpdpo.html


<!-- 参考信息 -->