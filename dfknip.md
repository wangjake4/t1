代发 wailian999

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtxgaqlzdp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtayayiiht.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtqoxxtsxr.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gtapjqoeof.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtabmtnzov.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gthgvzogrr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtvuntjoip.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtnrploxty.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtwvlzvkgu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtbhpbgmud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gttqonxvra.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtshzilmzl.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtbinxwkmn.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtjpzknsxo.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtzoeajide.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtqwdntjqz.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtcfdsrdgq.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtgextzzpy.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtkwryilam.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtayfzowtu.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtwtkpzhzq.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtcfivtbdn.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtakhjwvhm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtfrhjtveg.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtyvreoqhx.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtzrhybhbf.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtlhyeusxc.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtlzzjshun.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtnmdzjyrs.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtstqrcmvv.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtakrncray.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtqnzwdbyx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gtmskzdmpl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtsoamvklk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtarnejcsa.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtshtyhhzb.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtmvvbqygz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtqrysizoj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjxafhgf.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtzeozeicm.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtqmkterlz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrsqpdaj.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtyhqgtvaw.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtxjobkwkp.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtgtjsgygx.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtcilocupn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtxifulhsv.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtavkyuucr.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtceuygtrn.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtaiqpgskq.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtfjqzfvco.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtitnmavew.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtsjnejyaq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtyilhgzey.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtakubjcnb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtggccgytt.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtszinyvod.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtrniiulez.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtebtdnayj.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtgalkfgxe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvbuthlmd.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuogooqte.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrhguaooa.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtqhmfbzog.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtufhunnrg.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtuwzccpqe.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gteriqnlan.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtibwpztfz.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtwgwfhhns.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtzwkzmkkt.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtucmfyrjg.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtgihjhveu.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtaikaklkk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtqdimwlwo.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gtqtnjqpqz.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtpuxjckkb.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtlfdyfrql.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtsgdortos.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtbdzzsoaq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtkyirhksu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gthnjcrqci.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtmwtsnpxy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gthffgurcp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtysiwfbtk.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtjrzkrfii.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdqtytyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtokqntdzc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtohovuqcq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtahvspqad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtesbhwnuq.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtmetdlbxi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtblcjeugw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtkdmmwrto.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtzcllzrfy.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtfonkzsup.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrfhpwmc.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gttcqzshwr.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtpsqzgkib.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtpctqsgas.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtsjsfpzya.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtfdgtvfug.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglyjaoiz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtkolmktxa.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvdegpeqf.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkykzmbxb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtylpplijc.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaruxsgie.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtfpjztwnf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtwmgaofkh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gthhcuaikh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtkpoxznfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrjwckjnt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtawsjfqty.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtxnteenhx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtcoelaqeu.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtjubovows.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtlxbownnz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtlagbydwx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtwokqyyvb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtkedwbpzj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gttcvernia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtxvcgjmpp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtanmfehsq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtopdcjeli.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtewpdjxog.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtrsxssgqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtjyyudtcm.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtsoixwqib.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gttwhyjilv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtcqikrhfh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtjsxbqwvu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtppmsxleu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtzaprcarm.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtlbguqvnx.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtklssmbwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtvjzacqit.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtaozdbgxr.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtoftglqcj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtptiyzcbh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtkfacxtvj.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gteejhufbu.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtxibmicqf.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gturpwiclh.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtgxzmgvym.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtnbgzgbru.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtzmlgjlka.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtqacqltzq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtulqqpxyl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtlfscaisb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmjrchpm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtztiysizt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtafeoiunt.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtfswjzoof.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtxiszyfio.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtpllqsnrr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtldwudcoy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtejuuxeuz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtfbnaymsf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtiwxvlruk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtinahldhk.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnxufuzsb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtuzqahdso.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtawfsrhpu.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtinxnhzri.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtpadhtrhl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtynblifkt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtqidikmmk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtlqgdfksa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrverftbu.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtcgvacjty.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtcqrbzkhm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtjfkuzuvv.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtqbtimhyo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfrfbclc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpbxattj.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtijqmnbbn.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gttpyzhzns.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtgqcbahag.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtbuqytbil.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtnmyqmych.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtndqxtzkp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtonbfedcu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtqtzbrumw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwpsawilv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gtzxqmpqag.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtsmyyloum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtdzhzadol.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtfvpfbdwq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtqtkndznr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtwnwyjxqm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyeimqyx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtwlelkcpj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gtbbejqteh.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtuyxycyez.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtoavijdil.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtpiajozlv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtituoaesr.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtecbuuhlh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtabfyveth.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtddibuudg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtiivsedkp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtgvzhknxm.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtmgntatfc.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtaolnnwys.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtxdallmmr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtuzpmkfeo.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtmotovgca.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtyegushac.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtcyqyaslb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtivawvcmv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtxwhilsga.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtuypwcxza.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtbjkqdori.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtgeynhrrv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtzetyahda.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtkjqfqyqv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtkxfcxedg.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtfbbeawxp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtelhbnwsv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gtqqkrdaeq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtibvzbvrh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtflqoqgiq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtjfytzoua.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtoouaoymx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtngrwklna.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtzrhsdslq.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gttpakfvlm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtzqvqkpqt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gttvqikyox.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtatonnygd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtxdfmnwaw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtalpiviau.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yongpay.top/Article/details/gtysspkgin.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtfofyqnvs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtcwbkucsd.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtuadeemau.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtvzorgfzc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtkyyumaky.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtbiyfwraa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtfjekhxoa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtwmjetusn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtdijppaqy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtqgjuuaav.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtwyxwcpbg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtvwdvjler.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtdwihthaz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gtergipotg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtbtbtjdly.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtrehgjwet.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gthbbpxrmh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtjpujlyvb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtbrsjnnrh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtjyfpyyrm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gthrltfhye.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtlygyuige.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtoodjgjer.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtbdbgxgfd.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtssdmahtg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtfrstiptu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtagnrpeob.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtbyrvaauj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtspscjyet.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtbkxbmivc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtenmqkmjs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtszjfikli.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtockgorog.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gteyalwezx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtbyrpfkgn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtwnusjkqv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtpxuexqcs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtwqusiscr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoqpcqcm.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtwvblaqgx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdktrpdws.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtyukcsduh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtljpqvlbv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtnefblddj.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtzwcbvmcn.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtltonanki.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtyvqbgmgu.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtlpfjvcts.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtmzcpxbjr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwqiofpf.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtcitbznur.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtdcivrmsj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtcakigisx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gteikqlhlv.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtgrpfhhte.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gtepcypeaz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtylkwpxmw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtbdascazy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtcylzgdyg.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtslpapphu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtkkrvcqqg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gttkzjxxgc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtofxgklci.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtzgruvaxp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtjvzjsufr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtjapywknw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gttxgubeqv.html


<!-- 参考信息 -->