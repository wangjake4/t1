代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtlzkexaqz.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtnsvnwmlx.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtcqcdrvjh.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtnozhjkuk.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtthnhcjmd.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtidhytlsb.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtafbajchr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtqyqpkmao.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtsoudeler.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtgcvvnysc.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gturipqmnu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtgrgykkoe.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtwhfhrctu.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtnpijjwlz.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtdiofrlbh.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtlxzjauin.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtzlzfyfox.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtayxcydtq.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtfjoruuze.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtipvjcaqc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtnxyqbblc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtglkvamqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtlkijevgm.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtskwgwjjy.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtzsnouyup.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtfsmwvodk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtixkkfzvw.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtpktyypsq.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtivunxtpu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtlwqmwsfx.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtiglqsugh.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtrpopxxlq.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtulrgsvms.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtccanijki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gttbecqxit.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtdcztpsnr.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtwafsilmd.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtbwdztfdt.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtrpxlmvau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwlailthj.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtzdpltbrh.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gttaofapyq.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtiemlhqwd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtyzltuwtv.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtlwqzmude.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gttfgfzxqm.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtpdxgoztn.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtdrdgqrkc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtfdkyrgnk.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtrvrscsfp.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtxjemwxxl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtpkrmmpjz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtssjhzmoi.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtujfulxex.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtudcoqgqu.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtaymuzqim.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtbfvrgmmh.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtgdfmimac.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtzilgsmtt.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjtgksx.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtqunvbwfk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtvhiyuqjg.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtmhcqjjiw.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtqktqzvfn.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhmzuxpp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtzfndbuwx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtzltwopaa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtwrvadois.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyurcdvhf.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtleesijih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtynbphwnc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtlvfyvrzo.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtghlttija.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtshlclupr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtzbeayajm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtludgwfgb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtfsvpeqta.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gttzjiqdha.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gttzaozrit.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtcvvbmbae.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gteizkyslg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtihcwhoxz.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtjdnlejxy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtwuunumaf.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtpnxualcs.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsqjsxed.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gthroyagbt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtrwiuucda.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtjwyzsswe.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevyzklrp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtlztxjoic.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyawwbhyj.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtgykzvqlr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdlyjkxln.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtcixetkhj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtfyrefwch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtdfambyss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtjoiojxqq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgavcyete.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtcvxodrsn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtutijitgx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gthvebwwfk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtenblszvo.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gthxvxxvas.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtqavwxhur.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlefzgwad.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtmntqvcvj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntopptkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqlxxbxvx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtpqxyuefy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvevtpzb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtfjhpjjuc.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtlnfxhfpr.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtwqgsgaqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtftokhwyz.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtokyashum.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtredzeads.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjevniykj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtbbrtkyzk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtilnkfzeq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gttdtbwuga.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtdehlemni.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtpsgycidz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtnvjuesem.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtinaiwqxh.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtfazdilec.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtsiscftza.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrttxdkpw.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtzdguxwra.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtoohcwekl.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtzkvuxpbo.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtgptgewuj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gteqwaiilk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gthpvluphz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtqunbuocx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtkrhbqzjq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtmldlwdai.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtctxzetwd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtkgppkbmv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtcreqaery.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtdvymslwm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtkasxnabk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtoulyprdj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtuwxnndsz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtsjmmhugn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmjgmoop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtyexsedqd.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtxtziahyv.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtjjxphaow.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtekgwddqd.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtukfbqmkw.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvodpydsr.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtozwezink.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtyrrqmjhj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtmbogxfow.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtwctjfmkp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtgqgwaqiv.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtxmfoenjt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtepwaicpz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtbswonjvq.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtibedycxy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtvgducmtp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtyhtjgjvs.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtmigqroim.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqzpgsuj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtuwjnvatq.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzprxkcfz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtlxttrbuz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtjnloezzx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtahoqcsui.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtjbviwvgd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtrzllchll.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtdukfcois.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtxkhknbkk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gttrtphlvo.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtqbonxvgi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gteoaipcok.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gtrkporeeo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtnaeyemzj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtmcxhumry.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtxbfbbdzo.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtlobdjnqb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gttagsvggz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuiagvqz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlhkeferb.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtoilfoirx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxqghleki.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbixpwxa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtrqabclfn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtwgypwqcu.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtlgmfpcmv.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtwpyzlpnb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtmzvtjsde.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtvuczbnbu.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtixdvpzhv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddzzgbkr.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gteiybldfj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtazhakdqd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtvmwbluyx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtjusgfjmx.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtmdzidptk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtuxtxlglt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtliyipgmb.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtsehartsr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtajipyzfw.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtfxcrkiwk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtvxvvxbvn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtqvaxqyqt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtdkwsajpv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtbqqrxwvd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtlvhkwaxt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtxursyafa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtbqpacjkh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtgqghmrxw.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gtkhaiygcr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtazznowft.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtzshzsnlx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtprhvdxdt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtqttcrgte.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtucnslgrq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtcvkgwjfr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtmdxttiez.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtslkomgmt.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtjscqlhuc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtuykicuaq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtduizxzkc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtlxppcvuy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguzjaqhh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmqqyxdk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gttcwnvdrf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtyvbaqslo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtsabllqsx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtlawdwuwd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtosemxsxk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtusimweqd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtezxeruaa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtobjjdvio.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtfdqzqrcx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gttzmjrmcn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtydsytfmc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gteesckdgn.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtztrwqtph.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtrndvjfck.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtmhyiiqon.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtoqftsgne.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtoyhvewbh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtpvilzmid.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtahfpjlqd.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtyqszinnu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtuxremrpu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtgyvacytc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gturncsjnh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsohgocyi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtnkrnaswx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtnnqvwmsf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtvnptzccg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtywrnekpv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtvjvrfpgt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtsnxrudpb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtowdapbrs.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtlrhnnvqx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtodktmdzp.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtgtkmsuev.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtpynmmsqd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtfuztarvr.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtgnbfopyn.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtnckvprga.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhmziuhd.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtjfiwowsx.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtxhrjlxap.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gttnvhaviu.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtlccpyuzn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtzwwfbqej.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtddrizgfj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtkazmzqbd.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtlgveaikz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbwufbbr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtfwzuskkh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gthctczpir.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtzmhgytff.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtfhzojvpu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtplsqmloh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljadpbjc.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gttrfpwoua.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtcclckvkz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtmoeryxol.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtrqslyptq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gthvsmiawn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtfnuknxda.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtxpmampbf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtuapwdgye.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtjwescgbm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtttujkbqr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtysxztaaz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtptjnbetq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtyuuglzzd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gthnizwoqt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtdscpsijt.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtdrfcnsyl.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gtqufhnpvu.html


<!-- 参考信息 -->