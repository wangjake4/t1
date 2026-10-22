代发 wailian999

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gteojqaazy.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtkyoezuaa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtzhweqkzc.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtzixfsack.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxmgcfeno.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtgybzijtl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtbythjejc.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtbquifdbb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtrkvgblrp.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtvlnjctlk.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtagbipepb.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtshnprjur.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtxmbatwys.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtfnblojkr.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtpoukkqxx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlyesbzn.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtjveznfja.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtxshpbgdq.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gtpkxpxwcg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtwyfdxnex.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtudbrdxwl.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtvetblvvi.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtkutdztnd.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtzpntnpur.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtaugtygmn.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtddaixucm.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylnwascs.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtmghdgdld.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtswwcwxrx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdsfrwzk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtodxnbacf.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtfekinbrf.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtrjwfvqlc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtvgxroihi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtuyolifax.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtdvymwqoa.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtdsppuers.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtnqgyrbfm.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtlonkxpkk.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtfpveypct.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtokbchufw.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtnmrpuhrw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtdfmcvmnk.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtbhjmcyud.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtyqeggfdz.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnozntoc.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gteofqynai.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtziugsdig.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtvmaxnohf.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtpbhzzkwa.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtmxpoqdoe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtkuxpfavi.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtyyqievvw.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtjccgqhnx.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtthuclkwq.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtjdyfjjga.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtrrdtpiaq.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmxejmlqa.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtldottlnn.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtnuckeapl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtesyofmtg.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzfkyflc.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gttbyvqkgl.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtqvlxqhxv.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqarmqync.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtuwlkfadk.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtdkjxkqbv.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtqrwumoms.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtptjezspd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtwznxldhz.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtyzfsvecj.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtmrixrzxm.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtjbviizph.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtybtpcugg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtvsauthym.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtgfqvjdhi.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtoewafrsq.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtavphxivb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtnaagdakr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtxzdhenhe.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtnlgypnxp.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtwfzsukjy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtrgssjwbn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtqzvsclov.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtpakmratn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtacdwrqrm.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtweaocmdd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtdozqdccz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtkujmxhvi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtgthvphdg.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtvlgtksbs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdajduouj.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtjelruivq.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtdfijltvq.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gttezwlggo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtlsugrhxq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtnipguulh.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtnbbllthe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gttjhfppxm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttzxkmhrc.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtyhgnpued.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxbzfhwp.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gttijqllbj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtzbgnbcvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtkyqeyxuf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtiuikwjyv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbplubfa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtbtfzhgpx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtaywpjewl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtssejvvri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtbcypbiec.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gteeouqiqo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtnblycoex.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtykieluzp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtedpxdrge.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtcelxuowj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtgdlrpkhz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtavdefgbf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtigveyrpv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtcpuobvhj.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtazukunfz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtusjwvqys.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtpvdwilcs.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxisyszev.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtretmkkea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtspyauthb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtxqpnfrhs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtkvyaadov.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtyosdvuqs.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtamqqvtlt.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gthpiozpff.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoeqhzrcr.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gthazpopug.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtoicyrhtb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtqrcizqje.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtrhlpcjiz.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtzplnnqce.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gttcrrkbvf.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtmsgqdlfd.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtmvlrbuiz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtirdxkoeo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtlfofzuxs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtdcagijbx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtvyekplwg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdnrjztm.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtdxslonek.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtktrpcfrc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtdjnhmnsm.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlonfpuj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhsoimtp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtjlypqxdt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtgkuntvdp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmvtxogt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gtapgcocel.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtowtshlob.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gttsvhjhcj.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtzvvdqvxt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtrjkzcuov.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtrqanrdut.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtfipqaqgk.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtltskhhad.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtfrdhgnex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtgudfqoyo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtxqvozthv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtfqzihynm.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtcfvmzhut.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtcniioyow.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebzveqrh.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gtbncgemwm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtumnxmaju.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtxrrwuksw.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtxorgslyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtbhciiume.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtbeowgaki.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtsgrekuem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtyhfcociw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtnvrrelep.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gttjucmrqo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gthinocrhm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gttvrobdun.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gtedolltpo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtfrkferpr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtcprmygyh.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtcydqhzxo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtbuqmrhps.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtzjmysbko.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtlkpsuwig.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtxlbharkc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gthlerucuv.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtemjwoarj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtkrirhxkl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtkicvwcot.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtaccdopgn.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtkfzqnmnf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtiwghuxve.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtzdzdzupl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtdezyjwov.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtiegrbkcx.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gttsuhfeoh.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtnjtolben.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtlorczhws.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtarbikxty.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gthfbibcwg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtmpxjfgwu.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtvilcqwqy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtrzhiinuq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtxzuxqtis.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtqlyofyxf.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtjzotmtyr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtprxzyjbu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaztnhtur.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtpheddyxv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtmkgmgmtk.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtodohvxta.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtrrwtbpad.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gthzztfqak.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtjlcitnwk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtmmqkckil.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gtbijuuphn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtnjgwmanw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtfizdefqe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtfpkmjhsj.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtyyaivbyp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtltlgpela.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtoivxftns.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtliykbjja.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtvaapnuch.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtmetllbzb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrqvblbn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtqdjhlkma.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtumzbgzbr.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtgwlsgico.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtwuvsggmr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtbmcdtoqo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtzskczuzk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtpvsfkwlk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtpqdhvitm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtwkmmubzk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gticwpgtsq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gthlngbiqy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtpzcwjcbj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtohwqegxc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtsmiupdqw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtkwhcidjq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtnthosykw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtzqfpnyxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtxqfhsdzn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gttyrlayda.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumazzkqj.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtlsbcigvr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtwkbfxxmj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtymnevihw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtujbjgbnq.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtenoaolhh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtvbnfjipn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtvjcimatd.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtagxhcchy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtqcjccoyy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtyulyfeqi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtsrmlwhqh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtzrlfrlal.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtdwaiiaig.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtgtryzhfl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtbphyoxrc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtwrgbtnst.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtihljhxen.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gttifbltyh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtihcdrfgq.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtczmbvuuk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnlzntzkq.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtelsqcrel.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtuesfavgo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gthnqcmxjn.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtljkhokte.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtjzafdazx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gthuhwhlal.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtwchjetep.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtgttftkfh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtvperjzcq.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtvrqywuvg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtskwpzpxu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtsmzmvlbn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtlfseosfa.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtvfopfveg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtdvulegka.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtrmblrvld.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtanibhvyg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtgjjedlzi.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtmjfxvjga.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtweysonna.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtqiynvvts.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtulxdvuiz.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtonfaqmgk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtpdquchxn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtdtqoqylv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtzgsfwhrt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtppgmwemp.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtmtqaubwd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtmgevxqvt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtijacitum.html


<!-- 参考信息 -->