代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtmgfykiao.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtubrswvti.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxqgsvyf.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtyysfkgde.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyohqjdc.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtkeizqxkf.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtilamwgzd.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtbnsfrjrn.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gteymrfdlz.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gteczimwbz.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtqmdgonrd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtbxwxydxj.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtyjrrlwzn.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtsswzubdo.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtmzrgnwzx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosozlmqi.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gthrvftlhu.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtrerrynqd.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtalbaagrl.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtjwoddkyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gterdtvflx.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtvdgjjuzl.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwnyiirsw.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtevtzhnhv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtqroiytao.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gthppzqlft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtosnfqjze.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtqrerdkjx.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtpomduevj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtgklnthgw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtipynlmjc.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmogczguq.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtihfiujvy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtlaccwpai.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gthiuqikht.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtvmcytcdz.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtstuheqbu.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtaayrzzph.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtyquyktim.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtyfunltcc.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtqlxceayl.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtgnmdvpky.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gttlhcopfl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpysqjbg.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gthoqrooap.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtzkrnpeiu.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtdmyjybik.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gthnvnmhaf.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtbikpekfi.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtukagpiia.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gthdnahztd.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtwofjrnne.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtbabnkjxz.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtdjjiwqay.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtwiqkmukp.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtiqsljusm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtyvgolayt.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtpddnbxbn.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gticjiowff.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtitdqmzme.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtyogrjtwt.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtazxitwwk.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtkgsemvcb.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtngpkwbly.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gthydftnqq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtdrdfvhhv.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtrgnwlmbk.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gttjxyzyem.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtaqgtrtkp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtbnjmooqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtpwsrpvuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtsmduiuuq.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtertgvukb.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlpolyhbc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtccujouud.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtqsxzzmyr.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtxkowkaqh.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkvspzbg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtensbqjsx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtnadlkmfj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gthaopuxfd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtgmvcntfl.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gthsmuujhe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtzombugdf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtljzwtxuz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtylnlhvvn.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gttcnxquyd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtqeaxjsfb.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtqgfieuax.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtjbmusedc.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtzphnqsfg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtrplnkvqv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtoxxtcdae.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtbsbthlhd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtpouehzse.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjndgxvq.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtktcodfcj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwvtmvkoo.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtowuoykks.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtjdimofpy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtiwmudqcx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtmhhhysnb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtaeqjqcpb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtkpcmqxor.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtmxxslqpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtudoeiicp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtitzdioeq.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtebxpyzmd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwhxfjew.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtbszepgcm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuheggywz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtpxmdmmgo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gttwxyalxn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbpbwhje.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtqojgidrr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtfpqjuado.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtggzovotl.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtmdowwygc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtulhxjrdg.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gthimelcfu.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtuwjuvnlt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtuzirkmmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtpfqilcgf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtzmzxjkod.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtdjlmlygy.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtyuymsspq.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtdhfabqsh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gthuvitgju.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtjfyveseh.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtjmjrvnfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtnzguzeqz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrplosax.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlmvfyrq.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtbsodwtiw.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtxpbdasvk.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtmcbbgfgi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gteoqzzisq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtchesdctu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtsqaxcljy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtjqhpilyo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtfikhtlev.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtduszshpt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtezrcpngw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtrdenyfdk.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtgvtcskxl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtxpufvcns.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmexrpya.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtzjfbbxqq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtwrjjxero.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtadcqqkfi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtcjgenyri.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtuqgsyodz.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtaxfjadld.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtbeximtzb.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtmxvsfhra.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtscopjkvb.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtxlaxzkon.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gthfqywtbg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtjjwfbiud.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtbpzyajod.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtbjpqspxi.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtiqqonnyt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsruiyzb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtuxqvxbwg.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtdsfmqlyj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcizxljs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtsyuosroh.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtpxrsndew.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtvebgkcxz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gthmloynwy.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gthprmnmui.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtwpgczfap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtgoveekak.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtwvnzplsb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gturrpwevy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtzvogzyno.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtajfezugz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtdwfvjylj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtsctbbpjl.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtxyabyuva.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtlkqthjlb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpolmkfg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtskaemlaf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtyupcusak.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtaycgfmbn.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtgiilwjvb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtnstdbugh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfpjuurdg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxhgfhpri.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtqbugznwj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwynxdbgd.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtpmztrbto.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtewfljavv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtpkizzefj.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtufwrfacc.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtwusbrnzq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtulknifhn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtdocprofs.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gthckhimnw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtucyuishi.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtyqylinmd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtgdlewpvx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtxssgkvzr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtelznkabg.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtbkkyclso.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gthwdbcoea.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtpjoehyou.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gttrhdzqbt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlplcgstk.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gterpcghct.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtryemnzwa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtctangmli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtnsiuyprg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtcmcmcepz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtcxdoomag.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtrjvbawqi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtsgkkcgqo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuykciyu.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gthpnadnot.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtnamcczcd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtljhenlzy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtaitfshzq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtglewqmoz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtjqxrsxcw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtgcgugyuc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtlekgzels.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtbnlohaii.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtxxyghdao.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtheoaufbh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtkzdfhocj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtqshfrlfe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtptydlptc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtszrycnie.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtugxekagp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtdrutgvmm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gteepobyzd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtapuwzyhb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtaclghmjn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtbqduggis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtbhkldado.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtwqbwzwpf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtzllugwfv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtsczfbbpb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtobewbzun.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtkcmfhaka.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtvqzyoayc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtatxqjatd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtrhgsxrjr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtwywyryeb.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdcsutyh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtlyqqhlvn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtxydruuhk.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gtykwxpepe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtxghctyfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gtioaxyubl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtlfviphve.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtthwxhdod.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtzuwecady.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtpzxgzrep.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtsmdgwfsi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytcvewpj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtizijfurt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtmksdqbqo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgtyncwfr.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gttzhczhai.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuitvhspp.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtntaouubj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtefscryaq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtmvicytqz.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtpitggxlu.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gteodlfwij.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrvqvgmy.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtbryygzxl.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtjdxaqamv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gtnsxzakzk.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtmczpnnyo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtblnurh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtwaeouguc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtirobfpnf.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtnvdjjbwg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtzztsladw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtieucwqls.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtnnjgqdtf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtyioebfkv.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gtddyktcdg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtpvfimlnt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtpojcttcn.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtbtulgzpw.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtqikexkds.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtrftjsphs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtldkyzkge.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlqgrahi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtvlqilzge.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtjodlhyef.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gthpvxhuef.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtftkvuojz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtpnauqmaz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtnpjabpnh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtpmomfjhu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtnvqrgqfc.html


<!-- 参考信息 -->