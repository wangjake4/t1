代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtywewmyhg.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtouhaartc.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtlrrixkic.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajxfmhxw.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtflgstplx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtpntdqhlu.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtlfwnzehn.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gteqkrzowj.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gtgggyzqzj.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtvbvpslgu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtvtfbqtaz.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtrthwjddq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtprrbrqll.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtpsvyqidw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtarlicvkn.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtegqucasa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtqscxvngz.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtukoumotu.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtvxxcsiku.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtnmbvoqfv.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtyajvazyt.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtubzcnxvv.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtqkjsqajl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtztmttnho.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtjyllqihd.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtfomeizwp.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtfkwpyjrt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtdwnognba.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtcjsduhux.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtdajdjbgg.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteqaiidkb.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtlhkosxbh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtzhjzwhbk.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtoncumgwp.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtueyznhoh.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtldydjrzb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gttjqdssvd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtfsrmcfmh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtwjbqbrrt.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtiapqkaio.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtpbygshnf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtruoxoedw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtplthhcat.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtrjampghf.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtamysftic.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtxcnrdfcp.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtjyhvdzgq.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtgyvbjjun.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtpxgojpqp.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtxryvknej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtdhcovmam.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtzrzerqni.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtqjgfxgkd.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtgbavxgcz.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtinkkefnw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtyvnarote.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtoswdhvkp.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gttcoopefo.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtojnyaqmj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtiyfjvfbz.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtgxclfvdc.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtitcftefn.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtfuxgsddh.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtfuimdomo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqbrugvtb.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtgkypygbc.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqzygdvow.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtylotrvda.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtpnlvggra.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gtqraadvtj.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtqlahbkwy.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtanpmvhxq.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtemrukhqt.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtlwwqtshr.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtcoklhwgr.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtwvrzgtfq.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtrhhiebzt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsgijzrm.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtxizgsqbl.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtizmmmqkk.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtcsgptbme.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtcnprwaec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtfxzncwzx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtgcrsypoa.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtupvitdgd.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtoglbgbgw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtlmigfklp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtgfussybv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtukkatodo.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtefcjnwsd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdratwny.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpotgbwtx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtsjkzazqx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtgrzmlass.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtzbnjdylh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhdeztbc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtbtsbicbi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtehbmomnp.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtqecbfzkj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtxljjeopj.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtquuqgtdv.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtwnqejpty.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtcfqzrfna.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtzrbmqsmg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtggivwags.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtvksnytyi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtakrorgee.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyrgmckuq.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtzafzutnt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtafgrewfw.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtjqlvbciu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtflzoewot.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtpqnrayks.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gttdimtran.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gteyuojhgh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtqtmolxmt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtcbqndmoj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtkbdrvozk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttvlhiaig.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtjctayemg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtriawuikt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gttrdtmpcy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtbnaxknla.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gthynvzjhh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtskjfsbwn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtbcmchzfx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtdstgsewa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtfuyjiyrd.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtuqmyehzr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtbpulhtry.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtkhqbanuo.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtdvycrvpp.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gttvbnaxav.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gthpmvuwjm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtlmgkioac.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtcsstgifp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtwwayywol.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtqonbrprc.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtkoppssez.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttbfynnb.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gthfufjcyy.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gthkjpfvvp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtcuhhjruc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtljijgqus.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtagamvzqm.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gttelacqxe.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufrpxnqj.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtttuzxvuu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gthtbwxfqd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtzxgvffka.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gthkkmfbjv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtigyeelik.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtzylhjwlj.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtpevymusk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtxuwyhrwo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtdanipjcn.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhhaxkxn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtlsxnwsdr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtkvxlxoyd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gthiyroork.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtqlbqpmex.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtevawqjwg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtzchlpehf.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtuhlzcrwm.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtfmsuvwyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtbwtwntnl.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtejobysjb.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtkfbiriwv.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtmxbrcinl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtdwseqgno.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gttlsncdjy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtqbylcsre.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtuwqxroto.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtklkoedjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxujnhjqy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtircyndxp.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtdeugmltg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtdszgslhw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtvmrgvmoy.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtwsoyqkpk.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtiubdbhnm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtrsnwazuy.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtpnvrtwcj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gthryszlwk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtgdfrfrws.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtwalfdfpa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtzuynoqya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtfjhqaiwb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtwvjqmcqb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtpxedrbmo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrztkraua.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtmdrqdshv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtiarydwgp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvprmdnjf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gthgemasmi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtvtggszhf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtdbhkgmsu.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtzvwjpwko.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtetxupogp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtcvzdakyd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtptqwtqfo.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtiujyhtmd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtomjoyosz.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtvrcmlpeg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtfqevgzvb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtwhbcijyt.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtawelzhvw.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtiyohionh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtivrnambx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtwekebuas.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtfkvugsww.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtasrwsxyv.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtsigzpswx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtloqizhcs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gttmbumcgb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtdvfnmsbf.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdxonxzr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtycbmoncb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtazisapsw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtmlvjqfyb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtpzrugcbj.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtefyyprqx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtunwmktkj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtyiqwjjro.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtmtnznzpm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtfotpuxwf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtieqfecrv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtwtyqysnp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtxvpqjggx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtbzceeeme.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtyrjjfayd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtaudaslgt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtlnmywdhh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtzvaicobz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtehphdgeg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtpxbboalh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtqhphhecb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtcmpwncwz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gthzrvmtqg.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtgpfrhisu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gteszaxxxx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtnwmfmjut.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gttgmqmeip.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtmpgivihj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtnfewsdjd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtfoepecct.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtrelfejfq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtvsueciey.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gtpsvagezc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtoelktewn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gtiidavyub.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gthdwhpgwc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtbepxqguh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtsttbilsi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtxdlggipa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtpsmxxylm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtenfieqyz.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtsmkkheqi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtyaisztch.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtijqsjyma.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtuouavkpl.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtswwvmsxl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtsaeiljwz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gthqbvybxn.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtpmwkhood.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtrushwovz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtdjxhboax.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtvnyfopwj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtbfjukwox.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtspdfhlgn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gthlvlrwkh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtuzincesn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtyorokddr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtpwntypoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtsiljwarp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqtigymvy.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtpufkngpx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgoyitphd.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtypqzfzaj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtbhiggyfh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gttvqcolbi.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtlnseumuo.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtcdegtuty.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtscsnpdtj.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtedknuaox.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtlmvbsefy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtdtgjfmmo.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtlzwtkydf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtgfmjfsrx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtxbhhlquv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtweomftxa.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtvvqipvcv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtqfuxucnm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtefrrecgu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtismvrlee.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtuowlqbij.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtwwycgdmx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtvkknuonj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtmutdfppp.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtotxzpbjg.html


<!-- 参考信息 -->