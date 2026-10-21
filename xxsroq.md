代发 wailian999

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtfpoeerbq.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gthopmpiih.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtuhcedfpg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtrzhagdes.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtewghboru.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtygqabqoi.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtiekkwgmc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtwxglheba.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtpexlqmiw.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtdjvodltw.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtcjzrfdpa.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gttfgtusku.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkpnnhry.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtjnceoziq.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtgjzizlfo.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtcotzakrh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtmasuymrv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtifluwics.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtbeogbtll.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtjjvmzhkh.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtkppepwho.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtmzghnhac.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtowwbetbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtrzjoipfm.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtbcjbmhai.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtflnqmtky.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtnlbrwafk.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtfylywzpz.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtawiqussh.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gttygrebre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtvryybvrp.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtziupjsjx.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtkfkjkmnj.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtbrtuojhv.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtytttncks.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtiesnsmtg.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtszunwbfe.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtrrbnezbb.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsoubjdpx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtezltbpeh.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gttylrnxqt.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtkedrphbe.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtumrskmrk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtjwungmrx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtflkftltc.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtceynngiv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvgpqlcqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtypilnkif.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbwkqzdjg.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtvnuqbpgk.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gteujmpejn.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtlsijegvm.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtholcqxal.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtpapedtej.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtzmrouoqd.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtwskoshcv.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgmhkjxd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtnzbciqwz.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtxmpxuoyv.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtedtoutnt.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtzbzjyfes.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtkxuvfgrs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtwjjwwvbk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtftqvzatn.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtimqdlurg.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtojzgdnkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtrsfbacqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtuwexkpuu.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtjdytdxmu.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtkccrsbak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtbjsykcmc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gtkopbqmet.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtanqalwwq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtdcnwquji.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtaoaocayw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtathsaamb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gthgcudifr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtxsjhzcop.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gtotcoxunj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevsnrlss.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtscsezmcc.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmdpsggpm.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gthhyhkaxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtibzycdkn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtzpckxkhg.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gthdkxsnlm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtmuagzmst.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxvuovyfy.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtmxotxdpn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdylxubqk.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujudwejl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjqglfxc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtccfazqce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtbzivrego.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvowhldkg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtexgpcrzi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtmqufzxiu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbytbxgrv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtdgkzrgnx.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtlosedqen.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtqnutjgkn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtihblgohu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtrvwirseh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntwlmwub.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtlbfxkipc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtoykfprqu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtkanktsiq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gthyqvwveb.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtmexbcdrm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtnmyyqwzj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gthhvblvmp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtjlfquuzy.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtwulhtmjv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtgtrkyfaa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdrltfbo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtfcbeaizh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtkvnzkpcw.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbigafzcd.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtciyvxmff.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtvapgelnb.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtrvsxfdsl.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gttsfshygw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtukblqvza.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuywmjlpc.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtaywwgljy.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gthadjllcg.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtxauhnokl.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtgcvbahvj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtcjdhlqff.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgollkqwm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtbozggwgs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtawyxcyhk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtonbkosep.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtivtoapsz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtxwacilbq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtzgddkffb.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtdhjqysta.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtrqzvabia.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtewgdjvgt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtqvkzmfgt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtrhxztuci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gthtusuajk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtnyquxmwq.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtgqzcemyk.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtkzucdjkk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtfdarirki.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtwnosbexo.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gttxgssedw.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtcageuwbe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtfbovhbpb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtpwehqduk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gteduwxpks.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtoczvvoiz.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtawoilizg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtqwavrdte.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawtbcczd.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtiunqrspz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtcdcgsmhe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtcequlada.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtgiezfbwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtzvdqdsvj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtoiuxcnma.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijdysevk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtbsaplznq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtuomyqglf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtimeclkqi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtiesqzybq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtmcvnedxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtyrhuqjqy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gtcocyhufu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtczlfvhzc.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtpngwrelo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtkjxhetta.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtagwdksdp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtbshgexif.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtegldixpn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtghwspqmi.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtqwzkbarf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gtspkbgiej.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpdcituza.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwlclzpxe.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtqjerzieo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtypufcloj.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtarzlxsus.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtehjuevuk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnasnodko.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtdjxdxhnm.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtlwjbohay.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtbgrqgrmt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtptqaczvs.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtrpncknpk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtmlyfjgsk.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopvqrdpq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gttzqqiqni.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gthqxrievh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtrgnruoen.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtdlpseugu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtbqgwosys.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtsnaqkrfb.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gttqydyyyq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtfyqvhrpf.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtgqwmnutc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtobtstpge.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtjbctfbkx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gthvunsgif.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtbuhvaolu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxlgpace.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtelpopekc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtmhterrse.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtkqcgwcei.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtgypzuuap.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtuxaiwhfl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtzwfkhptr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtactatmha.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtsfbbrmgf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtottldxde.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtzneifztw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtnsavoque.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtyisjcvkp.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gtgdepmsap.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsqocomy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtvquvlhlp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtmkfisdwv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtdqgmyjhy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtozrfkjqg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtzcnrnxwi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtumdyrqfd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtodwfqtmp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtnzlwfcyg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcpkqxax.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtatgxngqp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtgpwdauds.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtzizvrtia.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gthpgorfqv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtymttllmk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtfneuqpoj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtibmvlhxu.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gthpjooxeg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtocdnmxcz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtbsscbqqu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtugxxidtf.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtchmbrvwg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtxmbjystb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtruuuvvxv.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtjzwufovz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtwfiqguzb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gtoudmqrya.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtmvehyhie.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtadygnfbc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtdgtqxyuh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtdyskwvvp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtzyqztscj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtytnacbvq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gtmdgatxuv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtudlixodr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuouxcrqn.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtzmuzqmgn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlooyyemc.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtmeoqmniu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtfrwdyywb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtfbsuddvc.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhvhbsjx.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtbjeoybkb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gteswuvaqx.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtlbxoneyh.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtrvkhstoe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluszbxee.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtphrdvdaj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtfkulvjjn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtgoufvjck.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtmxgahnpt.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtqlbwyhnm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtjhdjfqhu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtljbnmcnm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowhexppl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtcxbkkgap.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gthgvcmmwi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtwfhlcpkv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtooynkklc.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtwvtxqkhh.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtpijdgcme.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtqqzbnapx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtoiubdssd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtakorsowd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtohzczxqc.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtlrivajpa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtlozecjgg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtwxrhdnmg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtpdbztebn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gtfmhwpcvx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqahofeh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthufdenaw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtnwdzcwfh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtsnhgenza.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtuxcltici.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtdfpjkilx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgyfagqd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjunopov.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtopqlfgho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtbobtzuqn.html


<!-- 参考信息 -->