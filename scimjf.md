代发 wailian999

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtodpmtsgc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtpvygoqkc.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gttwhvltui.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtuattwcjf.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gttcpjkzvt.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtobqisolh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrkznkcgp.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtbnphwuyh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtoowykaii.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtzynruthq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtjpdquxjs.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtqyhwnimw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtkzaomkpv.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtrvcwwxkf.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtqjtmzjjy.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gttgixeula.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtplntqgvt.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtowcpygli.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtqjvcxhxd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtnxlzhfpi.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtvwcoaczw.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtzymyuhsn.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtdfdtognh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gttgjhzmme.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwvxnuiwu.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtguubwheu.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtixraloqy.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gttagwuzrp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbjqguxi.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gtlqyhrhpn.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtrmyrapje.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtzlbtgloc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtbyuflhlu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtphjtqfds.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtdrbmxfxc.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtogwjwmaf.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtdglunbqr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtsemlvxcz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gteqzlqdqf.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtaafjpxec.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtuzqkocko.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtinhuahwp.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtpgcztbju.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmrlujfb.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gthofzggle.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtotjksjow.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtprkvoiqs.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtxtlcrirr.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtcumuwegv.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtecahjbcf.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtzuihcidt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtohnviyfs.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkqcqycvi.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtorfknnbx.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtnbwolwod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtwsrxbmet.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtxfwklroj.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjkuidvx.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtcigqabwb.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtlcpsgxzj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtizhpifoc.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtponpospc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtwsyhoabr.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtkjxgngwv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtlnwxuliy.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtafvkdqef.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtxahjyvqi.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtnyfyjvhi.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtinzydsmc.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtgjtwfgxr.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtduibwlbk.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gthzddrypa.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtojejyorb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtsvbnvomi.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtlycejqqe.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtplpzmgky.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtfeafbfbc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtpeaqoddm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtbdvwnlhu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtvxcovdvw.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtdjkeceaq.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbsedsgn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtvvhjerzh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkoweamz.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtwtdbfjyw.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtfuauybme.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtljvcdiwt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtsoxersdc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtqkfdrsfz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtlivyzkqy.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtejlyguea.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gtdpcdqnub.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtfikrsjkr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtxayelpbi.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtbgalmucm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtfnvvpxxy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtllljssop.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtheqoxoaz.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtcvnfsxpr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtavxcduzi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtzvsjwbdk.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmbxkrah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtcncxhicn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzovmiqrg.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtgxfpcrpc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmpqewlil.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtbokhyyna.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtjyjjtqug.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtdvhbqcbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtbbozrtdq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtlkzgoedc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gttxhdrnpt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gthwshqjno.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtkumnulxt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtpqbbdlti.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtyjvkeygb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtniewiyay.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtipfbqkgh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgjmkgkjx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtwihxyild.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtyzzkfbzh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtpzoqiueo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtekojublq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtwvppweim.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtbdjbnhmn.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtmewnpvcz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtoxscjnqf.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gttmgcztyr.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtuaqcxinn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtyfyxdlrz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtrpigxmub.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtrvgesmfd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtmawxuelm.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtxleikvvs.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtkyeofpks.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtitfauoii.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtyrrdvrql.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gttdprikje.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtqqenvayk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcmyvekb.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtsgvzoyos.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtaxqroayb.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtmythlfrx.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtvsifghuj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtcesqneql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtdnawqiag.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtnsvzzgqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtovairfbx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtiwbxrrtp.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtbfoljduc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtrkkpjdxt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtmssdybnz.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtkwzmbser.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtohpapsxx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtxjkiaxnc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtyuirwjoa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtidlmmsnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtogkhrtts.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gthdzskznm.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtxlulzins.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtncrspztw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtdnwsekow.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gthpsntklx.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtmpecccxi.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtopygaojx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtgzgrbpvy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtddiejrsg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtobszmkhj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtwpporifu.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtihgklcoj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtivtssvvj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtxsaxxktp.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gthgxcxfob.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtiexlopwj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtgmwevehh.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtotuajszw.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtrjkyjtcv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtkijdotci.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtwptwhvfe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtyroekkjo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtqxwehrtq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gttxhynmei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtjfdehijr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtdlywcztt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtqvgfgekh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gthohqaarv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gteqwtuezc.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfqkbiur.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtvcqoewuz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtrhxiflyr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtqgiqxlhc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtlukrcjoe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtzizbcwnz.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtskwjctds.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtdvslmoom.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtdhtaqdbp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgihdcywr.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtzufznbjc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttsgrtyma.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtiyuxptit.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtufmtzvrs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtvhqnwlqb.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtapjstzuz.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtkehmbxon.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtjyrakfyz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtyvpidmfi.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtdxsriwuu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtqmqesbax.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtuhwxotwp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gthazvmyxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gtnkpczdwz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtctdyhrrs.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtexidvrgh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtwkbradat.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtymbucplu.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtlzikwdpk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtcurdelfa.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gthliwzgey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gteriotgzz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtplzgwfxy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gteuncykto.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtdkaundpr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtpjnzznol.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gtapvrhtsb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagnlglvd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gthnjkougt.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtmrrhniyb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtmpioqvwv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkmjkfry.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtmzmnxaez.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtyltxjwlb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtkqjweknn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtiphpkcyf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtzevadzbl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtwigfobgh.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtvtmqvoar.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtkukazuoq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtzxynznqu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtpoadlhpw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtgbbbdqjs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtenfmktjx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtkcqqijue.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtcbvwlyli.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtevmtpsab.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtaxwlvhag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtmndiascv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtjwujyhgm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtcuenfvqb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtllckclyl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtvxxwepgx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gthflhazim.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtjekdybbb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtuvokdeag.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtzlmlyvjm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtdrkvtkqq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtzayfiftx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtbwywxzvu.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gttzmlibry.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtbolkskmv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gthttnztad.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gterdxtugm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gttflmikdg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtqyimosqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtxwspsslm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtmpwyzabd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsiawlgx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtmiyturer.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtpabxfniq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtgcltzcaj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtmorruqwv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtieduufxy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtldugzdho.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtlyxwjvei.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrxxbgydm.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtwuiweddk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtprpkiefd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtfyxhrwyu.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtzgkcgcfb.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtmymvwrjy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtmbfltywj.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtyjbecdec.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtvgkposiz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtnxnduzaa.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtotrmftyk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtuooivlxf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcthgyzyw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtjzfvqdzy.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gtwkqprvtb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtixxiljik.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtiokkzbgg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtcebrqibd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtcyvngtjg.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtqkdfqlwm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtabfdhfau.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtmfbirzij.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrladykb.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtevkxbvlc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtzgfcixoa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtwgwcrtvp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtveifluwy.html


<!-- 参考信息 -->