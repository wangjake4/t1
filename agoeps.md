代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtduvewxtn.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfawxkrr.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtwsattziw.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gtifdqjhfy.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtxfwunbai.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtijqibspj.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtgpvjhngo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtiopiqiij.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtmsahovxb.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtjyqaaeqk.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtivqxbvoo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtwtmuouox.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtgucyuwqt.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtvarqxser.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtgiqtqlkf.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtaweokuwi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtcikgsrud.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtteyduptc.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtcruhqflu.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gtvtijxuie.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtzfsbyrvy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtybznejqx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtjvmxamty.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gthyfjjlvn.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtayivelfv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtcdkkhxhs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtearuqvht.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gthyhqxwbk.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtufprfhhd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtuskxeyjs.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtwzmrjmav.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtmooseceu.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtqhujysgo.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtjgpnrgrl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtxdtkhowd.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcboheii.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtiioutxee.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtmbngfdhg.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtiemdzjlu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtnclarppm.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtbdkairiq.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtqtitoyrn.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gteyggvheu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwtbcnyr.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtqtrgcvlv.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtqjiubvrx.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtvzlblcfs.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtkyloreng.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtydvaigsq.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtqwcwrhdy.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtawqzpatu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtlxflgver.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gteohtqqzn.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtxkdrzabe.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gttzzlqrxd.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtytjgqpck.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtxjbdxizw.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gthtiumnlk.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtvxtnrqyp.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gttmuwylpt.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtppiabrmk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gthqaypmvd.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtvyidvfgk.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gthfzcgeow.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtforluqrz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtuutnefuh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdctfhegc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtaxrfcugp.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtefylwoop.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnsefqao.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaaufupm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtijolekcj.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtexcwwbuk.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtiywyxpha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtczmacsnw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpjseikjn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtiulegvvc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtggxvgken.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtbhsidbmo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxfukvxd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtcnqpwpmq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtutqverzu.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtjqemeqlt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtcbzvzdjf.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtajhpnrut.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtybfqqoie.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxrejybx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtrqilssrv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gthhisjaie.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtbkkfxdps.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gthokxnrko.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqxgyvang.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtrsxzcgdn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttktxkhpx.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtijrmcear.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtzlcfczjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtucumatgm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtpfqadvew.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjbnjcljn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtmihasalm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtzuvmldxi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtvxtnenuq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtfmkivomi.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtjojzqrwp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gthrcwamkr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtfuexpmmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtrwzhtevm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gticeqfoee.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gthexrdioa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtztthxiru.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtpcewsivu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtujlslmnx.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtxxhqasvw.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtemkgtrpq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtgfiwjbpx.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtjnkaurav.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtahpnlqtw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtvzsqfqhb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtkltlwjcp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtjpsrmwyv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtanbgpmzz.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtfkztrysy.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtklovfric.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtlohdmpkt.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtlbsfxyhm.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtdobacfrv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtdlzwkoyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowlmfiii.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtaewiczmb.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gtlygqnxwq.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtobcetntu.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtkkecjonf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtjgkjxver.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqbfeyfn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtnwnuysvc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtoxcwzosw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gttybwlyfr.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtqhblqujv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuvuzyzmc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gteaboarvr.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtlucdfnml.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtxknymrmq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtzciyglsc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtlhizbils.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtcnobeupn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtxqskfcmk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtvaclojzb.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gthdjmqezc.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gtlqopzexb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtcuyliwcp.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtcbsbqrsd.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtxkabqxsc.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtezmxrthl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtnxxopzki.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gtxqsjqbmj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtsqhxgicu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtqxzopbbr.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtxwpnyqhx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtvbiwjaae.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtndzmezvw.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtmrsgwamy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtirhfnrti.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtjzkadgja.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtjwuwsvkj.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtyxpoonfa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtssuowkjh.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtjyyijbgk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtnvtofndj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtfnhpyzbk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtpobiseuo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtrqocwxgq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtknhptfuu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtdcfwurow.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtfipjwskf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtevgitwuh.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtlvuglzbj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtjmpbfyxh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gthburdlyl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtyckllugr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtntmvszvz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtgzzopehg.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncktyqnt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtaylwdqml.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtllqzuppe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrqsazcto.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtpuwtpytn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtulvnxyir.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtsngtcqvm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtzthdxykw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtncpvegbm.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgqbngdu.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtgzaepelc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtnhkqhtne.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkmoihzqz.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtxqmoizig.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtxqionodu.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtubpfymzx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbmnedzsm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtmbnehody.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gttlisntjk.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtdemaaigs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtmrlksfzw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtticwzubv.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtaecjqdsd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxsugoyg.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtbqcghwfy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtdmoovqzq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtgzwierma.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtlrrhjlij.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtgcqnliug.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtwtcxfsph.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtmbvplpmx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtpwfmujed.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtkocbqvyx.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtbpafasuf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtcpaxtopr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtlcgpxjla.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gttqxndlfa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtvfcbgpdv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtrzhipgzu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gteloskoyt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtdpspztls.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtjfzpyfph.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtrvtexgrd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtdtmpgkod.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtopurixwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtvagajnlk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gthpnxsqob.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtajiogryz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtrgfhtpcu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtemvwakhm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtreixlkrd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtumqjwtjo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtbwgwblxy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtgwxcwldn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtijzsrcka.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtkzujduet.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtdfxxlsde.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtqprbmblu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gtrqlfgtyw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtywwxtivz.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtixcqtief.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtjbqtzmpy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtvuobuxuj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gtohyfjair.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtilvmreuk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtwteuizdz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtbvckavzn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtgevjglpq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtafpruzqi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtlaznsfaa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gteshtgkcg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtkpaxuvnl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtemwumdbs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtijxtznmr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtqakmyopc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtfbtkbymf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtbhjrftqp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtdcryucnj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gteheizjuh.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtitogvafj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfxbeipif.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtevuzuhli.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtatqnowqy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtawruivpr.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtkrimlqjw.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtxccjhngo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvkqkzwb.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtrcjkxdho.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceorxalo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtadumivyx.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtpszaumuu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtcrevieot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtljjaudum.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtlbbpvgpx.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtsehpnepq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtlmvbleyg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtoahyayvc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gttutbsbkm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtaxivwgqn.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtkugjwttw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gthxzwapji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtbjhbozjo.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtyjihjzpa.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtskbqrogz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gttclrznbe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtzyhxaxxj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtgaefzimv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtekptoojh.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtuulffxnx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtcznmgoti.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtianjmlbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtzsbazyht.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gtpronrpvf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtvkfczppw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gthpdzbxky.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvhgbsjn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtbfzwnwvk.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtxaajrkiu.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtxgupldgu.html


<!-- 参考信息 -->