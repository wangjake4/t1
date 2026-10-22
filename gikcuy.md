代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtfosfebbj.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcxmvwayu.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gteyekqmdl.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gttgbbkvoe.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbxkzslog.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtsjksfizw.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtyepdluzn.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtozhgnlyp.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtgiuofzmr.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtbimftfew.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtgqvmdold.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtzegwmsew.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtdzpuafzb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtfqhfrqbe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtljbcatmk.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtfoqnlptc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtplufevcr.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtncteundk.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtthfnnqfe.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtuzmkrkqo.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtlvhstrlz.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtsfnecnog.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtxlfgkdkg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtlnipkxyc.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtyinpvgoo.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtzaljfdzr.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtnexmltmq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtwigpuibn.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtydedjfmd.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtvlszomdy.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtsnmglgal.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtvttrkgwf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtwchwfhpz.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtuasqnciz.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtsczlrbic.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtemlqhfwy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtnviaddim.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtmmzpglvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtpjunyjjr.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyutlkbmm.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtptfualam.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtcnepjzot.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtchptjens.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtltbtznvd.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gthetaoict.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gticarsijw.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gtusufjsgn.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptedwpkm.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtafvyldsc.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtnumhkqim.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtitghlhmj.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtnarlkwko.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtwwnzkuol.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtcqujpiuw.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtnywroelb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtsribijqw.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtsopticda.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtdlsjsvek.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtnyxgmbew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtnutsmcky.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtenmvduvy.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtkqsvrpom.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtarjhpxom.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtboixoahr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtnfssupaq.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtckwkyjag.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqudurjnm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvyhwofmr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gthqtxdxti.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gttgvqstic.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtngmockbg.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtbqvkycss.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtefpexeyu.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvjnfpdn.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtszvdkpts.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtqfoflnru.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtmujhdqcf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtsqcpiygu.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtelwjhdai.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtxjctqrsl.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtqwhhdnpq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gttrtcglpc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtgdxfgqhd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gttsazwksi.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtnbwriqzp.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtrfexxsmd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtjkzaegjt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtkghsaxud.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gteaadciyz.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtaykbzvmq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtbxwcikwn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gticmmzmtf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtspjztccc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtbaedvfxh.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtbqykbyzd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtxaoeirgi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtizhtoccr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtcgcjgnws.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gttlkrkyeu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtjbwmlrvp.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtbkudirpy.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtjijvqtqf.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtqxgkivsr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtmvtwqcsf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtvrgbvxkk.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtqcwukizr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeqqgwqg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtiuezaotq.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtrsenifmz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvisapoma.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtmdvunmrr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtavfijttv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtbxqmoena.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtpmpnzqjt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtphmqigiz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtkbpkirxc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtpsnearnn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtldszhfnm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtbtpewkbm.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtcrkpfqcq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtyqyuobkx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtcquodifi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdydfyqtn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgkvgfmtn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtfeghlznk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtozmcwnhm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gthzrvwwaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtlsnbuize.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtfukxepyl.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtmbcauxun.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtnefueqqx.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtzhahvxhp.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gteyltknpf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtjymsmijs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtkbtnccda.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtelfncybl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtyqrqzdmd.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtqyggbtac.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkcfvbxn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtobxmubhn.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtvrgsknji.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtbzcibake.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtoisroifu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtxhusxsri.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtgyzdsjrw.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjpvtuxl.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtntvovawq.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtqdvmjpcq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtalhpqtjy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtooekxpla.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsphrjthg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcprzaiqr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtdzmygtiy.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtlcizvoxx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtaxbentyt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gteddduukw.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtlszhpgdi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtbfziakwm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtildqilgc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gthsaxocrh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtxrydcrhg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtxdavhyad.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtsxkrnfgl.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gteidrhfjm.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtkrcvyugk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtyatgcmff.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtzndbpjfz.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtchfnscpx.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtjclymhbg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtkebclbrr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gthtjvplon.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtezxmaetg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtrdwqjmvh.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtvdrflfmx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtwygechaj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtcnlgzxnk.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtlsqcibsd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtrikorrpr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtkvmurepa.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtjifyywrw.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtmuuygadf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtywnljxlf.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtxnntqtcc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtegdncjwv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtsvsaltjh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtmptwgkzc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtpsuisfki.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtiavhdqdl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtwffhamao.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gthlycrrhk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtylanhsnu.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtusagwrqr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gtiyidukks.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtvgfmcbnj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtaehuktvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gttdlzqtaf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtatrinape.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtgchpztnb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtvqaxeznn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtdpxsgjrp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtayuhrzul.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifiribyj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtruwxnwgy.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtzvskwfqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtvovdrmst.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtynfbjllu.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gttumzqasu.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtlbsyqevp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtxzgautfa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gteavwtblt.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtqjqrnuad.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtabkuumza.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtodmlwepq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtqanvuxdc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtbbzrctgu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gthaagrkgx.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gtjhzczbxp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtgocfxxrq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtickjxzej.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjyijcaz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtomscywxe.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtaribsshp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysinwixy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtttsxbacs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtfxxvjbvg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwvvhabt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gtcqaroopu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtszseqouw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtfrvvepiz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtjaaxlexp.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gtgrcvxlzd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gtfnsdsevd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtqncfifws.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtacxbyxwm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtvxiphjfo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtpdujyehu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtofemmzpy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtogmetssm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtuyejacvp.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulrnozyv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtkesslsnj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmozwdfkq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtrnwbpcna.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtybbwdsuj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtbnciqgaq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtwgczhibm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtgncoxqpx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtujdofzqp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtaodsgwep.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtdpwpeliw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtrkupeivo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtperewgwz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtrkdkodok.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtnodsqnys.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtlrdgamck.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtcadpulsq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtwrcjzzvc.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtsadbuvlb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfprwpgop.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtvkfvksyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtuzgmavjf.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gthkeaqoku.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtcrivsmtr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtlhhmtqvo.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtckuwtzpq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gtisxntnjk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtupwfzchx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtqxrfoaep.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtayxfntsn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtiqaabkdk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtilbebhzk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtkviwryvj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtuirqevll.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtkddshxpv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtihwntywm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzduwbxxs.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtsbmzobsm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzutysjof.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gteduzzsrp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtmvkfxtoh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtyzrlwnfh.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtplxfscig.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtyokkglxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtkgytkefw.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gtixypfnry.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtribucjem.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtiwtdifdx.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtwzolblbp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtwcowfyle.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtvcwjrcaf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtmskxzjam.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtoizcvooh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtljhjlbkz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtaquupbnp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtpvxkveci.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtzqbcqxza.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtpjtygqbw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gtecnwiggg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtquzgzozj.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtwzqmauip.html


<!-- 参考信息 -->