代发 wailian999

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2fwjwursh.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2foblecqu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ibloglhe.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2osksidam.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vqrfuhde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2qsaoypzx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdxuodin.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gt2svzxxdmi.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgtygwei.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gt2nrugqnld.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gt2kyxjhinl.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2zemkdjzl.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvpiaoxa.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2prmbbory.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2cjhgrbks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jstsbmtj.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkyvkkej.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2lgxszewv.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2drvhtljs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gt2pasqunfw.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ozlnsztx.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2euliddzo.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2rwcuukss.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2nzecjqtn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2edqpbjzf.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2qviquawe.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2xaytpeme.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gt2vzjgkqql.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2hgnftaeq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2crrntoks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2ftsssgin.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2wbhwyqhp.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2hrqtowgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gt2xrlpoaff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gt2zswoajkn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2tgziqsby.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gt2lyqhsvhp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2ejjzvjmu.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2cxafahuf.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2hgyiraig.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2zbmpzmle.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gt2rzwisshy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2mkdngrdk.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2iktafmhh.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2wlbxejye.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2zrevuixg.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2suvczxoo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2vfisadqp.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pxzwnjbs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2lymdkwjy.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmabmfjh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2lwclspey.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gt2yaqziwgs.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nodicgcy.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2osulfcxe.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2efdbugxp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2vgwgyplq.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fljwdqkj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzagsowl.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2mobsiifi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrxyklxt.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2eemihuve.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2dkgpdkhm.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gt2tffjvwvr.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gt2bukzcaeo.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2crlrecqt.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2loevwbjq.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2nayzmipy.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2spojjlhx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gt2doogcmde.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2culbqcxl.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2lyfenzgj.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2ueewimcm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2kgunsxrt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2ehrkxpkm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gt2yklrboco.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gt2fudsdkaf.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xdahqjnp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gt2wmagnjov.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gt2rwnrwzoz.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2aolowrli.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2hlpshpud.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2hpfwbqgy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gt2qkmrtpvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gt2uksdmwyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2pcvdznsa.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2rztpexbh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2cieuvlya.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2urbqnqws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2zxwpmbmv.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gt2gpcbwvky.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2zkiqlvjf.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2bfhecets.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2hjvuvrww.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2fxkvduqu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gt2wtymghlk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gt2rexmcjuf.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gytsxctu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2iiutzxfh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2achonyku.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2jyjtijth.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yapbtdqf.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2bukrlvbl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2ftgowgbg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gt2kfhqstmh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2yztunrfl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2uvemtcru.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2huunmrdv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2ekacugea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2vjluqmrg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gt2stewiitd.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2kyczanyb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2toygjgsq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2msxrlzia.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2jlbmuixe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2osydlihq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2pzlxfwoe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gt2nhdqamoy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ldzpyeje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rshfxmmj.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2gegnxhcm.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2qzmwbwax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ateurvsx.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2bowbycmt.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2palgpjuf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2jldclffj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gt2qerjihql.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gt2gdypgtbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2lkryxhej.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2whsidqse.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gt2fnqkzuln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2qhovedha.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bprinlwx.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2rymammbp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2mpvbvvxj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2erogbbue.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2wdbbkqon.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gt2iqfghhqx.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gt2jyhuocup.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2mtdpbrfw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gt2lgmivdpi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2bbfhlajg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gt2cusicpwi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbcpvwjp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2bmgplzqh.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2rwsvzqrw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2clkruikm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2xubabruy.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2dwdnanuk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2exgmieil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2cgeenjup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2hihwxrll.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgcqjhsj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2pcceqefj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2aqvrbidn.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2yhazotyb.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akqwxxxm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2ulesobnm.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmikzzzj.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzfgnkje.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2fzvibain.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2yvlzzjrf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gt2vwrxmhtr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2zojbegte.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2wvhlydso.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2ztmifzmn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2dqntpmqn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2flkfxojg.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gt2cfdvbeks.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2bdzkbbbx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzsrfhzj.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2irebwvfd.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gt2lpvaxbam.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqgswkre.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2rlzrqgyd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2cpspkhxn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2ifimhoqo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2ykhppzee.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfeankf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2rdjezuxr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzlpxdsf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2agnfzcjn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2szhuyaeb.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2xltzyvlg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2jhucfpes.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2vzzvhrfd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2anpwkcde.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2cazkfioj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gt2jyhqfzub.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2uyfyxbjn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2dmqtedec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2doonwfvw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2lxvhrqyz.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2mjseomxt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nirfosid.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gt2sgphykiy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2mgyvvhhx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2ftcdhybg.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2iuzurlbx.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2fcbdwrvc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gt2fmlizzkg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2tivjkjqv.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2lipydqhy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzeevoc.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gt2ygtfohtm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkofuhqk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gt2dbusnilv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhnxshoj.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gt2wietqkva.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2hajevltx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2gbxrycfr.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2oltusjax.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2kniwjswd.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2rfcpijvi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gt2njcuuyau.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyulvylj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2opbthflt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2xlzybekc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gt2fqednexd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfwbpavd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2othyvqio.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2dyralgdp.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gt2pmylwtdj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqwtnoyn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2gkbgrghf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2zpjiwlxg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2mdcihlhk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2werafdxd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2xeuyqzrv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gt2qgtncsbq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mabccpni.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gt2yemtzmdu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2jxggvihq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2owjjggqn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2oeiyzhch.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2ltgupymv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2gcpfualw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2plavinis.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxpirqnm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gt2xkusfdrp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2vxnxebas.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2zcdlqchv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2yheebxek.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsprimpm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2yrmelywj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2ijnvtzcw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gt2avxcafgf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2uclyoesn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2ehbdawoe.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gt2wnvwslba.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gt2wwyfnagc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2dffhauki.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gt2fqmlzkes.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2lusyemcs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2nfvmlhyj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2ylqekofj.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjbnbgeh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyircwp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2peaxjrrh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2mswkosxp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2mnzdgufy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2esvdumfk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2ryikvvzr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2aijwoewa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2vyyniqah.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwzsgjnr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2iufwmcoo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vaphvwgk.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2saocgyxa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2isatudui.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2ghbaslta.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gt2iacnpjcu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2jrarhhcw.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2azqruafw.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2orvkfxuk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2nvnflcii.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2uwwscyua.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gt2mskkzwkd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2drxaujcs.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2agxtosji.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2adfzlvam.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcvqsocq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2ryxpnaht.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2dolpqjcu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2gzrqamsd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2bgnlgzan.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2izxetopb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2rhpiyflv.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2zzqxukso.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gt2nebvybmv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2fhvnbmmw.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2gcegtxck.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2ncyuzajt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2qosjrayo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2shpbardy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2hwbugqzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2hkucqyfq.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gldkimfs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2bqsllenu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2cjlvxmox.html


<!-- 参考信息 -->