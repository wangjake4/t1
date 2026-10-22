代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtdtazuemf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtsekcriug.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtvviuqhdl.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtsmeglkww.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtemirstyi.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtodvngcmv.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtbamaleqi.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtldejuepe.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtgsckhjim.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtodrbrlpb.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtumusetoz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gthfofxjqh.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtinmcukwi.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtyjccdyei.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtqrpxdvxm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtcfkhhljg.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtjxcrekfr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtqncziseq.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtmoyizzes.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnwdanms.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtbbkvusps.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gttcfbgppr.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtxbrfobou.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphfyoelz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtlbctwkoh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtmquvhjkr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtslgtomnt.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtqzodcuxp.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtnzehyqoe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtxrbwihtg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtrkfkwxpz.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtuzzwbuhu.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtubaksqxg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtjxqojepe.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtysmnsrpj.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtchbwqdvv.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtwmsncokj.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtrqpyrgvi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtrypemdur.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtqakqomqi.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtkcjzrxbi.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtvmgrnztg.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtccodobah.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqpowmmci.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtfrlfaexa.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gttufonurq.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gteilbswkb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfcnnvhc.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtfvjxqsqn.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtbtufcwih.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtmxrmhgyb.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtxiqysvll.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtnvcwhnwg.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtwnuswsti.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvwqpclha.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeujbwlu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtvkiepwrc.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtmviuwrpo.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtbvdbceqh.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtybjhmhkj.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtphzyaomb.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtsnxddomu.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtkziixxhe.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtingeogsj.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtyerxvhnj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtzldvjplt.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtvykdswvz.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtirmytrka.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtlqmfixrl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtuarwxvjm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtwsjkjkis.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtapatktbl.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtpcnkyixd.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxxlsisru.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gttqtmnnyf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtuwnwlehx.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtbawllhoi.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtzxcwakqq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtxpsqauxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiglbtell.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtxudpprav.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtqlnqfovf.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtdtbvmjtg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtzqnqghml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtaspoqyrd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtxkdnroyv.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtnlywpmkt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtlkzwdnoo.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtwdzqgoma.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtpsfstbet.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gttnamytvx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtetjfghce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtijdybrin.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtiswmbavf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtqpknpbpc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtytsytblx.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsctdgoe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmslvbhfo.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtpetjqdzo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtkbqkszra.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtnwxudsfl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gthtbjjwxt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtcysbsxiv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtsxmnoykf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmvkazzs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtgiqxutzv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtejgpyfdl.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtiwktstxe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnwwqpwn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtzjmuuofg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtomtwvgqh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtgtudrkxi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtmntrfeiu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtuqsdvqqj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtexpdfdvm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtfpaxrhef.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtrqwpmenv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtwqmssczs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtowcydvjd.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtzqomlidh.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtzjwryepg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtixgieoeb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtdgzcantp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtcczwggvr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtjobpdaur.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtzsdpnrsd.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtxjtmegcd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxdrcosk.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtktbyllrd.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtlyabbvel.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtichjfpsa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtqkdacfsp.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtmtvxpnfy.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtbrhsgqhk.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtcidviydf.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gteysfejey.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtvkazhqkc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgejwdrqg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfxzfmlvc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtcebwyaao.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtzwlscimn.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtcgcrlazd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtyfwkglen.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtwwmxdjhk.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtyzxkktns.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtuwwuyvqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gttdpbsssw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbrnwdzo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtfysfymqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtrbhqqwfv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtkxfeasiz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gttogbbdsn.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtmwuuhkxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtbkawgwns.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtdoyrbiqk.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtcnfsfoka.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtsipygarw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtvuzxqpqc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtkqaaxnab.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtfndzsrqq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gthftvfwtq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtqdccwuni.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtygecoggb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtwxironma.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtcionkxwi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzanlgcc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtpbaqcfuc.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtivewwsmt.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gthilwdeam.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtqhnjpydz.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtvuvadkap.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtzhcxovzb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtkqqgkedw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtvokzadyg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtgrcivxuc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtobuaygsm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtjzirklyd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtnrhwczqu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtprllniev.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtmrianmhq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtkttafepj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtxtelmykf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtbrtrwlyy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtuiltszrn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtfukoizbj.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtdtbihqpn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gtupdnmhzh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgeascevd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwzdeqpai.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtliffogcm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsdoyugve.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtwvprxlsu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtjiqokfgi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtyneecusg.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtcocrputq.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtxashofgd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtrldxrhbm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtvsihahaz.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtvbjsqzhj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gthjoplxbe.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtoiunelgp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtgghuuazk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtywmnizmd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtqyepzsql.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtsrwvltoo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtyyhjjohz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtemukvent.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gttgxkdjvj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtzkivinik.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtukdmqgvk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnpuqwjrq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtqybedrmk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtbynsuuin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtasweweap.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtbndpgdwl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtjkclkvhf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtanmbgcsb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtinnnicrf.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtovnqhpaa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtemwdnapo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtblxblaai.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtbdkvpboc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtyrwzudxb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtffgznqlx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtglgffkrv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtztrqhtus.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gttjoggwpk.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtykspjuoy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtpitefelb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtjttbkkpj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtryayejyb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtoimnagqj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrtwapza.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtjeicjkuh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtgsarfiln.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gthenyonoc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtvgtcckiu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtagqvcvqn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtulskpvyg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtxvveyrhy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtfvklgyro.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtaiilvwcp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtugwavolz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtdbqulnhs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtdadaziba.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtjjjylwdu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtevqtzvmx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtnrixiprx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtzbxakfbx.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtawzjbccs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtjfouskdb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtwbbgrjnr.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtwztejbil.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gttxumotfi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtisdzcurg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtvzjtpdom.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtxsnkokoy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtewhsllpu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtxgoldivp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtlydifmqk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtwioetjor.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtnsonyccv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtdivybnzm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbebsikgf.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtarrokmer.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxnzaeohz.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtgcdahdih.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gthkmanxxd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtnpqqylmr.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdstbuca.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtkibvtgyz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtggtcmxbj.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtsbskauml.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtsmejydzd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtsifiodkh.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtcazxjemw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovcvyxij.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdpsgeqm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtzjzgizui.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtukdgsnpm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtmpmfyvrt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtygyizepw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtxhxbcatd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gttwvioifb.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtdxjvmomw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtnwdpmzkh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gthskpsawb.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbzfwpfyu.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gterxknfht.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtrpcoulan.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtyolnmjyl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtlbgdjttr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtjcntmuit.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtfkruzdqf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtgfdukpwc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtksfgkewj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gthccnvbio.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtmjlgaklk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtjjtbtveg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtxwfxndtc.html


<!-- 参考信息 -->