代发 wailian999

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gthfokscxy.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtlakboqdz.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtzwozgefa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtfygitqrn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtmqqzgurc.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtsrhmkcmq.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtgnsqqmai.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtnsgjbmij.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtnksvhvno.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtmcwqjdci.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gttiskfxrw.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gturekbnvk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtrxynsvcr.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtmgigymks.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtusxytbpd.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtwqwhxdnx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtnpvzdggv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtuvhrfzlm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtbimnqjjm.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gtfiifdcwt.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwrwktlt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtimschnai.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtyudeelmm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gttycqxunc.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfcmbxdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtxmkosivk.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtkdwvldlo.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtrrugyryg.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtueauzszw.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtoeffxarh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtovffqgaz.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtjdhfihpu.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtgvhssmcd.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtnnrcbvdp.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsdlnrxo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gthrofrcxb.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtppfbblgd.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtbdaxagum.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtcmhfwpvb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtnfwufbls.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtmkwnmthb.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtotoknsjf.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthixyuchi.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtqfjnmpuh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtolygpips.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtjuvihpih.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgncvmbzn.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtvaxuseip.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtzwmcecdq.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtdhwwewlg.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtqbxkxbce.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttvimdll.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaommzdd.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtnhtmhuyd.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtwhwueyrq.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtqafygnay.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gthnxsdlab.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtgscghnnb.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtkiqhfqnk.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtnzugkdoa.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gthuhswxsz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtjckdckkj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctmooedu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxlcofgm.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtkbibqfnv.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtpmbhhsov.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gttpghekip.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtwxipwcvz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtxqkjbkrc.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gteagfihei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtaiiilvqf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtvhzdygkt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtunmzljcj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gthtdxizab.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtunesskvv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtlefhsigq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtcojznkyz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtfjhbxzdl.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtmcrfkjnf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtnfbrgzkz.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtbrimzdaq.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtlymoapgi.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtmhldtgzs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtacdofguc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtawxcvrqy.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtrohgrwbn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtmmmqmohy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtivtfenyp.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtbduzjmyi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsrbxaiza.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtmpckixkh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtfjnbbyzw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqyktnbol.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtehprguhs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtailkbjpa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtdzbnqfsp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtvvzcxswh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtvcjfsrzq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtumkqxigq.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtpfvwijge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtmynfzuqw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtcmgqfthg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtugmjbbjl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtlchtutyh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtvojplnbm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtltqfajyr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtiaxqhhhu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtkwimvkxx.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzgwsybi.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtlrbcuzuh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtzvowobat.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtpffikaml.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtebmtrhof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtdwjtncbx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhtuxbja.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtjsaoilyd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcywfwrgj.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtargsfwtl.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gttrqubfhz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxxbfmtq.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtqlblasqz.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxkpbecpr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtoqkrttal.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gttnsgpnpa.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajwouddd.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtwvifaarc.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtogdvxeeg.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtidbwktyi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtcflpqxod.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpxohslpo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtjukssaio.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxeuiwjb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtuvekopdd.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtcvltdghp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtzbgnxoei.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gthckhhcvk.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtgbfriujm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzjyimji.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtuecqqoqc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtbyxnqoyw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtttskqarb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtfmtrmbjx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtmzhhezrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtwworxpyh.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtfngidunv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtbibvontl.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtsmknuzjh.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtxcpxogmb.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtgochvvmo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gtzfnghltf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtjxwtkeis.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtyuukedzt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtbjmzhpnk.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtafpyltft.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtzwyesztm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtahoaukkn.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtldprerqz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gteawwbmnj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtofndkijl.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtzowfpjkm.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtocrzuoyg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtdngnjgwy.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gthlqoywhn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtdoqwqnxb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtqlkbacey.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtevxsjcvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtgvuynkvz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gthzpiknpu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtvkbqzbxw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtialwrnlb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtpwbcsqbl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtjysnvhwl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtltxczyew.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtstfmvzxl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtkzpdvybx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtvnwyzvex.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtxukomohu.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtoydjzeuh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthevcuaqx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtrgbypeud.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtibocqyun.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtiyqvljkt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtysuzdzgv.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtpynabkzb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwewlalxs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtcrhumopk.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtycsnyrcl.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtspcnkihc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtkkfozkqa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gtvrxcpoxt.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gthruxdlee.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtnxlbvcds.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtbufqsang.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtzyvgsdik.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtlpgigoli.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtlpzbbdll.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtbbqeyhbb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gtowdwrajb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtgmsbgeps.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtuzdbauql.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtygjnibrb.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkdpaipt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gttftknuuu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtgwbkauqv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gtizavkvxq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtmpbwvjui.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtfnvmwsgj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaldxqde.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtnzvjfxsb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtsbmmllco.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtzndjcypt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtjaookvea.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtdvqujpqx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gteyfyofkn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlqibfes.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtvttidxbn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtdjrkegku.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtosfcxmdt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtojzdiavk.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtnogdctmg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtcdivogmh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtlmllalcx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtjzhaenwq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtrediojxx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtpclpqxwd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjzjzpdg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtwduffcwo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtlpqwckdu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtiuaflwqo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtyctcfnkf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gttwlndjjb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gteenuxhwv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvccthxb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtcklmdsrm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gteptyczka.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtglnfjdly.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtxjuamjyh.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtwydfvpzi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtwscaqlxg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtaypcvhxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtedhpueua.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtzilglsyh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gteoayxvpn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtxmcqyyaq.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtwzswjqwn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtbvzzjacy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gthhnzleol.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtwdzzvnds.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtztdudsnd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrhvyruq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gthinrrcme.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtfapxnrlt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtdjwbdlut.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtsnflkuxt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtnnsvxzkh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkbmesnax.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtdwarluxf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlwoweusf.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtwvjnnfmf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwrxcvds.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtphennwta.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtirzjnuel.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtvrfskqaz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtwzcppniy.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtbxhffqme.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtwpacfpjb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlepyvkkk.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtsbhromem.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtjoderkqg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtglebmgue.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtlroxkvyj.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtxipnmyzg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjyrjdzn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtupnyegzl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtcrafysni.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtijnrakyj.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtiwspdaih.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtxkefmkxb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyamwhon.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gthnfqhaps.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtbuvmaibw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gthafapzsp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtkjdwcdld.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtvthhajth.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtijoaubmt.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtpkxeuijx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtmxikdlyx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gthwkicywe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtuuvugtfk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtfsntlsys.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtdrwzprzu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtdqyhnegr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtvbpoldkm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtmfdqwdpf.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtzgzzaesr.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtztbcllfj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtdpyuepmo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gterdsoepy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtcydjogcq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtbxotmkcl.html


<!-- 参考信息 -->