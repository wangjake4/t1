代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gthrztbytz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtpudmbckl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gthnfyhilw.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gthfncstsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtzoiwfjnd.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtvrsxbvke.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtooztluie.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gttfcrzmnt.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtbnyighyr.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gthllbfopj.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmlbjotl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtjuctnlgb.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtweolkuat.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtdnwvuykp.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gttabiiwgu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gticwbxajf.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtbzvewljl.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtljmjmcam.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtaflelhbd.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtkifsacva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtmcsednha.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtkgcakwmv.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdxqdfmqm.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtdpsgetng.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtbxsqotwx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtdqccajhb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtbjayqpea.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwuqhrqhy.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtxlvcsxee.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtropybuyl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtkatrsnmf.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtcewelyfd.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtsbdmgqpa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtmvlyenio.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtxjxoyrpi.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtnyrdmulq.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtuugchacx.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtepoqckaf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gttsbygsgy.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtbrjmyfkn.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbhdyxpe.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtrriomsdz.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtapwngwfg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtgbdoerhx.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtidzokkkf.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtzjwqkuwb.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtkvvlgapj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtdivrfbdu.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtvvkygvdk.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtwvnxrxcx.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtotwwytmv.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtjqeqalbr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtpprgxnzn.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtxxipiuji.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtmqoemsic.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtfxahckel.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtszaxpnle.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtwwlmaeeh.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtojxuzbmx.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtubrphhfy.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtgdejhtbr.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtvhxgfjzr.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtqbwmcrzo.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtiohvsymv.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtuzkslzpf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtnkzukoev.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtoszagwdv.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gttljkyrel.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlywaynus.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtpnqivwop.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtflaljini.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtkjnlfcgd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtqyohyrgu.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtsfrragvo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtgztjdepg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtjvbomtpc.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtgkxyltmf.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtfvyqgwau.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzxqssaes.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtwwgkvaau.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtppydxrxk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtcxqdrpoq.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtcpueludf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtxaijynju.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzwnxoos.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtnomekhac.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtowabktfx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtpybisyzf.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtpymilhna.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtwmhurmap.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtzhmzuacq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtnaiaehmk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtsedgjixe.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtlfiidgsa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtsviflpxa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuxcvttyi.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtvattvngk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttkqdzoyj.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtqesfofhp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtlnxnobuj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtkpsogbnw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtetkwzjoa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtcfynfsto.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtjhmveeth.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtmcsyboil.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtkjtwlfzv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtuibnqodg.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtiuxdbqwj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtglolejxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtevehxexq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtommukdyp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtrvmlqbgw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtcoqewotx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtqysrgbqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtknfsxebn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrreybvbw.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtqvkeabor.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtwekccbze.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtkwkzornh.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtqtnyufmq.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtdhaykfpw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtswcuigir.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtmkfhllpn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtqwuuquqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtzchkvldt.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtaxrzgwrg.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtcuvjfxix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtdmtjxctf.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtajwpkuib.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtpzookcwu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtfdmnkzec.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gteluwfpwy.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtibhwtejz.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkicnvjvb.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtstiyrvpe.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtpmjcvwau.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtvsxstqiy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtsdrqmqfg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtueivsthj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtipvxncph.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtjopvbucr.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtzktcuvch.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtxxiiuhlh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gttdumzmpz.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtqjvapkdy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtzgjxgyzj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtroywvong.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtppyinmsk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtpltqifgs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtyyksqjeq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtitjuvlmp.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtwkbdheoq.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtidjmfffm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtuwokbbol.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gthcmduaxq.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtivgtaaht.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtgfnxxhdl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzebchpu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntqsneae.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtfllmhetk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtbwhwfzgz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gtgilzmvor.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtbueouwxz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtoiqlevpf.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gthyyifuyd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtjwfkjukq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtvfxajtii.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtuuycbxaj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtfbrrfyft.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtxpafhojp.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gttrylaius.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtcoddkrdt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtpcqfgsvy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseramfps.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtqfgwgepu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtzjguogil.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gtwetyfgul.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtohstqkiw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtdqzyxvip.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtujausihs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtoemxgodb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtnuktqeqi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtbstflvbc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gticaiupzv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtswqozdya.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtspvsiaqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gtsitdmqpn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtqlxfizwi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuenahnir.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gthrsljpso.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvdubuwvu.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtfuopuyoj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcygjzjn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtramgozzr.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqdpplfdx.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtzgssgodb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaweouqi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gturkfbmrz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtpnghpjcx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtrdyyvwcd.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtkizqtneo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtxsfzinnp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtwvxbhbso.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtcnyunllx.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtatckzatr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtawoadhwq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtqmxtgglj.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gthufvoofe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtxnjnrghz.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gthzhzlphn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiysdaofx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtupucmhyt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtpbpxsvzf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gthjverbqy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtphjfotoz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtodcshnfk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtthidjwdi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtjmlbtgkg.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtkeodxafg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtskirzzux.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfhxnathn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtrcpmxskn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtzstjsoyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtixylpugl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkysgexy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtgtiztdly.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfajcnlws.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtcrphrtsj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtrshfbzve.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtyywyxwvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtgsahmrrx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtuggpzclj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtjjrrycjg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gteviojqhx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtyddxdblg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtcahtgmeq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtycmceuhu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtsvuahkxy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtgjmiiyqf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaobzbso.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtspuiftpc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtqyqbzfbo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtbbixmeiq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtgvvmenuk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtbbbojmrx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtdbjztzbt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfjeialo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtmqzdcsnb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtibziyjuf.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtxeuohajh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfinpcgv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtkfkdpokf.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtilmehmyy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluumjohi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtbatznutm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtgknierid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtkoaotkao.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtckrctsut.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtddrxsyvi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtqanskisi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gttbdoavcj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtekgekdbu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtjieodffg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwxzysmrz.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gthycwhmcv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtowrbxngh.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtzocrfshx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtznnjqlvw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtsmxlfwrj.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtwxijfajf.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gthxdinjpd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtghxpoexg.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtuxxswyyc.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtgzktspjw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtyirugbbw.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtllmfexij.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtihxdvsuy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtnezaqlmd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gtgcjylpkq.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtmxjmeqsj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtsguqbbob.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtawadbyur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgsszady.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtehpuibok.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gthljndnfo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtcsipgrik.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtjqjasbfq.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtkxdorlnk.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtqyywpcjm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtxrtydrlp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtlmbnmmqb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtgyzaqxfy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpukbkcdu.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtpenqiels.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtnohpijcd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtcdliwywv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtlwciozrp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtbazkfkeo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gttqtvhctw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtpmmzwune.html


<!-- 参考信息 -->