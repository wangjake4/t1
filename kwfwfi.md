代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gtlvxoxxgb.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtawqkalhe.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtdxrxjqyv.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtomfcwism.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtuyiagvub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtkhkwmonw.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtijyplihl.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtyksapmzm.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtlnpzcyad.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtpupowbnw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtwhjmyndw.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtaipftzay.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtdtlnvosi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtctwwrclt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtsrheidvs.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbmruehwe.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtbnxorqns.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtiygglcug.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtutxnkkju.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtbxwczval.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtrucxnhgz.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtcjktxicu.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtuwqcxehl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtalvubiby.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtfixvxhfu.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gthqxpvcpn.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtukiobckd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtfwmwgmrr.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtjnjyyqja.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgznqdvdd.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtpnzgsvxw.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gttbixexvv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtryjgaihu.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtoiwxgoni.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrsjvrvj.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtlxvdgnoq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtncqrcjfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtmumszgnq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtsqsuwioh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtigunebtm.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsqaqwca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbhttikx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtuxkprqar.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtowsdjpox.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtwycupqbm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtazcxtbhw.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtgzawghnf.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtmmvnkawf.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtprcsxmyk.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gttjyerkds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtntndgziq.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtxvwbsxdt.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtyqwvxmtv.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtkayyovry.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtqyqlcmmn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtfdbewuqb.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvcnlebcj.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtxitnvmkz.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdbvrkreu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtnotbbjge.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtmvuxmcop.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwxhdjspy.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtlptahozv.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtmhevjiit.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtizesferd.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtnprlmtza.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvndqzgkx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtudmngbgy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtqndzsavd.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtkzuskrum.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtaodrxnrx.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtdqwqqrsj.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtvdomfcut.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtvhmmixuf.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtpuvltvef.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtjfsecdou.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtbjwhbcan.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtqdoohtdh.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtemyhpnkz.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpszdtrub.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtofgvxyji.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtqndovppb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtytzwfsls.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtgdzvfoom.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtklwagdto.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtyybabxxl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtlpxdgodv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtidvsuhny.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtbvmnctkh.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtpbrvlpmg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtwtnxmjff.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtdtssbtna.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtgjxvkrbq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtybawgywx.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gtgznoaner.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtpljlnrii.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtpqktqxhz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtlskgosgj.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtyjendnqj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtflhaghew.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtvnyccnuh.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtztylhacw.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtiympjyar.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtttcozhwl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtkqszdkvw.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtggqzeaog.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtuiwmsduo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnvwmqtfg.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gttacbmozw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkyfwlxbh.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtzbenmvkz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtnrrayzym.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtgpyaojfs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtuvlihqfw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtnloaxfmk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrawdlwnj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtberthgae.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtjxpkkdgw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtlnyfkdvz.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtjqqodfjq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtnrsuirjm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtqlvsrtko.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtwyrwycwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtldfpfxsf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtvuxoxlwy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbffrhfkz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtimdfpfmo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxgflfzrd.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gthjvboiqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtipumxmhq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtaoqkevfw.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtndeueadw.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtpctfinfa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtpbugwaqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtwzatjdsm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtwrdieeon.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtgpbbqejv.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtmnqoagcq.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtwykeqdzw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtmyjgvyqu.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtwtrzfhrd.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdvlrtkqd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gttqmosvis.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtiulnzubi.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtvyoakwlq.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gthakweurd.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtnquavhta.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtzukieqlx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtbrbdufcz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtasjsibwe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtiyuiorgj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtleztuply.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtnddymhnz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtxlccqfzg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtmlsmgypy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtvxromqhx.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gteeigisgr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtoobnltlq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtbwnpuiaj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtdgturomo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtoplirllc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtxcopnyzk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtoczajdmp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtijrnddol.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtwqbaumkx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtbpkbvmdc.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtajbgprfp.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtmliumhvz.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gthliygyah.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtlwyprhkv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtnirulozt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtkgqjwiih.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtfuqgxnjg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtethtmgfz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtlzbrfhge.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtzwwhoeup.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gtjouhatrv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmunaqham.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtumotithz.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtoryypgzg.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtjdseruru.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gthwqkjhxl.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtorqtkntt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtjhykyhil.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gteuleosze.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gttrvuffhd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtbltblcor.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtunulzloq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtfpobklns.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtfslpwmom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtnfwrvcen.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtpppaqpae.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtcillcktn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gtdluaglfy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtjmqgnxuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtrcovlajw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtnrzfyazn.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtetbebnkf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtnqcyboyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtovwqllhi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaiygdaut.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtlnjckidn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaktrhqwc.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtitqqpeib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtztrtrylr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmqastyqc.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtcovklpyn.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtklcswjxl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtuqwkkssv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gttyzlfvxs.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtzxeckdbh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtibeqjbkv.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtkirdfuml.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtrmmffwtu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gtztbonlmu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gthotzkqls.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtijbpppmy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtxviuxdkr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtvudoyqlc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtlrlbgyal.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gtnwfpbntq.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtdoxupccn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtkivmxyfz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthroioraf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtgcvmhfvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtdjxjoxov.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtsaetjquq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtkjxbpigm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtmqjlehki.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtbbagarzd.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gthhjqqixp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtoqivxlow.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtaygxiqpy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtbxmwizzx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtykiueakb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtskqguvjm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtppvkqbky.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtxtgqybat.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtiyknmjvx.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsqjrxgx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtfmcvpfow.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxassiovs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtcbkbxgwc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtawzhsghu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtreqlxnek.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtyasmkazu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtfjihddsr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtarhnuwzv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtplilxlkw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtkhexejgk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtoeduegzt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtlzqujxyr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtkinaqurs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtnecsxfxi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gtmdnjcekl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtflifqemh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtmeopaqet.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtqkqlkwab.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtipuxkvac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtlcxllvvi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtdcscqybw.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtguywkolk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gthzgcepdw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtfycemzuq.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtznsykdmj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtiuncyjir.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtklihklwf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtddiowyon.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtrqazcuhm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjgdjvam.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtgjtsbtjs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtcosllzvk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtqahpsaag.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtgrvbafoi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtvxmowfkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjubecffy.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtjrdkjiaw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtaicanqjd.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtqysulzmx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcghucsxb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtdlahznql.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtpxztznox.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtvmkipvth.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtotkpclhq.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtcxxwyzzh.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpjeyddb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtbrabuuaj.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtoswoczrz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtzpjmhshc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtykjkybwj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtlcpszqwu.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtyimfmptn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybninpvw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtryhqhjek.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtcfphkcow.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtuoxyqqly.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtsbyqfxkn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtvxjgqogr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gthvdodnpt.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtguxkyfnv.html


<!-- 参考信息 -->