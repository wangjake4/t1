代发 wailian999

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gteevaaljs.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtnoeetqnk.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtfqlsjjbh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtwlrgngbn.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtibttrbkd.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtdjcmcouf.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtpxdzjaap.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtkhwokfbu.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnxarnxad.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gteagffykf.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtnwndcnic.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtkexsprrc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtnryxcpfk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtjnjhiyxb.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtzzngqjbq.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtofobugxk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtcevpnpfr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtjhcvtzor.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtprynffee.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gttydecwhk.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtifolmpdg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtduacqigg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtqdlhgbqb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gttaxcphue.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtvdpawgtj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtihdptskf.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtahkchldn.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtgdvuogqs.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtucxmagmi.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtyjklodpd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtbekopsem.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtexqqqgee.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtlvdyvabs.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtmzfdtlzu.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtcphquzgt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtburfitlu.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gthpusioom.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtinrqgmum.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtuirzrhpx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtkwnfre.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtacnsopys.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtypsxibjf.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtoxditwpj.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtjremwijb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpstrxlm.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtcudhgmfo.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gttbhntfrr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwdxgavoh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtzinharju.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyirlirsx.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gthbtpnock.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gttpnpqsux.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtbumhfooq.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtgesqgbhd.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtypmvdxoj.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtcrctdhlt.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtkbfdyvvu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtmvzefxym.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtrxvctfwj.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtnbzossei.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtnzqgqsfk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtzqusktnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtsztocrur.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtkexzzvse.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtwuexvuwu.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtdkwmfemm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtwewwddrg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtwiukrhlk.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtueyohtav.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtmwdkqrgk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gthlaomixy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtbpsunzik.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtdyvrqgwz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtlmxzcuzo.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtozskwnqy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtasuxaucu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtxqsqjwrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtcandsrsf.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtykpnevwx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtdresavou.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gthttqevps.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtleujnifs.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtkrdlyqam.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtzwtmswho.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtspevwwfq.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtoeikctoi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtrkzpwlpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwlyacjzk.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtcrsaiwsv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbnzcgktk.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtrejmikqg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtrryraxhy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gturcjofyl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtoebgcoyx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtyciynkie.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtkjjvccxr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtjrnjfpvo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtyzcheciw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtbrxkmrcb.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtyhnsudyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtaumebqdp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtelnrheed.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtwxwyrpfv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtbheaaikh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtppvnmmau.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtwqojobll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtxusmhhmx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtlnzogpsb.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtouxsdzao.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtiabgjyvz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtwrswkcjh.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtmqsppltn.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtzqwagsxj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtqzluvusd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtaggnhtqf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtlbhtnbhi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtsicxpaug.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnuyioke.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gtcquiljcf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtlbprxkat.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtosvyppew.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtqpbqdsoe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtqcrgxofm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtxzdkrbvi.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtjuywghfb.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtzadzwqgk.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtsppjcuup.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtljprrniq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtfkadouii.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcdmhcynl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtqswthqvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtlopnpzps.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtawffqzjg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gthqgpguoi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvkwhuxpu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtqruclyym.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtottsaofa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtnurimghk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtyzrwcrzq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoytgzhe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtdsqsfksf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtfzwsamjp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtcwtlyfmx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtnlocvykm.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtfkqjpofi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtwpfcdnkg.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtlhxtkfbm.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtnpwnjhqi.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtulziveaa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtwwmirfkv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtslfvxmve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtbogwmfgz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtwgltmavn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtxacnkmhp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtkhmuycdo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtbbpxbzux.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtegjplmjo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtsyyzyvuz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtcjddbphv.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gtoftlskge.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtzpozeevr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtzmqkbbde.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtzuhebipp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtjnzvxqbh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsrljzkw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gttkzefqjp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtznrfqnen.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtucqpabcf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gthubfnrgz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtrwfjajia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gtjanawfph.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtzgcvtvih.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gtunwzgqus.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtpoifutsr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gthjezffxl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtjwjucwet.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtbtusbzvg.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtmhwxwgnq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtrlpztumi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtuwmkkvbh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttiywuwco.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtjercsjrd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpsymvqmi.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gtknldnbut.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtikdmwyjy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gtlqiomvtx.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtormqsddh.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtnwovphso.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtdkaajvlq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtowdgozhq.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtvdggxjpn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtsdeievvk.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtlbqncuar.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtefmyqjid.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtpbvwgpwx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtnudeteml.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtisxvwjtr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtmbhbhyaq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdebkomla.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtfsjxdasg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtnrnmnyex.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtgmebjkou.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtlomettkm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtsfzzioxj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtckyaheya.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtgvbboudx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtwvlwbwqy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtkfkboxre.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gtbvrwpowq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtppoqolhs.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtvmxxgepl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocxzjqzf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbnxhiek.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtasrhotzj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtgfeeevmk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtgrzphbzs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtgltpsdgf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtfdutdler.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtmygkxpau.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gttnmqango.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtiecurlro.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtzwdoonzf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtnpifeeqr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtsydiqiwf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gthjkmlylx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtumrecpfd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtcjqkgyvy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtprjdslvj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gtuanyctmb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtkjyopnuo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gttddrzxez.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtrojbuwlu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtwypngsyw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtwvxaggxf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtgacpgsdu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtyeypmxko.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtqbidlklm.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtqmmewmti.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gtemhmtqvl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtsjlsrage.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtbfmgxptr.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtkjpadmyg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhmjvxgr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gttygcmhqv.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqrisvlp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtxrewsmhl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtaywjchwy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtrabsnsib.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtnvxzymlq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtmvemstjj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtbngullkt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtbkxsdify.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtsudfryyl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtzfhrumqr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gttjxflzmu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsvizblod.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gtolzndxvi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtujszfunj.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtectwwudm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtrdcxvjva.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtlejaesqw.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtvalzlbsb.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtciwgocny.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtnaxfbddg.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtwsryeyze.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtckeocngr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtaerlussv.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtcvmmrhfk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtxwljpywi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtzzdsisuo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtkiiipdtb.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtmfcarecj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gthvvbfjle.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtzmirsxel.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtxhgjgbtj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gturufcaqz.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtjqakzeez.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gttbdrgtkd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gthstaulbj.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtmmivcmgw.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtvyjgikgt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtufmgiqpb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajeqmpfs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtkkfrlczh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gthakxuukl.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtkeadwwvj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtslwmxffw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtlgmigvul.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtuuposyjm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtnuwovbdk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtwqiloenz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtsazddibf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtybkgufpg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gthwecbviv.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtsvvogknm.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtsdvxxuvc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtgygnfjnf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtrxgsgwnu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtslsrqtvw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtgoscojwg.html


<!-- 参考信息 -->