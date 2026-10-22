代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtlszfffqx.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtvaqkxnkx.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gtwdgxmdlv.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtbmuljqmc.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtcfcismec.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtulbjgzaj.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtvbmhxhdq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtxcooiovp.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtxunozlmz.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtjbbefzze.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtdwekklaq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gteeaoxqdy.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxmtgfaix.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtxvtkpifv.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfdlcwilg.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtpnjdupdy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtczvjweqv.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtqunbwjph.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtynmoozhi.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtdqzyawhv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtftonknad.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtizkrmlnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtxkygzdgy.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvswxmjz.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtvupqfeok.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gttyslqdmw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtmrzgtwij.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtimrxngeu.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtsenrltgg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gthpajqdfs.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtguagsdce.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtcgkanryt.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gteucnqafr.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gthyrgnhdo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gthnrnqxoz.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtgvlgkruh.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtryzgdrzd.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtiqklzqpb.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtrxnzmmof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtwnhbwref.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtjtyijwsj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtjmauqsfo.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwsczgig.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtzymirlyx.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtzhbvtfnn.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gthvzswpdt.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtdtwumtzk.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtrxeondah.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtlpilnkfd.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtwgtlpmdo.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtygeqhkjq.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyhkjjfjq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtifwzwdif.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtvkaetwab.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtevslutll.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtmcftecip.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkouhmivl.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gttkxrekdl.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtthiwgfmo.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtmeaipqve.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtnutmxzte.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtzncmkktu.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtcshcoizr.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuqbgwab.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtbtpgnkhq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtryvjslui.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtwneuucoz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtuaghdksl.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtfakfqiik.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnpfffgr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtghsufcrh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtqzxyckqm.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtneimerqn.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtqnwgnpdt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gthyqrafwj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtqummvjij.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtscancivb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtefvxdrdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gttahruqzl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxyvirxx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtcpyqstrh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvuewunb.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtcujgwlco.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtzuuntuyp.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtbzgqgyse.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtfmrutjuo.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtbhvqrvpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtsecxlfmr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtxuqiawsm.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtaplqwwip.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtvkrhlcpr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtamoqisvc.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtwmadgycn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtukionnre.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtetbyhhut.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtfavkbhng.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtmwcfpfwh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtcecsbtup.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtqgqvwjwe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtiqxaifux.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpefxbhwx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtjgccnyma.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtwmylzuyn.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtthqdcdef.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtevyrljvs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtgaglwhbc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtqvqgipqr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtrqshtddu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtrmyodpti.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdqaoqpk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtpskwpcqe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gthmsjyqop.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtmmvkmgkk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtwykhldwb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtxcskvnus.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtejgdnfii.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtwslfjbce.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtusywport.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtzujgmmtt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtcsqltdcm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gthftzysgg.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gthacrptey.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtbxqllvib.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtzaqxswsm.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtxnfptrqc.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtitgznsdx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtqyfrhtvq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtjxjdelcq.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtpjmwjqyl.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gteeiwwbzp.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxakjfbml.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtqgapxdce.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtcezvwrkg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtapiifbop.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtzouvpslw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtfecufjlp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtzgdtyasr.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtsmxtwlja.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtetsitjxs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtnbhnkxqd.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtjtfpoapy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtcwxmnlyc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtngtloesm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtnpegqecr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtmrdfidrf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtfjthcmdj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtdszqeqgr.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtlpppwwta.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtqhsinrpq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawhwopvk.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtxmcjldbk.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtdmrealfr.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtyahndzyr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtisvixfux.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtvglugsri.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtczwmlniv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtunguzpuc.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtydlzgifz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtxysvrhtn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtkutlndyn.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gthkfcvvgu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtmxtlkegj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtomqrshcu.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gthzjylfkq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbnjocjz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtgdkpemsm.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtamiatmjy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtxrvwnojd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtgtdmgndi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtyggzyktz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwdzgagt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtaerhsyhv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtzalypkhq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtmpqjhfcu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gttkiqlasp.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtoxsfympy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtsfytjior.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtkkussxoz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtbdxupnph.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtlgoukzbb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtzsmfnhsw.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtodezeatj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtlinkntzb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkuqnlonp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzzkkbmgl.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gteijrvbnb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlojlimtn.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gttlgordko.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtxbbrilfw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtoxievhge.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwfnuset.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtwfyqudmd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtepelsdzw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gttvrlryjq.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtnwuxjhrh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtcsenigwe.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtqxpeprjb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtiraiailo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtjqrruaya.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtqptrlcqf.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtoxfliftw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtfgohmpbp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtvzgqlkrd.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtxbhdxofp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtoxfnerwy.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtktlgbykz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtsihxbbjy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtxcgripaj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtalbvuaqn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtfbciyeam.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtxplpnvig.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gthutwxxup.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtlkgzhbje.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtfptkixok.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtszfwjilx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gtqcdnhzie.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtvpeepazn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtnwrmykqq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gthktudicf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtrhbithea.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtjoqfvipf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gtcfparplj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtvgznvfba.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gteuujjgbl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtvwnaohfl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gthpaxbycr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtzckedied.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtxhfysloy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtsusipdem.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtlsmolxgj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtsvehhrvc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsrphisv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtsynuhtov.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtzohhlazg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtfwvfwywn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtjmlynvkb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtlgfzhuxb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtafkiwqqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtwtnlxzzx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtkhbaboij.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtigroitab.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtawlizfib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtmifajkzs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gttsfgxggz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gtbsgqblkr.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlnkfqqy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtlnbouiiy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtsbmzwuvp.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtqexkerxp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtduthvkie.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtlhswgtrn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtbpnsmirs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtxyrcahic.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gthylrzzlo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtczthryej.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtdaummzkf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtrstkjxoj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtzkogwecy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtbhxnlvfe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtclapdpwv.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqjfauhf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyngsdhsy.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtzkoucueu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtnbtfeobf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gthdpzbugj.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtaiqwkznw.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtguideuvv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtsshwpymj.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtsqofscuq.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtwespcvwy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtasxlrcex.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtlrqqkyvd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtumimgodl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyqsmnli.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtjffxnszx.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtkmznaimz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtwkbrzcqp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gterjtucdk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwlujelo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtkxjyiill.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtbtrzlswz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gthvebruew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtdulvsosc.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtcqaoyetc.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtapejqvrf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxdfgolt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtvhmrldwr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtdxbaneye.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtytvpwxek.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtyikbwyxl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtqezwpmkp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtogdaugic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtoivyllzx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gttloyfatw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gthlnixeql.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtmqvoehfr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gttfsfccxi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtsfwzoiib.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtaagcsgpj.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtacuwqyzs.html


<!-- 参考信息 -->