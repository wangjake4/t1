代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtwphsarpq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtialjumgi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtzmvlgkiv.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtaxhjxfhl.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtuexnnzmj.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtimbstefn.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gthdqtyvjn.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtwllndhgr.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtqgcejhhf.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtpnyqicqz.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtdyyfevgm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtrimlfacj.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtsoctfvgi.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtlphiwspz.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtmxguuffl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtklstwtmv.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtsxiysauy.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtwpqpejlt.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtxmqxcpeg.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcvtwawj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gttktdomuo.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtylcjeqfu.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtlldaxzth.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtmbmkdpjk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtevnamefd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtgwfoglex.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtdaplhueh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtyztwnodh.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtlmqvdsdd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gttryaxcnd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtfpurwneo.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtlishhudu.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtegjvyuwn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtkievjkqz.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtslicgony.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtcdejcdyv.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtnugecqgc.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtjjuqvjtv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gteocvcdxr.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtvefeggxm.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeilvlrd.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtqranzkvz.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtesetqzpa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtteireiwz.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlfghpclc.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvnaspehx.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtawjhvwik.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtyfhttkqe.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtaaqlxhqe.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtepxlyram.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtixobokiz.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtzfbejifs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzuemfpgi.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnmnmncql.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyadopcbh.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtxyqhgthi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtovwxwkji.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtqyouhfxt.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtzooyxxmp.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtdyvzrzge.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtnhowiwdo.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtzqpghnhq.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsptlleal.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtrsjjwdtq.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtxkaqqjph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtypxqctdl.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtciuujqnz.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtnadsjscf.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtgkuyygck.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gtnhbbmhmm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtgyxfwbrc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gthuqzghcn.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtwrytjwcu.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtgxanizdr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtgdtysczp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtnrvjulan.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gtrntuudtd.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtpfzttmsq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtiytkgnay.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtyqjaagnu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtxvlexcbg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtyhzudnrs.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtidecdyol.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtzvsagpwr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtuzfanwho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtqgkvvabc.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtnpxddght.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtvniurqsg.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtljvtqqfh.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtiehlpbnl.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtqapoozuf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtrudzyqcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtjpgvuxpz.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtiosxpyqk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtmfnwqvlc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwkaoedlr.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtpecrrnzo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmoexdxio.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtjhpgehqq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtrythhynf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtuxllmozn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtmvhwcgte.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtujkglgfj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtmdxflzjl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gttaxpsrqu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrzgztpv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtyujtxkrq.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeqmsylp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtfchnobka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlxppgkfx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gthrfqsyva.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtgzlmeaxu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtwshajxcp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavmeugej.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtcsvtqphv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtbxvpipuu.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzjvreyd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gtdztrruil.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtzqmlaftr.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gthyizlxlm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gttzpukamq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtuppcpdjd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtwplzjnsy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtezkkzlkf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtexjrszhd.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmfbrejl.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtxrdoktwu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtdmissoem.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtwuzlhtzp.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtowtbhvbg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtztbxjilu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtrhwfuzfe.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtotqcuhwa.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtbqstewga.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtrsaynisr.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtoqowpqde.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtjbegxiay.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtfoiujacq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtkmsgmkag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtvqxnmjvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtclcyjstq.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtbdljbnpb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtycufsllu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtthytspgp.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtqqpvtawi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtidhggqjc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtvvlvkkar.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbulkezod.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gtfwqaviig.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtaftibcud.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gtrycldzhe.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtwywdoufw.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gthyzfugsx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtayuwnxap.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtopsfrpop.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtehmlchbn.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtjfdwbqzo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtjkamkeqp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyouloll.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtdoxuvgsz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtuyzgoxeu.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtyrgsgbui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gtfawfodhy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtxceiafce.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gthrdoiwab.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvndxgskc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtsdutlydx.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtdnwkivsh.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gthspexzbu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtkcxytsar.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gthgwxxbmb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtumqbpdai.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtqouvbrcn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtlntwelvv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gthaecputs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtalmixwlg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasnxqfga.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtabmuktkx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtvdkxknqp.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtorchemtf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtvukvvwtj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gtxfogflbl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtqqfxccwf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtimpetttz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gttamlgugu.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtyjnvzfaj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtzlrpiqyd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gttvetsvnf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsmhyvsfg.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtxcpruxdf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxubgpcsr.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtdehdfzmp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtsiheqtom.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyquldfg.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtvlpxbyxi.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkdrrinjh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtjdlftpcg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtovbuupmg.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtiujaludb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtcfahsbho.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gthpqzxlvv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtgyowkiaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtssvgeajm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtqenbekmp.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtdopjwfya.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtjrmysyiy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtqsvrnrsk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtvbhojthu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtdmkyoeuh.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtfvaufxtz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtcllvuheq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtcqtchdtl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtfnwmbluj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtdhmhyhxd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtgrbyjzmz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtudqwcsmg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtdxplkifm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtymeodtfm.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtgtgmpdgd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtvewzdwri.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtswnwldxw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtxkstlgty.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxslximc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtrjtoctnt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtexpuntln.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtxakjopqu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtkruvzqwp.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtpostufgw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtjohuqmzp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunasjohh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtglzvzcet.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtstqxtzag.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxhiiexz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtrgjjhtaj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtrbufgxkz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvowfsbzp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtndodsscw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtgcnwoooj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtrfkzcldx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtywzwuipz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtvhvajoyf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtfedcelck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtymptbyag.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtywtjaqkc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtygdkgsrd.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtmmjrkiur.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtnssuvdur.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnndvmei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gttphsabkm.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtfatluuyk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtrtdvezgu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtcowvniwy.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtwzqdmrrk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtuvbmutdu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtjbyhgoog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbsagefu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtcdlcquvj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtvndojoli.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtvsrdkuix.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsosuniz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtegtihyiu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtgqsdceih.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtzlaxxens.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthnrwwqpk.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtwhqapais.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthsxwwfun.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtdsjzofrx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtahwqmysd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtifxosjyo.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtbumpwxoe.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtuyqfzrbj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gttaeqhnnm.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtjvkanclb.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtspcwpkhf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gthbqusepb.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtmbjhuhbe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gthdvtfryi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtllxovwnl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtmhnjzicy.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtembsvjrl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtaktfhcog.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtyjsxqefk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtvkyuoshm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtmdsjhmzf.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtzfeckqhw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtwmkeflxj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtfbbddgjy.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbjawfxnk.html

TS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtdttjxuif.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtbdxgvbys.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtbekivoql.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gttnmpcuex.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtywdygjuk.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtcxvhwrit.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtswhvacns.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtjyecnueh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtfphspzgw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtroreqxmo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtwklbcmsy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gtbsrqfvth.html


<!-- 参考信息 -->