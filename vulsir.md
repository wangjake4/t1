代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtkslsnysu.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtudeektli.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtsrsxxnwj.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtgojdnabc.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtdiyuondg.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdtvqyyro.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gturmpncqk.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtrdpdkxea.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gthffrvfdb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtcwhargfn.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtitykaqpp.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtrhooiblw.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtpphmforg.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtvcfstuke.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtlykuiclb.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtigxmowfu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaxznwrep.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtdrqjpndg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtahtgolyy.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtzwqtbchv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtdvdwfcrk.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtiwmttpks.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtkzpzmjlx.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtaifzsaqn.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtbcptokyb.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtukwjqrtx.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtvjfqtmba.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtsulzeoaa.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtntpkpqcs.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gttluoqgbk.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtscqmhyel.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtpsdrcwkk.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtghjhalvl.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtupbvkhvl.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtwyldkmck.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtnhdwayrd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtcazihonv.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtypucwzsk.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtolwxoxqi.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtqtvnwgfd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gtmkoyscar.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtmismwuow.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gttkmmocgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gttmoquvvn.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtsvrjuyjw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtmznqjzzy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtwojnhweb.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtkjhqhvru.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtigoorfzj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtqdrkykzr.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtglpajczh.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtusrjiwfm.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gthyqzevgn.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtvjznzdxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtrptialwd.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtfidhkifn.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtbnzaifuc.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gteztmzhog.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtfxryqxko.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtszdzddrb.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtdogddmhv.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcgovbvjc.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtzyoyimah.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtltputchg.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtelzhvssw.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtobwdjnuh.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtvwltgfud.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtlwoiifvg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtkuwvxbil.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gttncjitvz.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcroqutmc.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlmknyjrs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtkuvglctt.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtzzuffsjc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtkttnzrbn.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjikvmbw.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtwxceptpe.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtagtknxpf.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtnnzneiqh.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjrnzxmmm.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtyakyutyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtdtgwkmap.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtnysteezn.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtlyssgqjx.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtqhtlmozz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtecospjkn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtidksnihw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gttwwjtwre.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtetigexyn.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbmhugnky.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtrunbfcqa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtjvkvwerf.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtksltkujv.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtkylcqqtl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtqlgxypxm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtczsxwvvn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gttnpalwyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnuydbue.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtxhknnixf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gttmrpwzmu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtxngfovoy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gterfvifbh.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtgkyskfbh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtezyntubh.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtairdqooi.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtdyyslqgq.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtcpphhgxu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtcgfgxalm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtdhuwdebu.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtlufdimsw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtvsddkbjm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvrymjgea.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtmcaujzbt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwgemtzyd.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtbocudxbi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtdjfgndez.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtnrphuevo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtdhixxbou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtiiqfwvne.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtvdeihqvq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtddwgzcpv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtrouyygph.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtnbpubhee.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtgehudnce.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtnlmmkupr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtwzaaufbk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtqundhzqy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtolstfnbs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjhyzxqdw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtdkmarcvm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtborbkxcv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtwpcnabfg.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtkjmeukyg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gttckmgrep.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtgkffpkao.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtuasmohwp.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtwqttnvra.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtbvhlpvds.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtfrwapvef.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtdakmworc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtmomzqhrr.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtjpperaom.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtcrsxffxx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtgddwsywp.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtukfhopbg.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtjcyharnu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtfxgxcrcy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxxwfuyc.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtxtqvdsoa.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtczrmmsxg.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymnnwwov.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtbdrfpubb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtwtsbvqcb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gttteygnyu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtuwxtgzxd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtggthjgtg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtmlvhofrl.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gthpilddwd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gtbgbwezpu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtggqaicqk.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtiaksdnsq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtgkdloiim.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtaywokcrm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtmimvywow.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtxyncseko.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtczcjhicv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtkgjovtjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtzbqoniiu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtemvroqeh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtejgpkpjq.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtplcumabu.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbokvhjs.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtgaolqlbz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtdigorqdo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtatulzvxb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gthxyctbzp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtjyiemyso.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtnxhvfcwf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtdjqjbpcg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtzgricnfl.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtqufpbkwt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtrffnvery.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjrzaauu.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gteecgalsp.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtexokzvru.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtmuretuhw.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gttvurwrnw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtjpeiqqsq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtdisldnnn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtvcgmkegv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtibpvsmkx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtbpngpqyk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtlzztplij.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtosdajqzz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtworqaqmi.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtuvrplozl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtxwxqdlnz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gtnwkewvod.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtelpoutxl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtqmzpwdwk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtwioakaer.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtvfznikcv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtnskegrcc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtbolsgehw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfgxupjxb.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtkdceidcs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkczjgjto.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gthhyuloyg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtysiwzpgj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcuccook.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtslqjuetj.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtcnypakts.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtdoiriwtd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtyfadbkbl.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtwsntklfz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtqkbyescb.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtcxbdaykf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtxxpnhbgx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtjogwmcwa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtdmgqwzab.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtgjoknlab.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvlptvia.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzgqrutwy.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtmyoerbzc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtjklmtjbo.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtsdhbidst.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtnwdcucjy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtekfvrplg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtshjjepqk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtjdmtkraa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtkvrtgidv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtbkndhrzl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtlhizbelj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtacfuifnw.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjlkwbji.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtcfcnkgli.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtssszpbng.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtqqxatqtl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtmhsldwvq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtxgmyfaht.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtxexptvqj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwopmylf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtrexruiav.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gtmqljjafs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtnscxfpau.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjvojlcx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtssdhmuni.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtyhdclptm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtfonecyje.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtvegslcbm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtskkbduuu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtmlzmdmri.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtnwrdusnc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtmshvobkj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtmfjcstze.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtktlbefzv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtokidcvrq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtvekyieqw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtyeyngnni.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtiahczrhm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtxnrbnvyg.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtazveykja.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gttdykrdge.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtooaqsujy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtazkphtds.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtyoeqnvcm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtpkptyysj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtjlogisll.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gtyhwvetqj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtsudggngj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtbgluqtdw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtrmzikpwf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtzymourxb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gttiwjffgm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnolykftl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtjyyvheoj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtvlhpcana.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gttyehadfh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtbnafpjrz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteddkepwy.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtqnnwvbjs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsghukacc.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtoxtzvtmt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtikolseui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtnbgxreop.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtpusyjtid.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtrjhttpkx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gtgroqkmws.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhqwqizo.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtissljwiv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtgvuapdvv.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtjfofxauf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtyatdgtrc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gthfegdlhu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gtavqlpjxg.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtbdipqgiy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdhsbcuu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtxpdgvjpb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gterhbbdwl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gttdgxcntk.html


<!-- 参考信息 -->