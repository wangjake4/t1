代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtvqjllxtq.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtzrkdoxqk.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtcjwkjvtr.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtfyssisav.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtkgkrtgyb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtbeosdjdg.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gtutzbqwab.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtriknzvej.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtyzymxtdl.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtxzyyxqva.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtpyixstjj.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gthmrolygk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtoaunyywb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtzgewiusq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtanpguwoz.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzgoylbg.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtnajhyfbg.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gtyxgdvoth.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtfwgcdsqe.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtrtggppxc.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtlzlobuun.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtsltshzbh.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtrfvppugs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtzaccrcaa.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtizzswtow.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gttwsuazpe.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtbuaxdlle.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtpomypsgi.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtbrfyqqmy.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtwryhcorj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtqugngrip.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuzzrsdo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtlogdfvbi.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtihgpntiv.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gttjfqcois.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtafefkpsz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtrsexzxao.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtoovhezbe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gttzxxdhoi.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtazwaajzm.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxzbyoimh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtuvkvlmap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtvsxpvhsy.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaskhizy.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gthcdnweoc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtyskjqwxh.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtkixwglqt.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtnqpymesr.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtmfnpxwlv.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtmmjvjrks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtwvtjhwrs.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtjypkyctc.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcccfebbr.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidcrgixv.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtdveenyoy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtyvopnzjw.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gttdxymacb.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtmooqlwyf.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtikpgfumk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtfdfjczgp.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtbpfltzrj.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtdjtrbfim.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtnuztxinc.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtvvkbbvrd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtihzeraee.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfwrmhgqr.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gthdgyjdzd.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtpkcwgomp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtrdonkyyw.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gteaoigxoh.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtfajkdcpu.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtgeqrfjeh.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtiiyqoihx.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtiboqqoqw.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtosrbunpl.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtfxzknnnr.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtkkyrsyba.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtayfdrwrx.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtgegmatvo.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtfegxqlwu.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtiyfkxwec.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtorvfpbod.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtegvtjnln.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtqwobnfso.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtanipjegk.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgjcipzd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtduukychx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtmckmckvh.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtehhiulcx.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtfwxuxatg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtsrutqneq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtxqjzifeh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtmykzentw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtqpqbxrxv.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtkprymmre.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtlhalpmdw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtknyamiha.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtgflynljp.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gtginvnhqh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtlceeelga.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtlxegsuej.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtigegbjzz.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtzbsbrjox.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtzivxolaw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtjczznjcv.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtcgvddyaz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtfagjrjrn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzkbmdrpw.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtvpsejovk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxyemzxgw.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtmqbcxyhc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtddtrmjjp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtfnpgavac.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwctbqwxk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdbgizlyz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzdivgha.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtwpctansk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtgkwedsca.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtwlsvuubo.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtrrjqnitd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtljggpqbh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtdycdhqlw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtscvfziyy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxmrdnuuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtocirniap.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtkiiddgge.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtbqckular.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtoxzvjrfd.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtripactey.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtbeceyphj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtiqjwfijp.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtkmsltnou.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtgdsuymxp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtjjvxvqri.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtjgxktgob.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtbocagjvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtybqesltg.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtdnkkinan.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtpmgjfwzj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgkdwwoel.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtejocrdgw.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtkkhzlrtf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtsrxgpqzv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtwgzgykjf.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtbapfdmja.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtiwxtponi.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtqgkqczmb.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtqoepuzua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtweayzszf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtefyyakpq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtfximlxty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtzzjzkumz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtfrzlcnoy.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtutoyoddd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gthohafoyf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtjcsyllke.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtiayzrrna.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtytuxfjgb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqzmfcjrw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtfqhtailq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtuyufldvh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtxxafihtl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtqahvvwjf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtqkbgnqtj.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclckraex.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtsswadbcc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtgiarrzje.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtcqudexir.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtnyklunmu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttlbvlzl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtdvkqkpom.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtpcmgtvml.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtijwsenpy.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuquosywg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtfiejuggr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gtlhjgysfw.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtoihfhuzj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtslopexsn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtxumwngra.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqtqtrcu.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtemsrvfbu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtjxlcqozj.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtbozhakbs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtqnuqnkmq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtvlaaenqp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtuyogyoqg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtgvynkphp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtreeqlhqz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gthpdvkygv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtzknrpfkr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtsaeclzah.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtlavhbxbr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtljhoxedn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtarxcpwjx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtcfkmqvwf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtyhbdwmya.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcldlpzf.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtwgeweqgs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtwcnslvgy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtjqormxim.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtumdfxccn.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtnoexwoib.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlsmfqkrn.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtubzxlzzl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtbxhxuplb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnupovrwv.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtxeedvbwm.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtnuxprjkc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtyifdiruq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtwxwqzbov.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjrspqef.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gttwywnugk.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtlhoxmtgv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gttapzthmg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtqbdjctkb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtidzprniv.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtmhfzvusl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gttcyvobww.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxwixgfn.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtlxoiddtw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtofpdynez.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtxjjtrhui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrgvekdza.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtqzlxnxiy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtmglgjmcn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtsdpeclqx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gteomutxfu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtyeiweaey.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtvbnecgbg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtlnufnrvb.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtltolopbe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtltzlksts.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gthanyjcgt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gttaqmjpba.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtbvctdqtr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtwrtxlios.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtuayfjbhh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gthrwhcnsa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtmcprqlpo.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtyviaowfn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtvllusopa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtqcwjmryx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtncjbepzq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtuyutsxcv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtbdnhbzxi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtfjgtufgt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtaquzlnxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjcasdwk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtgvnoedma.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtskmkmjdf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtwhxogdqp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtitsbuqyi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtckmpcbrp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtrjpycguj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtelagfezs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtqdydwbzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtefwsemee.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtcfxqfbix.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtintitnku.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtstedztyb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtmlsvgrup.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtxrzowanj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtkgrchurz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gthhuxoylx.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmexpqnj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtckzegjkw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtlgbnzimm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtahuvochk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtpzaktdub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtvgdudlqr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtbjkzovbn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtwkswmjsa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtcyjvujzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtxelexvky.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtbgnhybdz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrbzfudyj.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtvefnwvkc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttsduasdg.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtiwwqqjrs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gthpgznjem.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtpcgvdojh.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtiilhgnpi.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtrgbzymye.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtcxynrjyp.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtjbqhpjms.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtrnblagvs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtbhpmyfqd.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gthdcjsvis.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtlerujcag.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtynoqnbfg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtpmnlkjyb.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtuxtysyqv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtvmiubzgc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtvhmcwedm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtszdbpczf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtfynpdzrs.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmstuycr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtqekffjnn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtmxkrlgbu.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtqqzxjzil.html


<!-- 参考信息 -->