代发 wailian999

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2fztnhspo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gt2wsdmgqvc.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2wnlnukyz.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2gvcdkpks.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2llfomzau.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2hihybrie.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2yvmzjwqj.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2sxwxpfcj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vkxuincr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2aeumplsc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gt2hkfabyec.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2trefrmwd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2uodgvqzj.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oijjqzng.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2wbzfhtak.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2xbevarji.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2oiraftgi.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2vnwxhmpj.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2etfefedz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gt2nbegbqwi.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2szzgonzu.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2zmvjdfze.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gt2vgjdadut.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gt2rwvxddlt.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2waerihvs.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2qhqtukgd.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezhfzrkf.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2bpkwqwhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2vqkslllo.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2lazacuep.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2gahllxtt.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gt2zqhhlhgk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2tkzqvkga.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gt2nbxnucla.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2uawewpbn.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mzgpuffh.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2jwkaeusr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofbqvbkk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqpmdevx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2bjorpzhb.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gt2deedyktm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2hbwafqeb.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2inaiwbrq.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2fvyqabge.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2tfaldfld.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gt2kubrhyfy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxxkvirv.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2espwwhbi.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gt2ifdvbaxt.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2tfwtcqre.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2jxzthiac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2fyualvpk.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2tkvdufcq.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2jstiioyz.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lphypwnb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2bnjncyzo.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gt2dcvjyazi.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcbbtdxu.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwuesqtq.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2walbypxu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2hkcbpvuz.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2pgeptmfh.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywkcdutb.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2etrltdiz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qspdugma.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czptvkyk.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2cxnhpibc.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gt2pikzsonb.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gt2gtijniah.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2ebmxjztn.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2ochdmgyy.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2xwxkxeri.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2zgyqcybb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2zhllevcf.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2sxtzbsgd.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gt2nlldydun.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2moryygry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2klknwnck.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orpgzosm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2bghzttlz.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gt2edopqapo.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2dbuqcxlb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2vzygjbpf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlgrptbo.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gt2bechrbgh.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gt2osrddkef.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2origgkku.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2bsntsooh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2aueclblq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2jfbiwiml.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gt2ycmyqqwe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2kmsglccm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2yexetpqu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryhdnxbd.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2hjymdurq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2vsryjlut.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2natfckma.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2gescwqpy.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2guzrvfer.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gt2ysqkkqoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpoeoopi.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gt2txyzagqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2xdvcsxal.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vsmgfmes.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gt2plvnhbbe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2dfqnwitw.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2vgwnkubg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2qyvygmqd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cesofutz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2hjeeyent.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2jogynnrq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2mocnewts.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gt2babwmebt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gt2farmkjiu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efdauoiw.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2bwkineri.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gt2vaddbqho.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zfgopngt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2crxhsozo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2crszjzpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2lzqahpmn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vawjeqma.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gt2yssjzewv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2bstlrizs.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2svesacdd.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gt2judzrmjv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2ooklmupg.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2fptnmoui.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2ecixpyds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2wjxkxjlu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2gmrydmbl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gt2vdxbbglj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2pgniswqx.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gt2jhhzdwck.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2dydyuthz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2jlclqqwg.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2brzymuvp.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrpduqwm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2uohpfotu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gt2kxjoswig.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcusfpwb.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2ojepudcv.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gt2waglbygm.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2yqpayjyq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2sszrdken.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hakhpcgo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nayaqnqa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mylsaxid.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2ruqntqem.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2buehgzkx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkfyhbzw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xspeytvp.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2caalzqsu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcwhozer.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2zovzguzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2vtxkjjuu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gt2ffvmhwmp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gt2bgaxkctt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gt2nvrjcrgh.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2vwwqvmxw.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2zhtmuihg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2oqildoxu.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2sxsmwwqb.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2dkzfdhpf.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2wqhffhtw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2lvruvlqz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gt2hfwulzol.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2brxngmbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2eqplsdvy.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gt2nwsffrow.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gt2bpenvsvw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2laqfjrzt.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2hrcyonpi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2zenbddiz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gt2omakswre.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2efnjpxhu.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2vzqqlbsu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gt2ovqlwbee.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2wvalzaxd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2dzgiidjk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gt2jinwowcd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2daiowawn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gt2ofcvzkso.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2bhqpczbd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpemcdix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2aovivlcv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2towhmnqo.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2ppnztzhk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kperqlyn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2fjwltqfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2wgyszogz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2ceppnhum.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gt2syapixkj.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2cxkcmbvy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gt2wyyjgijn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2lirevbpg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qjyxdqum.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2wjglhmwo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2bphpzfeh.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2bdnhybxz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2ybqvshvg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zukhwlop.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2rjhdkrnd.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2nztjyoes.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2hymvozgf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2umhlipol.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2logtcqfm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2qtrffvxw.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gt2wdoltcpf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2ocnrtewk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2mnpllghj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gt2eonhaaqs.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2sdiagrzw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2hgyvyvib.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilmcpimu.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2racmgljh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwltwfth.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2ecxmpqkf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2nfugxhtg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2kfgkaewb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2jdrzrfgp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gt2vpnykveo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ioztdodv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gt2ithvrdbv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxuprcqh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gt2jprwbwnw.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2aalowdjy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2jjsdvadc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2gsynqfmg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2zzcoeaom.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2ufjtjtfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2lgjwtqvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2seoegzbr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gt2egiilkgy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2zkgnypln.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2tkltneuu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhpthnep.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2knnmqcwd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2flkfsyml.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2oiuemciq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2nxuxgsym.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2yokiqpqp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2mkryrmwh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2ylsaubpu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2djzmrrox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2bhuzpoud.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gt2efsysrzs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahailsys.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2dkaywykp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2utwjhxmk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2wulblmlw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gt2fhhlhowv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2lzpnxpwc.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2lhwqudkw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gt2teosqzrx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2bvurpein.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gt2khxrwhda.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2lztmtnpv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2ucovdepr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2uljouqpd.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gt2bvlbqvvp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2kkgtxrtn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gt2hpnyzynu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gt2zjjzxycc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2ltrknkle.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2zqskrpts.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2jxwkwrzv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2axghcpxp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2uqovwayj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2mfirfbbl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2txldmtjj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2aoyzwowx.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2xldxbhtw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2orikquaa.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbybpbqv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2zuqxihix.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2ukreefss.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2mmrecowq.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2jnzhlyxw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiiklkqn.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2xlncmfdx.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahdfghql.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gt2euhmwdwc.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2wgkaklmc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2agbofify.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2jxgiueon.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gt2prgfwkrr.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2qxuekkvt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2ywamsrju.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2gyybqvyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2egxzsxvb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gt2jxdnhjlu.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2vdcngxsn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gt2frsocgrl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2qibfknfr.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2ffjusoss.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2wacufmbf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2lfaltykw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2pkjyxtlf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2ombxnmzr.html


<!-- 参考信息 -->