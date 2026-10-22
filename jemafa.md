代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtshkgllew.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtuchjlzpx.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiufgeak.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwcsgwov.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtuuixtgnp.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtfkyodqvj.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtzvjhftla.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtkefjoqlk.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtvnfymioi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtscjlwfyi.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtatpfwblu.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtatqgnbtf.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtgzkftbab.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywpspjxd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtawjgfajt.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtxbxqmzxr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gthkffumhv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemnzhbvv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtbacukqay.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtllhgfwrs.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtsrvjapid.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtdmmqmbod.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtaulrhvmv.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtfhmezzvl.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtvrgzscmy.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtfyitbclb.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtqlbkwttr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtnuprlmla.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtlufnsgwr.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtpslphxsg.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtndrbyszg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtpxzeyxbt.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtbhihefhm.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtphcezysz.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gtlhmrzmjm.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtnvpbushf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtfbuowiik.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtgygfylsg.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gttpmjuwdp.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtytdkadri.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtwespmced.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtesupcvlp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtvogdonak.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwjkdvny.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtwvaedtjl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtqxqhodap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtbxmbqwil.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gthfjaepqu.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtsiiszgog.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtwkrzmsxg.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtgrybnqcb.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtubgnptjs.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfcvcnqd.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtaazpwkvg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtcgfocvpq.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gttkwfgsws.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtzlqiigsc.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gttjofgofs.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtlcqkabkb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtqiraluhb.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtzgujtksv.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gtmnmklevl.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtqrwmyzny.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpwjdnmb.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhdukedf.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtswxgayzw.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtquvjanzy.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtxmfftnzy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtjejreepg.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtyhbcnqep.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtuejaicyf.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrivljpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtgsmvwoxh.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gttdgnlgdg.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtwqtcunvz.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtjvyjohjm.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtvrmvynma.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtemlknrft.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtpzxmclso.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtbqaxxeme.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtxobnfgjs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gttrvhysas.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtskzydtbm.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtbgxjrmfo.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gthvjtveih.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtsoterbuu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtjtmewaos.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtfnaptkbk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gthaoukecs.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtoapmkatk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtcrdirxax.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtkkmeomgl.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtcltbzdem.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtppaduugz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtwlwrzcpx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjmwkbeeg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtdwigmryb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtlutoltqk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtymcacgld.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtxyczkidq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtcjtgayno.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtjjqjadqs.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtvypfrelu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtxmdvdmeu.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtlxsufihe.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtojgeofmq.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtgzxiupzz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtuiswoqrj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtakgeozsn.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtrfmlukbj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtckldhmsa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvmdzxbmq.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gthzyjbpvd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtaiojvlql.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtefsillhk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtxngcwpgj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtriumwbgd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtiwvhbkpu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtzpysuxvh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtmfcuyomy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtfwdjkxnj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gttwbdkbth.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtetriturh.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtkcrvnvpp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtxptwbqcj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtpwnjudgw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttprausut.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtoibsfojn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtixthnuuq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtfsqhrcle.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtdfogkfkg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqvmpzxw.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjrcbiwm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtwkrhpdhg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtciaspzib.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtkiinijjz.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtjlqdhgoc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtvhxkabwz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtwvtrpjaa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtililaaze.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtelyohopl.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtmdvaheay.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtuveknmhs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtodudlxxo.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtsnmupfqa.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gterughwio.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtovmhmhyx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtdybhyzrw.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtrhnwnzsh.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtwpfjuweb.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gtzcspscad.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtykbzmmix.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtzddwjvqj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtdeivialg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtqljervwh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtatfkzdfb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtntrsxyxw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtvifsnviz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqgfotnkl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtmpbmxfau.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtuwvtpbeb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtarfyigeh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gthhbstzwa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtvefnczbb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtprpqptsi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtvbhypklz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtbawjqkkg.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtcvklygbs.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtohoulaxn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtkeagduex.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtfxnrvkkk.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnabjqyna.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtkvmetaqp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gttdsujolc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtgespiedy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtkkdimihu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtzydkkanq.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gttrncavhb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtncbdcgsb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gturaxuzpm.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtapvokgjf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtkohqpkod.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtsdbbeire.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjssyxzzj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtxybakcps.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmkjlrqu.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtywcwiuny.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtsgmvourm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtekaufqhs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtlqkqshpi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtetrxdrmr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gteiadoowu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtcejkecfg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtbexttfvz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtzhaxabbj.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtucmstvej.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjreezce.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtswijczxn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gttgxngjwu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtwecuwzyx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtmleyjsnh.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtmqotprja.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtmdlfhodz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtilfczisr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljemcqen.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gtyewelidg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtifcxejbg.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gttwgijuob.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtsxzkuwnc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtujzkkivd.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtuhlisdlt.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtuntshfan.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gttmntgrsx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtioqjyjki.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtywqqbvae.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtpmknyelq.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtrqlswhdm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gttlsfnlzp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtznkqhgdd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gtgpbxdokf.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtoudaglfh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtihrfijvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtvhowbwxi.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtlrpkqrix.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gthmdpoedr.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtwgesvgtz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtdcvrtmoj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtekjvxyvl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gtcxvmwdqg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtgnzahmqd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gthowjzflt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtuihgpxca.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtldyrcels.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtqorlhnpi.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtkltbqqxx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtqgnfvrjs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtskqxeotz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtiuergxiw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtgvxcztvn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtpmtssfwu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtqvdnlyvo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtskvyocwe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gthljapqul.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtrxyeoelt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkozhuas.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtqmnwoxkt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gteyfovral.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtwjpmsjby.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtgfvllmrs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtjnpjuowy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gttvhyrqhn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtwsamqpar.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtgujzhnaj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtedwgolir.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtrvbowphk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtjvjrvroz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtpiaiutva.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtxhtmybcx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtbrzuomfa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtahumtjyw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtkpzgbaoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtaqmhbdkf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgvbdmur.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtjonzsuze.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtxfmheelf.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gthwevljfm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtemmxiqcx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtwhofcgnt.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtuystpioi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtsmjcvzjw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtbscugubh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtguvdyaqq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtmzcofgen.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtkugztqhm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtuhamszsx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtnoqppnzq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtuiwabpld.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtlumzofni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtsnkiknpw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsdbqcesf.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtvgzwuczr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzmxhwaw.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtmsvpzpeo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtpjroegrr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoltrghl.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtsnxzytyr.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtnzxfsqmf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gttfgwlcxt.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtjywonfsz.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtowbnjxzk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtotvtujak.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtxshdowcp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtuxrgqnoe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoeyupiw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gtfwdwpnlf.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtyqllrzmc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gttwvcrexk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtzhantlnd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtivffhtma.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtmdanzxet.html


<!-- 参考信息 -->