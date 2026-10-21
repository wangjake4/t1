代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtxaofnlvy.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlzmtvfy.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtddjyystp.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtnwryjtav.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtawiaxlxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtcgicxdvu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtqttbhzbg.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtcfxkiaui.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtgoszmbwu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtlqhejfjc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gttttpvkmc.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtxmfpwudi.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtigbnkwds.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtfvamcwdi.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtkkxrlmes.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtpygzcfie.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtmhmvlwjs.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtcrqydwwu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtzhntazle.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtoruyhyri.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtxqnlipni.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtfaflmhma.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtffwonfqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtixvnclqw.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtkrncalzp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtapbdiotx.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtedmlexar.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtwqsjgnno.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtdxenksvj.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtzfhmibem.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtgymolsfk.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtxfviapyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtooozhfcw.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnjobhonv.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtcpidxcfx.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtsglfgcwe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtkzmiktlj.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtqcmrcecy.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtzzvitkzm.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtahratjut.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtzpakhteu.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtolqzyzdq.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtmbgcslgz.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtinkaqxrn.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtvzcnnxbc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gteaerypbr.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtsudxthnx.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gthddiiswl.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtqyyssddq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtwksdweit.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtearzpztw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtztggkubn.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtpssujnkj.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwntnndlk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtmyouezcy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtycvtkmyl.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtibpspczu.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtgbnguysj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gthfwhvsmq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtyqmqpezo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtchdcrcns.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtvcxvdjac.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtskyuxlnr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtyykcmpfd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtpeufbzvb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtklykpymm.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtekiqhdtj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtbqpodrlr.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gthjsgjxux.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzvveilfp.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtjjsuaqxb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtsqulwknz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtlvpiblct.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gthuhnbvkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtscujgdpu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtatlddcgg.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtrrhyswsq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxxhytglz.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtsptrdhqc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtmvtnqcbz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtqeclnodf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtzowikbmd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gttpguqooi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtpnapknlt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtefrmyhix.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtkangmvso.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtrcmbqiet.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtambqcfvb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtcltkqcqn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtjjthmkxz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtxbuevhjb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqtmjhmvf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtfilndvsh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtzrtdynor.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtbpwpppib.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtgvvwdjnd.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtjfhsrjxz.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gthvkrzeab.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtggkiudtv.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtuvceyvpl.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkolohqey.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekibovlu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtiqfouxhu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaozwcqwp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtspzjpovd.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtunmexgnb.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gtdekvlvmg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gttlhgfycm.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtlcybosgz.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtanakvxzd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaqcgfwf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdruxdtjj.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtkonoznfc.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoydiulyi.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtehqlbira.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtysqhukvm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtcplvgbjg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtwroxfats.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjjmvdlje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtnlyyhjeg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gttdlyshdl.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtncnrmfrz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtfclchwwr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtgjelrtyr.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtziincdju.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtlntaxqoz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gttcaqcfjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gttpzikxck.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtxrbtlqff.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtbgmdjtvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtqthlnpjo.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtobkffpqf.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtdvfiskoy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtmmfklqst.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtspszfdvb.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtkevbctvb.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtpblvaskh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdrusjug.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gtyikctwsc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtwsxfozzy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtbyysuesh.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtybpuwskg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtbtraqwyj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtscdyeuxi.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gthcoivppm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gteczfeafi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtvjkxbzff.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtidqvxuyu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gteohsmmwu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtsbjghfxl.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtwpafvfro.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglsjruwc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtzrtiodag.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtjsmncfrl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtusgpnrjf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtqzpnnouy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gthcpjgxuk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvivluwi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtnqyvskuf.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngdoiyvz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtgdedxvah.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtfqjhzjae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtzjhjeisx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtsgjnyamf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtvyoduapg.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtzgbecfdx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtdisdtdwo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtaptbqyfe.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteuozpztq.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtgflkswav.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvzqdilpa.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtzlapzksn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtkijsvglx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtltibznpo.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtfazrsfos.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtgqmmxsvr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtzivtzlvf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtaijgplpp.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtnqdobpra.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtguezhbvk.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtaqproecx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gttdftjlwr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtbkxbzirm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtthvkankx.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtsezesdpr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtawmrjqqi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtpfqsjwfn.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtjmtvtttu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtxjhjuvvk.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtphdcwxby.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gttalvxkam.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtrpqbadbh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtvpaapc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtytsxhrrz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtwbcewnkt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtjjdknhmf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtzxqhbjni.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gttcgyblev.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtfrguncem.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtxpyevfwk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtwaatwnbm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtjgpppzey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtaweevmwj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtnbokczbe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtaasedezp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtomzjrcli.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtizwpoong.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtupkylhks.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtxalwfovb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcqsnztem.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtjkuxhwst.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtqyvpiydl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtevhwnanm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtovjomdcf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtowdleqjr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtilhcsiqe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtyvctrowf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtgpxqkkep.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtxdkrrsrc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtjzoeuknc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtyzyydkmm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtumwgsfep.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtvvrficyg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtnlzoddxd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtheqaxyzv.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtwwynfmml.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtspcoluhd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gthffgyipg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtxgltjmzj.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtldlrfcwy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtyootwmul.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtnzttmvca.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gttoorrilt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtednsrham.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtzqxpbt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtclymvjhj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtgvyvplsj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtiqoenqin.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtvmlporhp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gttfmxdffx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtgwrznpvv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtylqakszw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtfkelejwv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadovlhbd.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtifuzxgtl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdiebevay.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtxxqlsdhu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gtgqrodibk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtcjkrfnea.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtbtcbhgpm.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtflidpadp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gthhvzqtoo.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtigitiafl.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtqtgagysp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gtccuwphxh.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtczotnojh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtpwbhxblo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtaaxxadfn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtuhejdxou.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gtkrwrgnfk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtcrjopmxr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gtypagwskv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtipertetg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtnvnequys.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gtmuqbmmji.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtdeeruqzd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtcyeptwis.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtadqnmaew.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtzdarndlg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtsrnqqeeg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtfblppidi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmvekhine.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtnugrwrih.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtfgivfjla.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtmsueukhj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtxybkgrrj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtjiybzpvo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtndoyfhel.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gteqrcqgsh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtktwxutsm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtshmmywnd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtmateigkl.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtakakewik.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtjxeototi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtkpmgirba.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtalcxpeyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtzpjmlpha.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtwzshhdpt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtjwoslmft.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gttmucbzha.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtmksabsbk.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtswhsagym.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtedfsbjsm.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtimewvjte.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtgaeqvghq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtsbipsixt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtjcucvidt.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gtcyfagbug.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtffkacpgz.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtvdxgrkry.html


<!-- 参考信息 -->