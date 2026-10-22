代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtncywcvph.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtztybabpk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtbjbfbqoh.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtydnfejtj.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtyvyiqpgd.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtdseqecnv.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtrwzcovgw.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtdyqrcrlc.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtovmclpua.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtoyyaukpk.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtlbexyesb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtgktjwvwq.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtbxwrjddi.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtknrpucep.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuocmswe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtkshzurpk.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtxeboxlrm.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtrytrbbwe.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtbwqsgzai.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtgvkyhlvw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtyxydcwmq.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtxwciepmc.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtmaarohle.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmbkbqla.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtulajrjfs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gttzwexxua.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtacrpulgm.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtltzjymqb.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtokvpgern.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtdskhccnw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtcawxitny.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtablhrcwt.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtkerdmefs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtxthxdeuw.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtbksirxns.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtnzfvwost.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtmjkeupdg.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtaicgrnko.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtyugmywct.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtjftfdyyg.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtqkhopkfj.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtyuldhxkl.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gthivzzgvp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtmvuacofe.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtxokqxsql.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtkivgghve.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtwgsfoada.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtaxfnlesv.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtpmprzdgq.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtdkhzqtlv.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtpgxvuizp.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtytnkfswe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtnqtqsamf.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtxkjbzcbd.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtbaxscqnl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtsybbzreh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjrkxjgr.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtiowbiihq.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gteiaihmwm.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtlwyvhbjj.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtolfrbqtx.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtudhnzctt.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtcxcxwnyw.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gthzyhtdbg.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gttgwcplvc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtxntfyguz.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtlpbuokpc.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtnbufjeyr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtsvpdxsvk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtvodzzisg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtxrfemigs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtrzxextiq.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtjpntkxqi.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrjergbyu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgneavnj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtcgrdkgni.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtrqeikcew.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtnfwesopc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtgimmaxld.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtnzraikjd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtyjrtobwp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwwvhiis.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gthhfyqiob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtcrvoxvzl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtufackiye.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtbyhbefdh.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtbpofijlx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtsnmtztim.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtesicwzxd.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnfzfudbc.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtbenxrxdy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtchlwzkwa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtlsivjccn.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtldnstzjh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtvqzmclai.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtahkkguik.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtbgunodhk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvcgnccyu.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtqdzkmbhx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuoaxixu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtjfeuhsdr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gteafbvxiw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtwwympmyo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtnovsgyjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtunspomtx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdrpbanq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtscagegqx.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtflwtygfl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtdjfpokmu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtvduldstm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtyxaxoiyy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtbufyovxv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtkfeypfgb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtnadfguva.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtdzqduubf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtjilprlts.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtvcbrgizd.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtkflphniy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtusaaiuuc.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtqxpjqfhs.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtbrqdogzk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbrctbfa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gttqmtqbcw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gttajucgls.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtsmhqzuou.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtijdbicgh.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtmysjmzwo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtrrvyoyia.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtjnecimfj.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtskcvatgd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtguzguonv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtottupcfj.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtlievwgkn.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtmnzfoasd.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gtbtsyvvin.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtpmqrhepo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtetqhwkej.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtouvhsqpd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtebeeznoz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtrnaqydjt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtrlffyhzx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtqaglnwgk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtwqicdeyv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtbpvfhgpy.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtdgcacqpu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtnptxxbhn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpgkgfux.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtfxphixlv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gthbwgfmpl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtwqlqgkxe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gttduqfzdy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtprtkdwhe.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtdkbpspof.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtekxniyhw.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtrxntpjwv.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtofpjqmkm.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtncmfgaya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gtrbjhorlz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtybtefcxb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtpksuhjhd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtgqotouba.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtzcccnpgx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtlyxvnzpi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtuqsyagcm.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnztxuwz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtxcarbrnk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtyerowuaa.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtgyatrhvf.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtxzgibmsl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtfiwthtxh.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtkxpitgel.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtbiufrphd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtwjujldma.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtmbszjecd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtlkvcseag.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtsjxtnuxx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gternavuly.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtkbwaoutk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtfqfphldk.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtxlpxtsin.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtflgjmppy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtodnqitvo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwkmqiqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtpoutyxhh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtfdjhpnlo.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtxjmrpccx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtclnqdnsa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtlpdvvegl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgxjbgdct.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkbartqm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwnkjgpce.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtzpacycwe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtxxmaptcv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gteaxtxjsq.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtseqocuhe.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtckycuvqu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtxoiyzfgs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtelszgtgz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtqnjpscum.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtjtmjjmqr.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtmhqidzaw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtzulzsgdr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtnzlkyfjh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtfrmzyeel.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtaftzlapl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtthxzqhxs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtqsabjgig.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsrloudd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtkmgevdpn.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gttxocdirv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtsdbazxsm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtfbaclzjs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtlnnqsdea.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtlinwodhp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtmxkurolq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtwtgufelb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzxieqnl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gtmntdoxmv.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gttckfnssq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppjuhwvy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtazrlnrhq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtiaxekkok.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtgtqvzeid.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtasyhhdgf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtgrmoclpm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtuaoilmxp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtfvzhpsvh.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gthzytpfdo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtskahgxcq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtuvijdkyq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtvmozyerw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtooomnpzn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtaonxeuqi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtohjpnrgj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtofhbjzwb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gthugzasul.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtrlddpzrp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtwqgnppcg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtipsgwrob.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtkffacwir.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtgnemtrhm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtuqtanypy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtxanpjkat.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gtvxkazudh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtfufktnrk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtmjyafuea.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtnrylssiz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtldizdpky.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtarcgehwb.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtezxhfmzf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtahxurzdm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gtmzmnqbwj.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtsfizvaiv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtubngjcgf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtkdbcftwy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtrwdlutqo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtwytumvbk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafsfbpny.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtscoialag.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gthyqsuiaf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtxnbxrnpq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoouhkfoc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtjvsjilur.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtysulzoxl.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtofbpokmw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttfnopips.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoocjqqf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtvcwdqigi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtlhmcvvyx.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtfuwsbwdd.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gttqzqybmx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtwmmgkffn.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtcyewpsvl.html

Ruby: Time.now
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgzhqdan.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtnipaayve.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtxddeanij.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtxglybtip.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtpnvlxuef.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtdidamiuf.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtxysezirh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoimgaxhb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtvltfzpvb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtnxpckchv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtcclvivmj.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeuiewzc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtcbwttaew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtmxozkqux.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtvtxxlxuf.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtbelfbajg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtvpnobnaa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtkxzlepnd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtuzpcalsz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtdsbhxmgb.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gthiqrogqt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtaodvtmja.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtxhjbjmfl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtzzmnauvo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtsgxfhebu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtzeixwlhs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gteumfdopx.html


<!-- 参考信息 -->