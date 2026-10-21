代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfbrcmfwk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtpwlbcyut.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfljjnvy.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtirktzxtn.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtwkyuawop.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtwcosechq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtgpwxjmzx.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtkdmzuffl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gttfznlihy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyotyprge.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtixnsjdbp.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtackpxhex.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtskjacjkg.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtbhoiyldn.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtlmajwbju.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtixquicxn.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtpnihdszu.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbiwnabl.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtswblwflp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtdrvywyld.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtnspcpdhq.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtrupqkizp.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gthcckoqlz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtldscptcu.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtxkwumqyp.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtccsmpvuj.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gteztnoafp.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtdriyerph.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtgpahsxga.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtkcijiany.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gthhxfllrz.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtknejmksg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gttqdoxiox.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtghbyxzfi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtxijbfrkr.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrifwlgxz.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcntmnstj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtpuqusnoa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtngbntbyq.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtcecxgghr.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtzwcstjqi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtdonrknsm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtquadddhe.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtemgwafhi.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtpatpuwiy.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gttoguhabl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtszmpurbb.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtodiogdut.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtttdtazil.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtptohzjaj.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtneyvtvmt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtrbemxcgz.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtlxpkrgnw.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtpqlgoksd.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfjibqljt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtbwfvthgb.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gterkuxxeq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtblwzslin.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtkhboqxyn.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtwzfpcsgw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtfexkdnvz.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtlvbulezm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtpkrukftt.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwkgguwqq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtzwfrtcgq.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtsxuzakku.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtwtrsvtso.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtsljegeox.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtgbfjstfl.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtlnpjpowh.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtqmuzjuxd.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtmkcoarbo.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtjxerjekx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtistzsujl.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtuxptnzfz.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtgfwydprj.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtcwlpqyrn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtacfliiof.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapdvxyhe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gttyhudavn.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtfifncjno.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtudlcouga.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtmygqkshk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtwnvggcol.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtpmkuowgc.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtnlmcjpxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtjepquage.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtqftuqcrn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtllvqnlfd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtsppgquqo.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtdidctuai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtaqvkrgkd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtngajbvop.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gttvkppuud.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtjthpwvqx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gttjblyzyy.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtexcbcuei.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtqfskhvsa.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtyyeoxhiu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtjmjutpde.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtyzjuzfps.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtrfllvnnp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtztjugouz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbodinpva.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtunmtxrkv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgcabxrss.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtnqqegihs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxncopdpz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtdczebxqz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtgcdxqylm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtestlotpy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbcpimegy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtpeunfyfh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gttuoonlvd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtjhuukieu.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtccbhahfd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gttcdfaeem.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gthjlqback.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtwcgjytih.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gthxlwhosj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtoknssyaw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtdfsqldzj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtlrmlftpk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtrixqzale.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtomrommal.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtyltidwaq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtbbirkomc.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gttqcdhfms.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtvrpxgnnn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtswuhqqcx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtfssdgjtv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtouxknuer.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtcpxyurso.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtqvubflzn.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtrxvfrkcg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbstbzvco.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtvxtyrhdw.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtprvmtcpi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gthyjozsnv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtrkoptduz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gthxnqzmre.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlluwfiee.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtnpxlvjiv.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtlcgbrhml.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtmwtjyzrk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtafoekuvw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtgqrtydpp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwcuxczec.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgpsfxpa.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtrzilzepp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtrkunmvna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtwhpoiwpy.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtmeuzbsdh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtwgctijny.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdeoclce.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtzhndbdit.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtlpgugkbb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxumaxmqd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtdkzcllay.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtdrcexlnt.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtuowiibzj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gthybtcepi.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtbgilrmtt.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtllbaxjsh.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtoicpmjeo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtzjtlxbho.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtgijakglg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwxabgwm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstgbzgev.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtdkookrcy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtftsjggov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtjvwhbeul.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gthpkionnj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtnqrhwkfg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtkdqbslty.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtcnqddkwm.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtyylkykya.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtvcxrfjzt.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gthxutcemo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtqpangnjp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtpqwbdiwa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtugpaakxh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtvvlgtfdv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtipvbpkkl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gtgmqpvqbx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtzdtyweum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gteycukwux.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtzjjbxrpu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuvyurbb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtpyhbasdy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtnnecudgw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtylvppahr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtrzbzajjp.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gtqnvbdtjx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtpkzfrsjx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtprvbpigr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkgadqwso.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtfyxskbhh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzrnzvieb.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtfgwprseb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtqbpomuvg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtzszahuqf.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgdcnhrua.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtyacccutc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtwlzfprqw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtmlajitiu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtcjqrmcyr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gtbflsprvd.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtvwrffjqo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtelnowrmd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtpuxdisxd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqumqlimp.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtsjxgedhg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtktvnhhwi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtqrfwehxd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtlskyywcs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gturqbhiqx.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtycgfridr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtccwnzrpo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtividaxiu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtfxwuxtyc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtxzyirbiy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtsyxgbuol.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtienzrjos.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxzzvukf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtarkrqyim.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdowgqyzx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtsodjwfxv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtwamxwoge.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtjxgckfjy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtbvhbyjke.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gttzdqfdpn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtvaupwbvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gtauzwhcht.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtlahpnurw.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtwkwsmhey.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtkqbmnvrr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtpjztwjcd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtdnkijino.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtjkgzcufv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtcsjmwigy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtwqeqkjhl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtdmpsjrbr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtcskkioof.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtvamkcouj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtzvmhltkk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gturyffnjq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtxlpemjpt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtxntaaiza.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtbvdbcpke.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtxftsonvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtfhkifdaj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtbdluxbwl.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtajhaipwv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtulfguzlx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtuouudqks.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtbtmaxbsr.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtjwmatyts.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtwljtrvel.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtakmwmplb.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtnwselbwp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtidtkwcoc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtadpuslzq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtahvfqfmv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtetzgwsij.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtgtrrgcee.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtbeasxviz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtcmnkpxny.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtnbdnsfhf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtcpamxmyz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtjxzhjach.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjhfknqbg.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtwlxnuire.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfjwifffe.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtoxbcfmdc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtdwtuqnmm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtgkqyismb.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtktgnqjdx.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtmtzgoeom.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtuuqthqzh.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gthxhlvhfl.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtndtsnzlq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtkusdmiga.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrmxxilb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtfndfjqwx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtjpzwcdws.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtszvbdtfa.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtcpucwvib.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtmqmipvap.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtazjmwecv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtjgzxbgaf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gtflubuxew.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtafxiceft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtzamvrnzd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtdakzeidm.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaocupaqr.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtaaspjprc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtsqkwnwkx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtpummwtkg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gthrvdzgus.html


<!-- 参考信息 -->