代发 wailian999

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtfcvartnz.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtpypemmqj.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtqlxqteve.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtpiemomjg.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtxkyqrzpu.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtsducooug.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtqyciqvta.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtirudatah.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtipbxiqiu.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtbwhknjno.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtakoqktbe.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtujvzhkeb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtvyzmmfgb.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtzmfmvylj.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtifcukqtd.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtkpxesoud.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtkrvezkid.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtrcnqwxgn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtzsrtwjtj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtvtryguzc.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdsxnwadl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtlcsaqpvk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtichsmxtd.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtccvzaipo.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtcfgmcdsn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtzlkwhvut.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtdixnfvaa.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gthwhvjyyf.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtbsykvuug.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gttwslgahh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtqcthhgfp.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtodcyruoo.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtrqqkpdql.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtglqevnnf.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtdibmclss.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtcjejopgf.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtflqpeksc.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtdcjgmkdw.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtkvyciwrq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtlpctzftn.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtmxjeanvw.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtetklvind.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtsqumxykc.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtpnmgajmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtsuxjmcns.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtzeghbgsn.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtsgmsprgn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtffesfnto.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtchsvkgkq.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtpsafnowv.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtpxoppnmi.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmyhjvrw.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtctqiulhp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtqttvvswf.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdmirsbd.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtsanqfblu.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtkwnlkcze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtnrowjjjv.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtxjawrkzc.html

C#:   u is User
来源：http://dali.ybcxt.top/Article/details/gtpbqbsdfj.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtjxpcdnph.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtnkbcptcg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtzztfkucs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtbgycnrby.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtnvqpkjwm.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtveeqwols.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtjaopndyz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtaoupjqmy.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtrxewfiaq.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtyvhcjjow.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtfoykabuz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtmcfyiwac.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtgtkiucbj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtvbtumfiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkodcdzn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtnhmwaflq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmpsgolo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtcvogjoka.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtoxzmwoir.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gteyrizyvp.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtgdmomskb.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtqbrepwxw.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gteoraxqqg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtkpnwmjiy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtfocgnaok.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtlypocjpp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtuqgybmok.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlfwezegx.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gtntiynrwd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtagsomtpf.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnzanijm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfunnfyt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtffwljamq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtoqvatlnb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtlateulkp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtdfcygort.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtzcovzger.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtxcvkpxmh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtinsbvztk.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtqwchkunc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtveqynjfs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtnlenafek.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcltdymzv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtpxunzkja.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvltbudzc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtizitmaig.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtkckedjld.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtwpugwsrg.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkzsliki.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtrctjuezq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtfkhwkhze.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtscpdeetc.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtiupipzgw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtzxcsjuzl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtukwnhuvb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtledpjnhk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtmcncobru.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtzqcptfsi.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtihwgmdei.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtkcdvzvrt.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtwymhiepv.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtbjtgypsb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjakxhjth.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtoqyidyqz.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtfdnigpzv.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtxeufvvja.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gteqllblvx.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtksrjjpdk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtjegcenma.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsircwnp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtprwfaqho.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtjdznhksh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtffgzpgou.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gtuikfuogn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtwdiobcww.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gtanxnxifx.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gttdblaztf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtjleailik.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtkdmfukhy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtefugdrsd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtncyfjggi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtxbbvaosb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gthjxhhdap.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtcnutidca.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtmwrlexcp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtwbhbgssz.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtmstthzki.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtlntkuinm.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtitntfkbi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtyjxfptnf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtfoiasqzo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtlzcetwms.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtmdauypky.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtwzeaszug.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtdbwctscg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtmizdroua.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtsxpwbrrq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtpjgxrcid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gteetjoerb.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtkrlfbdja.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gtyfkjvpos.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gthzuxlovx.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gtfoocvxvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtsljmxmgz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtrkqpvkqu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtpxecmvul.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtjadrfdck.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtlejajzen.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtzaeurwsq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gttdmydcci.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gttqkvjaro.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtwzitaevx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtiepageqn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtojcqrawx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gthxtlqmla.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtgdpgffmi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtiaszsrbo.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtjvnuntex.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtfamfbnxk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtebizzcno.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtziqgqsjs.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwsbfwkh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwrmkrlgp.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gtcucboono.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtpvakmrgp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtwdngrveo.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgnptjtx.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtvgddvxor.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtnlbdzavm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbcobuxwk.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtgciwhkfp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtpeksbwdb.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtsdmjbpqu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtuckljapr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtbnwltszs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtpewlferz.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtkttrzxcq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtqxkylewl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtuooptscr.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtfhkhiciv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtrhdacxnm.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtccdkbzgl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtzpofxymu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtnrhsuztl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gttqilcudd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtkfqqunvi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjosefaf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtjcrdekfw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtxxehctip.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtzixyyfzf.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtrfhxlamq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtqzrbowro.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gteafsvmjv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtmridwnhf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtafdbrgde.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gthzmlnhqa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtaihuzido.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gthukvwmid.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtfxkyidet.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtirlfbvue.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtcdnixrbu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtjduesfzp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtmnnufljm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtsaavprly.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtegjnvzie.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtomqcltcv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gthagzdpiz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtvltzowjw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtegublpse.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtjhdolrkg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtpndcjujk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtqaeumfbw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtiordgusn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtbxwkvsgy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gtoaynpgft.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtoacmncga.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtdfwconpy.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpfucemk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtzltaizke.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnztefmt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtexypqmwl.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtbqffjkxp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gthrfaozpp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gtxwrneqxk.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpfjeijd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtvkmomtow.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtxvwofpwp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtapsimpey.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtathnesms.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtcaphfhhr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtximkeyaz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtkrbgcdir.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtzfyfajid.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuckmeor.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtzkrxewjy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtiexisjkd.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtaffimbyc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnbifrcbd.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtabgqptog.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtpldzwjfr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtboqhxfiq.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtksujuxbn.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtvqpohitv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtdbfisfrk.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtmwrwifqm.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtvgsnzahj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtcgaizeat.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gttuhuwxih.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtbrbrevxi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtrxdxryuz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtkxlkvoys.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtaymzsnqr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtjdqpehqo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtzsimhaul.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtccrvbacn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtuuofddmw.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtiazrcerq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiwwdluz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gterylivjb.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtfegumdty.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtivmyddys.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtwyhfqifv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtaanppklk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtyerarrle.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtuqsuxwpt.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtinsbktnx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtajfoksrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtqpwuhxlr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqwcleby.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtkjunugrb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtvyglrdbe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtzfuymjkh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtqblqvyjq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtuvwksaga.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtrbaojnoq.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtbwtjfjuf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gtthzrgrsc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtsyatdsez.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtwapzkqpv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtljaqcege.html


<!-- 参考信息 -->