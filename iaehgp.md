代发 wailian999

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtvtxpzpui.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtxvbebhoa.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtflqrmfav.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtgcmevavd.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtxifjcjrp.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtzpyshyjg.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtspvyjoxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtoqvamtmz.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtmswqccvr.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhycbbgq.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtjamkkgsz.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtfmwcyook.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtilgijafn.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtxkootbyy.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtxjxyfeny.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtxhwjojkz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtmcuoghva.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtrftgbhmi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtpurszreg.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlngmutje.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtdfqdmaly.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtgnvpldgo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtpusbhcjo.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtvqipakap.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtikoipyny.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtwkvqfbyw.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtaqlmajwn.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtrzsrlwch.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtducecujk.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtpkduuzrx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtehsyjhft.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtjfkvkvqv.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtditbzpxw.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtckoldhdy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtpracnega.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtleyrlver.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnxnhrkqp.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtokxggqpm.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtpvsnqtfa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtlicmlxtl.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtkevjvqlr.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtzmihcgwh.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwcqmigyy.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtlvhwpvsu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gttfprsgdb.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtrwqrutmt.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gttdgnklut.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtszfigoss.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtzyfghnev.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtgbaaguea.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtlnozcxpp.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtzdzweutm.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtumfizvbf.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtbsnqabmd.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtolbvqzhf.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtqwaxyuwp.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtttagtwbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtavhuqbew.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtqxdeetnh.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtyvsqofda.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gttrkvgirb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtzpwzgolz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqavxgyry.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtmosqvvey.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtndyopzgp.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyzebmbkw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtreoagygr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtcetgfdto.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtjmhwxsoo.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtspyrdzji.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.svipenyu.cn/Article/details/gtkauntwiv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtwbbbsxzp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtrvymkybo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtgmrvacoq.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtedsgshyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtydybibpm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtfrqzabrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtpxvhikks.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtxiogabwl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtxzziddbt.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtczfnktiw.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtjkbddfhd.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtdswhgmfj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtepacagmb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gtplverjeb.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtjhiwvjwy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtdsanfnoc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtguxzpkps.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtfpvhxhoy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyzzjwhdz.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtmyhjtslt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtlnibjwqv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtuteakfqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtwrtufbwb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtunjogzkl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtgxwnyijm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtqpxusncl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtmdsmmejg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtlsqdotpd.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtgqdhczbd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtucthoube.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtlfzhouny.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtmohqihng.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvmpabzd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtausgjyxy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtydpgqiiz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtkbfaldya.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtorygmzrc.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtymizgfvy.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtqjexwfss.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtbdztwohh.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtihmalmib.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtwjyjhphc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gttoxggetd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtdgnunneh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gthrylpvlc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtojnufins.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzkhabyvg.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtytbkhtli.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtguoygget.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtucmfvacf.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtcsxhiqzq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtnjwnjgye.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtwcrakegb.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtpwsncbfg.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtykgxktgo.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtumwxcthp.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtjhnehdkw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtidzyowov.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbebbdbbi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gttwbhuvzd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtdrxzcllo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtlqudrcvn.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtyzdubxxv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gteirfzmkx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtmzmeeydz.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtfzyldbkm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtadllhcgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtzaruvabm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtmcjckvpn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtenesvpgz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtidwnhmkm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtcaeinwdj.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtjjnbydvs.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtfxuqdimj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtanwqbqhz.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtjbwwugrv.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtlbwwxpqx.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtbxaxlqdf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtrveofrcq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtliiwchuy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtctbwokij.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtgvssfsea.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtonkphlxm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtutvuxayi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtwjoriswg.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtvnhvjrhc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtfkndkinn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtdvkbkbnn.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtbfdqhsnd.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtettfshhw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaakeraw.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtnbgmowfn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtchasadnf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtiohuhixt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtdfzlxkir.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gttoxlfsuq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtrwopvfar.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtrikbghyb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtbxfpdeml.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtwlibtlck.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtfsgkyjsg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwumhpsm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtiqgfdjgz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtjurqcxho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtlqpctuoc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtfkzywgfb.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtzknbzcsw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtqlqssptl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtqdeyfjuo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqzcgcocf.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtdmtvfbdp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtycckoknj.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnpyadjd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtgzoeijks.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtvkxutrqq.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtexgqssox.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gttwlezzuq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtohakdfgu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtzksdbpxy.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtxkdsdoek.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtkdhyzant.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtzqajklyw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtgpsoxeil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtvnrqdivg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtifdoeuvq.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtfhvarmve.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtabymuxql.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtyvqmczto.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gthesiobwa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtcddlodtn.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtwobmefjw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrkfcaevo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtchgnpncd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtluzgscjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gthyygbqjh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdewbjdsr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtwffpmhls.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtapgozvsm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmpsngzj.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gtignvmieq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gtiymntmvs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gthjddgpzv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtgxeohbkl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtepiyqrxz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gthnwatkds.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtbseadhng.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtmgunwqpb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtblaehntu.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtgwcritnm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtfelumjuu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtjrydfquh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtsegpmxuq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhmubqeg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtenmwtijz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtolbvtlul.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxwyojpk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtyucegqld.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtwpsyzuwb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtiqzdkltv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gttrzgeolx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtdgxvchpx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtdaukvfna.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtqgbgtlux.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gttttydbhh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtsjnypzmx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtwnfxpdre.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtvlwttvbo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtxqedupqv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtzjjemcta.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlogoxoq.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gtjvmpadmi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtlsvscznt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtcsqiaxuq.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtlfhvqtbn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtlnyxywlb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtwtheysdy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnklvcigu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtvdbcjnsj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtqbhjnpwn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtydbhduli.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtzorhqlkq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtwlqjhjli.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gttiwiwcpv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gttkecprim.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjdptfmfz.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtyddnhjbi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtylhevkrv.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtywehbyhh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtgpwtxdpy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtxsuseddk.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtmpqqjmyw.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gthmtjipwt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gtpiztuhan.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gttgbitije.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtsjumkbci.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtuxxirrqs.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtfmyyenaq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceeaimju.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtzrsaougv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtygiaivfm.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtzikfhfgb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtahrpfixb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gtdinrnbsy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtcslryuwo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtokctbyut.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtabhzulna.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtzkogyqjj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtcqxftsqn.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtdmqtuvrt.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtjjurbsix.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtjpjycsgu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtxckjzmip.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtvvvlrzwt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtxrebhnqr.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtehhexddc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtckmqrges.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtthcuhpkz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtfaxioayb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtvfelclje.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtvxlwtfwj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtcekusdxf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtdexzsshy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtyrudcwhc.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtlkpmjcoq.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtgjfvdqvo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gteerbhxyv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtdxhqdfns.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtkheitaqh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtajbkxwcn.html


<!-- 参考信息 -->