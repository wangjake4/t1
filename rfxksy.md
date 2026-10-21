代发 wailian999

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtozkhnrao.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtypjrklzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtrptaasjf.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtcnojxbxn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtasbqscgh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtqtdfpjzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtjddimkps.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtjjsevset.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtnhwyayoa.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwgwtbbw.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtlnnadqvq.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtqwgusrld.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtuligeqsp.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtxvpslvgi.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtmsjgsfzo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtxmtpeifi.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gthhmjgbsb.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtsnskpwhm.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtycbvllxn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtcqtxwfun.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gttlmukpwi.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtqjespabc.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteljogvvd.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtvdlqszip.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtcpppcfyo.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtixnsvgav.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtywicyyhb.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtrrvigauj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gtlxiftdpm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtojxxbkqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtoxezhylv.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtygeucxsl.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzsdeops.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtartgnbbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtlmedxavs.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtmlbmsrhj.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtmoytvbpq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtqoketyll.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gthouwkzox.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtegkqgnsc.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gthhksczjs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gthhzazthr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtextaruln.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtespaunti.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtzgvzkevv.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtgifkcmks.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtdekyqoru.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvxhmbeqa.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtannyfqvx.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtscqbbujh.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtxdsljgmt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtxwudejeu.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtjporpzxm.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtndnhvcig.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtbxeynfpq.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gttqvuphiu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtvhjtpnho.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtgxjyqoyr.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtgoqvrlag.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtunernaia.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtnantwrmk.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gthsagjask.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtsyyqyrae.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtmurjulmj.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtykjaynfn.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gteuicwyve.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtzzgzvpwi.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtjickqltq.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtlqfbufss.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtcwmmxgwp.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtmlmakhhk.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtwcxpbrdc.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtphqiuypy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gthjxcxmqw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtczunsdec.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtfvufiqbn.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtmmtwkeip.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtmfuuxfyu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtsdgstycy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtrifsuqmh.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtlxfnnqlp.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtyabvmnau.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtibtvkrdj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtztvwkgdc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtzxnvxgsp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtnhnuveyp.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtishsrver.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmyqdytv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtsdkghdcq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtzvlucljq.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtfhkfcduo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtasqlwfft.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtbkufitxn.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtmbzutnnq.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfiddvkkd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtmwlglyiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtzxoncmje.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtfbluztdl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtcnkzxvot.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmghnmuqy.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtwrzseoyd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvepcqceb.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtnqvbmnsu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtbpegqxib.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtxjzfyctq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtykttqxcw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtfqprffmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtkauqezzv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtgmmptbjb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbfknzbv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtefdtgxth.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtfuzfyzfq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtdzwuuhtu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtgawsescl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtuxhxtfjq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtsbtlrrnu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtacweoton.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtvdrzlqtw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtebwujfza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtanmioitj.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtstspulcf.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtimcmknla.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtczupgrss.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtzywcvlha.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtgocyuzcs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtcshvwhom.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtmbpjcrin.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsofrdtl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtqpzaljov.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtzyzkljjw.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrvpclra.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtyhucqziz.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gteibmgnpb.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtcwwgjnto.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtlegctkml.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtqbpenxpa.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtzqsfvmib.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gthgkbbquo.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvtybapy.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtrmjkvnvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtfnmbksxc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtygcmbzqh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtqlvpgqek.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtbujfdbip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtdyggudft.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtdgjkfytx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtarmxerld.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtvrwqdqqw.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtuxxpaupx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjiwwsyb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtwdzqyonn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtsaaldjxl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtfjnangoa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtqmrdyctk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtjimdkkyc.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtzrcstezk.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtgzxyisvt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gtgzdudrnk.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gttmbfpdyr.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtbgenvzqa.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtadsaibjc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtgpptnrgl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gthpmeqtvm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtoabtvvxg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtajhlupne.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtrkuypyuw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtxwxisfxr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcstztgqu.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtkcglapfm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtmmeujzju.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtcakyedqp.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtqsiihzqq.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gthelfqcri.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gttqwsirze.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtcwxumtae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtqajfykjc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndvadati.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtkpphjajp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtdgpoaxmc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtfracathh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtdqyhxxxu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtshjegnvq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtkjzxamze.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtpfctaxxx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtagcbpfaf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtvvkmixrc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtwinxoeal.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtfotndblj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtbovjpokx.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtvruphise.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtfulhnjhv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmexsokna.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbrrkbmbn.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtpogkiinh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzwfolynu.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtlfadnadc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtcjsokdfq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtekotkaxz.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtwoplpuan.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtqfaioqrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtrtqrnqsb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gthvjobadz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtcqzwufpw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gteojbsiyt.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtbwtwptai.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtotsxvguv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtqvchmgri.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gtthfaxhop.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gthubzdqmq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtxcikqhhl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtymidiqkf.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gthqykvfcd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaslkbyq.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtvrwknler.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtjwrgoptd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtxxcmecxd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtuprfyxoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtrveicfgt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtgtsqmlpo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtdadfhgyp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtxohvxwyt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtjfycwxxl.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gtmdeouljv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtatxbrxgv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtltgubaga.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gthwjuritu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtqtsfmrif.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtkaniyusd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtxaljafzt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtvfrwrzna.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtccpbgajb.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtogyggyxl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtagcjdvbw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtstnjcwey.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtsavlvmzt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtejihdrsa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtfhddynjh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtjpdkxlka.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gttzivtyoz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtqflzivre.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtrbjuzbpm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtmqncxcup.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtgqwaautq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtmjxrpify.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfahhspe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtxuarejra.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtemgyzjlm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtfmuwvbvr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtzvhkclmi.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtykzkeokb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtawtojecb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtbschsbbw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtzsycareh.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtbjczxmrp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtreeddqma.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpyyuxmm.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxtjeuwq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtqaomsbja.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtnuntilqe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtmyfhwcdd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtwzcsvuaz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtdjaqsfks.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtuflehgso.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtnsyynrca.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtgcruystv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtwpsiplpx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtzbqhlkrf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtccpnsuve.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtourrohmr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtneoqjdno.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtqyppfvqq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtjejgciin.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtunlmbxzj.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gttdjpxmzy.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtybgzfzhl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtcbdffamp.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gtmlfgvvld.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtxewqmzob.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtdmfzxupj.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gtrglcecdw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtdmcyxhuf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtrilwrhpo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtofrzdsqy.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtonlyhplw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtjntawqcv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gtrjjbmoiv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtiggpdmjz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtboyqstgy.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtcbmvgiir.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gtxdewrcno.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtodmpaoxh.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtjepkecqx.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtbtbbniob.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtofhsvitc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtfvfjoqzk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtrfaylshr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtymvutkar.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtntueluus.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtqkoqdxlm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtswilozxz.html


<!-- 参考信息 -->