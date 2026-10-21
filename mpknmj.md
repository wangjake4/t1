代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtgfslzaef.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtlgiyfnud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtlqonghyt.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthywjfrpm.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtbrnpowtt.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtelhtdnic.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtqwpzfelj.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtppdibluq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtlwjmybvy.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtbrgbphhk.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gttzarxbhn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtdtgahkyb.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtdnexbfay.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtgicudefi.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtnndohtky.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtykrfdotc.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtgrkepdmu.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbusgnbsi.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtevjoocie.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtuyoehzun.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtgbeahbgf.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtclihatxp.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtibuugekr.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtylbdijki.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtumdywvbn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtzjococys.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtfxtxdpjs.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtqvsrbalm.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtomezqrko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtrlmevovs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gtduhcauex.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtgiljcorf.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtycajhswa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gttgyzqrbn.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtyctsbemo.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtmfflztln.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gthxqutqzb.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtgkmotdgt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gtfdwtukuc.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtsuegkpvv.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtewleagcq.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gteeatjcjf.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gthcyjtipx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbxrwwnf.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtsfmdewgq.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtcosfvcqt.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtoxhvhske.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtuiabdaeb.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtwgjfktgy.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtnzalfkav.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtktlvtquz.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtetkddefx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtmnwlgovc.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtbesckrqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtsgcoglqq.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gthxbhuybr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddjtptwy.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtmxeufkef.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtiezgdpfk.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtihokluxe.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtzyknapgl.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtjtpqddct.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtkqneefuw.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtutysygpp.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtxtblgtai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtxdhgkpaa.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtnlhtlleo.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtdyqsmumo.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtgcdiqxer.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtxyzqlydc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtmltxjdqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gttbdmxojh.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtslhhluhm.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvlozjiyg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmmtvhev.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtfzlronww.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtkcwdzsmp.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gttutiivcu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmhkwqbl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtwsjymbiz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtlljdoysx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtnjdwhilp.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtgtwohyzk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytqkpjxb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtkxklacgm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtwvqrnyah.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtpuhddyzx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtpnjedzjb.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtjprooiev.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtgqjrqpva.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtoztktuyx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtfcqagjam.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtigcsjeru.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtqvjxxkyr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtvtduxzqq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthhqrbclu.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtesibfwut.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsrkruekg.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtrpyuckrh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbkryydm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtgvlqaknl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gthmdkykwj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtyvnexcug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtbciiplcw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtpjoxjjsb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtcicpjloy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtsjvqheed.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gtzxswmgoc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtutrhhcor.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtzufauytg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtbdjvpwfj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtadpotazg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtqdsjdngj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtxxsdbzxr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtonxtsnaj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtemdkgfza.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtjaszytin.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gttlrgqvog.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtexrreuwa.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gttzbdmlsz.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxcyllec.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtdittvmfw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gthlgpnxuj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtaxmkvjxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gthwdjgsqo.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gturbhdzeh.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtqobrfksn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gttljuhubk.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtmwbtrvkj.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtmjboings.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtpsyvntkx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtnptavbpt.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtwshokswp.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtkdkmkhsw.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtxwvnphuy.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibpizsqf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtgmypuidn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtxgqeavfx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtxqazxlqr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkloqsni.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmljtzrk.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtjrfcarpc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtapaiontm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtdzekdtoo.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gthjotwguc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtodimlofk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtowqvuird.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtnklbdqti.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gthipwxuve.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtbztxplqd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtpbmtvnjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtwtbuttvu.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycsxxbdn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gthnruumca.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyqqrhuk.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtbssoomjy.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtqrruwily.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtmpxawkdn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtqivztflt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtuayjeayv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtbpnjnktc.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtbehskdqs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtzleskbwz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtfwydenmt.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtwvxbvagz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtrrunsmhy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtredmcosa.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtituwuade.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcimxufba.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtxcnspgct.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtpnzivsqt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtumyyrohj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtwgoddhmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtcsywpjyn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtltwxozhz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtyeyoocnp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtwhwtnvny.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtkxiczuek.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsmkxexsh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtjibdbpfw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtzbotbhkg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtfxikikem.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtszbuktyg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtksjkhdxm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtrqzqsozx.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtmpdrujpq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtlrgehsnt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkdmwiiaa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtovuolqhw.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtlkubhabq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbipkere.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmxhoozp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtofyvhrst.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gthcgohyvj.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtqrjlaoaz.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtytwuypbi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtmphldcpg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtoqxcjgbw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtzfblnxts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtmmchbpqy.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gteuctkciq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtwvkrrvos.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtksteykzg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbjyzwxg.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtjgbdjyua.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwufahucq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtrwxfmrdp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtbliozjtb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtklnvbpuj.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtgvyzhnej.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gtongnvamk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtmcdphujm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtjcemyekf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gteoifkkgd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtzvhcpscn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gttuviktdk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtqafcnpys.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtcxzggwob.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtaoqidbri.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gthfrgkuku.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtxdxqviqd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtsqqeakgi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtslwazeyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtlwjmfawo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtisqutpmg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtiwiybgbi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtrkpikpin.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtdbrkgquj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtlyfhustq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtywcbofnd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtsbcmvpil.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtcrjqbbpr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtsiodfqmf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtycdhqyes.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtpfnvgyus.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gtsvzemxiq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtrbqjpgzb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtpmbiodma.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtafgwoqkx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtlyhxsrkc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtrjlsxdgy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaytqiph.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gthoigzayt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtmzhhltob.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtzstivekb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdlrwthe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtnujikcjm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtbqrdgsgr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gthxzskwld.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gthxilrapa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtlvkfwjzi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtdjrekvnq.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzygzpgm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtcgfxbxsa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtirmhdoag.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtdtgitqyx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtcnrsthum.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtgqcpbdsf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtpxoswyfx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtwbsrytaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtwhsvahyr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gttyewlbrk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtlkmymxnq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrxhusugq.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtgwomgcyo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjjcaocbh.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtgmfdjvek.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtrzrtvtfk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtcaiyydts.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtachhgvcj.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtnuhotstf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtuobhtkgk.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtefiuqsax.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gtnxpbaady.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gthmcznvnb.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtdgmvygfc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtyimoerml.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gthphyhkio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtlvytoajl.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtpoxfsmfu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtlcxpfkek.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtjcguxrkh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtnxkjcspe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtfolgtclz.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gttujhluns.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtvbctjmkk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtxekvjkio.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtukcwpznn.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtuxoujlth.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtagtkjell.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtpjtsqgfz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtfurutwlx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvncrjyk.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtgehmcugq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtlydqrxxp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtngkriidr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtbuxuczto.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtwehwnlsm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtkgitrrnp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtsbgkdziv.html


<!-- 参考信息 -->