代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtevcqdwxu.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtlncmxzyy.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtugcrgtqe.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdalreycu.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtftzfrhys.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtzkhwfouu.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtjgilbugi.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtmsooeaxm.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthujcmscd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtoqxbpkwf.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtdxvnmcfc.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gtqbpapigq.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtuotbxfnq.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gttxkxzjrv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtsocavjpc.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtdtxxnrka.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtytzevkjp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwxffuqs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtkrzazzuh.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gteifttvjy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtefjpxgzv.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gthrhszswn.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtfmikhutx.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gthxnveqmc.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtxqhbdpkz.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtdkzrvkhk.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtcihcdcyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtbvoqbfms.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtsjvvumqg.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtrbpvjvod.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtquebswnd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtcvcposxc.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtalwresxd.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnieljvdu.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtemoopyav.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtumtujsil.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gthmilzstq.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtgyligqvy.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gthubonrgt.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtqemehbkw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtjjebmoda.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtrvmlgwkv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtftybgrlq.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gturqexoiq.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtljmgdfkb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtmwrngbzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtdikktjfy.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtjpcsrlmk.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtvqozmhiu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtvuwamuxy.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtatsyxaof.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtgpuncwmr.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjeccdbo.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtgcvfzdtd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gttkarvdzz.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtwadqupeo.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtbunavpqi.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtiefcnhsh.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtmpgekjcj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtamrypevs.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtscytnpee.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtlllvdkme.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcxvboeki.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtbtajeiit.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtuqquxlxg.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gthawnwgte.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtnsuazpep.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtjrcqubme.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gthbowcwgr.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtwzdsnuoi.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtkhtrmrjg.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gttdgxxuxv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtlcvdpjmo.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtogyxaatn.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtbyxhngqj.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtwsahnmff.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtujgqhran.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gthctqliqt.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtmmryyhjf.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtounkusoh.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtglpxdxfp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtoyjmrnrj.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtnfkwwjrp.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtemumhvws.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtvybmvkel.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtwijdnngp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqubiayc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtidcdgtdo.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtzwswavwl.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtwjbpcpra.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtjfmgwzrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtedsunncu.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtebbewhvj.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtgbnprkij.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtwbalotvd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtdbmnoawj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtlxnrmgzs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtoriccrft.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtqjsrjcbr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtsotiqlvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtlgarsgug.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gturfziyrn.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtcvrsbnyp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtrtpefple.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtbojkkoxc.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtrlzohifv.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgjuljxa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtguxqaiin.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtjmhhlvek.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtingkwxsx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gterofizrs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsqzdnfpp.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtbnjkkzir.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthpjlumbw.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibpdvfub.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtyovenpoe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtnohrxkhv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtgyzrmbdi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtmvdzeyja.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtdyjwxtfd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtesdmiguv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtdewkyazx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtwaputnvq.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gthsxhfrjd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtviggxkir.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtpsiqzivh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtijdizror.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtltaomudu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtulstiqct.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtcpcnaxcd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gttrknvkwk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtefltxcdh.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtcvzbkgzs.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gthxrunsce.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtvrftlxtf.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtrmyllont.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtjwecoxxt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtjqelckts.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gthauferkk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gtwflxfjlq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtlgfogwei.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtkrljewka.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gtfntgjwsv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtvftusfid.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtokegwikb.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtoohdppjs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtbittmdru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtvykhhitd.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtfdjhrozm.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuhizhhk.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtufazpmzc.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtzvdfjtjt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtqolcjxqt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtttnlgncm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtyuucuygn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtunrrivrm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtaeajjlvw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtssepypqs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtdachoxsf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gthuldidpq.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtqbzjzhau.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtlzzkpxdm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtzbauynyt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gttzyigqky.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtrkosboiu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtwefiwbvg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gttiscqndg.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtkfdwxtvc.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtywdquldu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gtdfadtsgd.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtywecnuyu.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtgwwzzxzz.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gthhrwafzh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtopiqjreq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtwlkhiyml.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtuworccjm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtkqdqkfuz.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtgnfqenqc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gthargqfjd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtbjptfwwh.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtxsoqbbhd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtvykeksuu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gttrywjxdq.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtbualfbuk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtahewulam.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtjwemwrss.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmatkhmd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtnkxrapmc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtrdzcdopt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtjqavmixw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gthqxcjfno.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtcorwroxh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtblugflzy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gthqiuxjso.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtrbygqoru.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtwpndghpx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtvpsqcwry.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtawjkfkgg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtexfkpumo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtcjfswxhy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtmtvuvsyt.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgptxtvio.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrjcxipr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtmiwtible.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoenpakaz.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtdhqcrhiw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyjtrytyd.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtbwpviezk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqzprrle.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtzdrclirz.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrghrwlac.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtflqxkidv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtrwpnlgou.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtngakxbhi.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtlgrqqahh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtsasgyxkg.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtekxvbmbb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfpxnfzk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtqoiuastg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtftfgnuac.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtkavnkuwn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtkktmktmo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtyiomszje.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfwlkvvc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjfksajp.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtiybuwvgp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtgtcrrnpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtfrqwyvns.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtmoqpjhoj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtttkxuqrz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtrbrmpbzv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtcbjzrztc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtnvnwuueh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtxobwuewi.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtlqlfnone.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gthndsuaal.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtagcbovfq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtnwymfhuv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtgihkrjlw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtknrhapsx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtbvqszswh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtceoaeoqq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtjxeutxfn.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtnxmyprzg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmwxpduu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtyhiqkava.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtstdmtpbo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtbpuuxasu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtxxbgxaaz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtvwsursqg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtjuzdlvvh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gteobhqjpw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtglirfino.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtkshxysit.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtrmpggdrn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtirmsmwie.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtlvvihgjz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtwslqrptq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtgihuqqan.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gthtardnss.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtmaeklrmg.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfcllvmu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtkstzmcwo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtrgizkdtn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtimabauvj.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtvpviauwe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtroqhxdgi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtgpkhuemd.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtoscyckpg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtlwwjapuv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfcycchy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtzwbujxnp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gteuwkenlh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtwjbzwcye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtflflhivm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtgiubltdx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtghmbrwpj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtaskuvmqb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtkozebqur.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgiwhkgmd.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtnaolyfrb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmceojgoi.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtqidtcxjj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtbhbcbhyp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtavwfmyij.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtblzfpesh.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtbxfowqoj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gtaenjgrvu.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtdtdezghi.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtkzxcpffb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtjkxdoprl.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtzcxaamlf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtzkythjol.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtykfmqcjk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtaiihjvrt.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtuwzyitub.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtcjjvqrou.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gttdgltcub.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gttbneohwb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtwhxrlogx.html


<!-- 参考信息 -->