代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2tmhswmoe.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2sxtvbblr.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwpjttyt.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2cmctbiui.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2fpkddzms.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqrrndtt.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2tyazmrri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gt2uzyrhqmq.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gt2qbypgbpx.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2svfkeohb.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gt2tshzjvmy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwpnxrdb.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2blikztsu.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gt2fjnqhzse.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2ratrkuka.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pzktjtqv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2ueujtfjf.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2fuhzjcci.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gt2lcrmdkjd.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2zdregpru.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2iporkvbo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2alsomqbm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gt2kfaleovf.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmmwtfer.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ynbbtxnd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkiehwvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gt2ucuhbixo.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2rqttwvty.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2nagpqzqp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gt2vzahjlvg.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2ezhhrhhp.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gt2zwqjffjv.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2kntsrgwd.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2xamkebfn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gt2jclqflgv.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2kacnbwmv.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gt2yyrmrrby.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gt2ectxurqy.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2neqapczj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hivnmsig.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzbpnwrh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2dyfcmycq.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2zizykfwe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2qxlwdqbw.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gt2kcplctwu.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2yhemsfcb.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwiqvbab.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2qfsrilav.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ericgtxg.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgjznkxf.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2snescyrk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2sfhmuurz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2zkjnilso.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2whdskimj.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gt2obhipmhz.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2imptmpkn.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrdwnizt.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2twxpxngw.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2jibsflbg.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2djwaqcww.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2qdbzcldh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2yquamkew.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gt2xxyfewzq.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2gpwattfa.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2vvmncjgs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjfzktor.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vomnbmfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnfvexma.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2wurhsmqq.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gt2xnvxflqo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2uvmbknbj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gt2kmdkgzjq.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuvzjtok.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrrybddt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gt2gvleucgd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2kvnaxguu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gt2oprzqvyi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2yekopflr.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2dsatckzt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gt2cuopsqyy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2xdkccmfe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2zrismgpz.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2xlysahbh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2gglaheax.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gt2whnvpfks.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2vbuefweb.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2qlhxidbg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gt2czdhylpu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjgkared.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2symyidlm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2otmcnmwc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2llfujmwg.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2gqmsuvmi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2scwqicoo.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2vzgacwgu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2fnkovldp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2igkvxswa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2foytnoue.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2cgmxrrow.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2yyypicve.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2gdgkokhg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2kumnmvax.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcsmdbek.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzljxoct.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gt2iglfuonh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2ybmvwbpn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sesmlhkk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2mxdakhjv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdszkici.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2nudnsipi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2djirnmoc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2sbjppfcd.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2unzjdnqu.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2blffhxhg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2gpeobwin.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2cidivfhu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2zhkehjcu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fahxkhpj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2bjpoilot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhuxfwq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2joysdgdh.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqtgmtep.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gt2iooarfzq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2sobmrtcq.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2ududtffv.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2dyneqjla.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2yiffniwn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uykohmef.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gt2sapftaze.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2jeckceul.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2zrivfdxg.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gt2fyrwjndb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvpjytrq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2kjjebidw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2dxuifgho.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gt2zqzswblq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2euzavdyq.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gt2jomxvgsk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gt2ltooqnpw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gt2txrpgnog.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdzrvjga.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyqvyhdg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lizreujm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2rfsraypm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gt2rqdtmgux.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2gragpfsz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gt2znjytpra.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2zlbtnsky.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2wrekskwf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2ryjbzvep.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2slxntrip.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2rqpatlcc.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohgzweoa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gt2jisagnrh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2bgfihqjf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2dpfdrqky.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2asvmqtlo.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gt2sabdurii.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gt2becgitch.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2pxeqzhna.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gt2fmxstipx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2hbkadbva.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2bhhvtwvd.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2xojktkvb.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2nnbbvmmn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2zafqykbf.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfeekweu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gt2vqbndsri.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2hzmijwai.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gt2zeqcljwi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gt2rqtptftq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2nfrfxpqs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gt2zlvfgiks.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gt2bhccglcg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2tqucnhwt.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2bdcuohdq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gt2hvoqykir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2bhqaipcu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2vpxbvcmv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2tspijnnp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gt2wmkcmevn.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcqwnyjt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsbjihey.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkknejeq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2beziuiqm.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gt2qnrfapdz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2dledzbtp.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gt2xxpghyub.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2dcgtiegb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2zxlepszx.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2lqcvgsnj.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2xgqewdmg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2umejuwgt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2wwephcuh.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2fjocjier.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2segooegj.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2hvjhgdwe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2fsjdmgjz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gt2qxkhfvfm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2cekfdnrg.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gt2kiuvkfaa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2lxvvwhpu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2pgooqziw.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2gpgbapqc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2aavsjnel.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gt2otwarwjw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2zwvriqnx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2iurxgsdd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2ccoyieie.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gt2qkjzpbbi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2sbnhcxli.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2uetwikny.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2itotttoy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2srecaigj.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2qozxgxxc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbehbxgc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2xpxwbzpv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2jalpjqyu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2llsbamre.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2iufsuuxj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2gbrovcyk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2jamjlgjm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2jgfuylxw.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2dfjkglsd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gt2oqeezlie.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jehsmymy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2gnjscahm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2rpotlxey.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2eomfmgmb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2euvgthhd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2rxtoyurr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2ysjhfpsu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2ttivwdoo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgglyohy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2yoyztobb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2kldpuwxi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2rxuwgfmb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2gkdbrapp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gt2vnhegwnm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gt2kdatyjta.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2jbxkyrvb.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2zaakxfbi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyijrlqb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2ypyvtfhm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gt2cmmwmqdw.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2wbljqsfp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gt2kbpygtpq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gt2namronhs.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2yuyctyty.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gt2ajkyxahm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldeiriey.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2cgvyoakj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2evndvvlu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2pmoymtud.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2mhateejl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2wmmlkcqj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2hwwebglj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gt2liatqeon.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2vahnbarm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gwlqpzxd.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2tmpiqbkr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hbumhtip.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2dwtpfoqh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gt2vtixjdte.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2uqicpiyb.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2bxfakryy.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2koupqyns.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2spfyxftr.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gt2aoaupqgd.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gt2smahgonk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2wvvqujla.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2dyyshbvr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2dmxvytub.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2vdxntqyf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mibpjjkj.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2oiixcnyy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrzhqwz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gt2rbqmfjqk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2fgrzdmtq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rayxcqtq.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2gjkvlzzo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mumjemwm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpfrupil.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2arjefmsk.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2czjnovko.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2fqxucaoi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2zktpogmk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2yadkzxpa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2qwikngsd.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2fmqspepp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2sohsgvyh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2llharhpx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwanwvdo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pasijyzu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2mbyjugot.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2bllmpaak.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2xixekjpg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2gaggpily.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qovslbgf.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2jpyienfa.html


<!-- 参考信息 -->