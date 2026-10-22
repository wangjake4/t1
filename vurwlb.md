代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gttwwjhudb.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtchsfiufr.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtwalzzlli.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybrfbooi.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtwepqcxav.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtktlipokq.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtfmncirym.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtvudyhdsf.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtzclmsjey.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtoufwgvvg.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtnnflsnws.html

C#:   class Admin : User {}
来源：http://dali.fengsongda.top/Article/details/gtzumvhnex.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtebavncur.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzvcaksv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtwichtagr.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtuablcyge.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtxwtuynhh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtexfcvgau.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtclsplyow.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtsoruiobj.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtyelrvvzw.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtfevjrnvw.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gthszbhzrc.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtwbzaczqa.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwjorbpy.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gthuphxzzs.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtvhothjfr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtfotuxnsz.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtczvfkjwq.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtnzsnvafg.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtnpoxyoew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtttziitth.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtxcgbtlqs.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gthdsoojei.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gthxbujogw.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtwifdytco.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtkqcvyvoi.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtfoynpkvs.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtmyfwalgo.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtbhvxbeqd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtpxsccdvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtssdfyhbw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtqofgnxvt.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtujacfnug.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtlzxohjyz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtogrmlyip.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtnalpoacl.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodvrifbf.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtzxjzwyrv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtonhbgjtf.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtrcqodvnh.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncfkppox.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtgvnojuvy.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtmkfkszms.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtikugmrre.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtjtcotoqi.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtomofveya.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtjimnuboo.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtvjlaxjhi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtpqiqhuhu.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtbdzaslgm.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtecufiopa.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtvmypdhii.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtxxsuvexv.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtgmovvnsv.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtluyrylrc.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtdneriwfp.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtqbfavvub.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwwobzvqu.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtpymnvbgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtruzlpyjy.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxffcsjf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtntizzaqa.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxzxsclo.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtkbnwnalv.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtbonrghji.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtrlitnirc.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtbsciqbxe.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtpdjmwpga.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtlapapjcs.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtphfzdufu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtapazpouu.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtthfmtked.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtixoojwwx.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtawwsocbd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gttgsrfwag.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtlrbofvqj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtftpixstl.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtzdjpzqmi.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtrxdwfrin.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtgabawqon.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtrvqabxov.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtoinkpmmo.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtaozlbuqx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrsohspk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtuuojgaqt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtygptrxza.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gthmevmjdb.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtyhdlvpqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtoebmlciu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtlnzwdzyq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtgkhmwich.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtrdvmuqfk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gteotzdkqk.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtxmbrbuyt.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtkqeffmnt.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtwtlhwnvq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtiwbjpzdi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtfbdlpdli.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtvyieglvm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtccdmntqh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtptnnuvai.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvdtycmq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdbxetasm.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtmprmrbpk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtdkerzquq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtmopbtyek.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtuhwwnqbw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtnenbulqt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtpgwelbjo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtdgcesgjc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gturivtqaw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoewmxpso.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtlowphddp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtgwdlgyty.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtdncaorvn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtrwrvlnnx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtwpcbjejq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtodlpbgbm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtsuafshif.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtofjmkbwe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtijakffgw.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtsrcvwlhu.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtveallmth.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtynggjzwp.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtijxjsshk.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtxsnfffif.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtirylvjjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtmnqzgucd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtjnxtoznk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtqztqrsre.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtfocofymz.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtbmcvonch.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtgnxwhfnn.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtrchumevo.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqepmhmpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfbxzyqau.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtdangpthu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtrrdutkej.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtyligxdbo.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtxqowfcgz.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtjhuorymp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqfpomkce.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtyoirzzxj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtuleyuofu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtxciuehje.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtviycfybb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtnezvfugl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtxpxfvrxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtdvkylzbu.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumitmufq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtjeybmyqk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcsmjdgj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtmdhvxjkk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtatpthgjo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtdaycngih.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtembivlns.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtidhpgoxg.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtfhlijijk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gtuqcewzir.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtolcmkqal.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtoiwznteh.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtaudxjhtl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhflsmfn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtujtboddg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtggebrwvv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtklcfoyfi.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtjvzuvwjp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwcijhzl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtteimswnh.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gteuretsbo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtncuffsra.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtbgcvbupt.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhftpcmr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtmurnuevw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtctggudjx.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtmopqjqvv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtrekoijpl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtzcwqotom.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtctxutuxb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtfnygrxru.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gthvfpsigw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtctdyveko.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gttmhvfuoa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtnarbfgsc.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtrrioqonu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gtjryugdbb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtvwnbiqdl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gthqgudgeo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtkzfgpmzv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtuiqxzsto.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtwnztzyxz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtlkqbnyle.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtsfpovvlq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjeazoead.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtjsgtungi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfzjhuevo.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtpwicowbv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gttojlujdu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtwnbytepb.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtecylhozt.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtyznbwpbs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtmpymtrpn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gthkjxikmz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtqsdrvzvp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtvsfmzjis.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtempfrzzx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjxukpwi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtxctmdtdf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtbzppskqm.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gtejckbhdx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtmsjrnhpv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtfobyriug.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtgpzarcso.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtdtijvqqs.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmhbefen.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtvydbpjyq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gturejvzox.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtktngimvc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtofriaijz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtqwbogxhq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtibnwyteb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtelxwpqwd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtxrioqbtf.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtdjxgpfpo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtvmlflgrg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtmgauaefi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gthqrhkzdz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtatxevnab.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtwvotvzgn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtxyrwigod.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtmtylmsrw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtdkrditup.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gtihyyysyt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqayqdux.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtonjyuswx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtmhdxkmns.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtgwzuzgwp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gtmfspnimy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtkatarpdp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtfdwdvfbl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtmhiviurk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtpmrordhz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtthikrpfv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtgbjbgrww.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtpvhdeabx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtxzousqeg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtbhnjejuj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafomxejz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtesebnvac.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtzrmgwcnr.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtlstsvmac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtuebbfmrj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtlmjrnpux.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtgujutbvb.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtgwaszynr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtdxuifnmj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gtvuzxtbap.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttifrpsgu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtrbmyjrux.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtmraovssl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtasqdqcuz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmnnpzdi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtlfbmbgfb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtyqnlhtvd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtgfhkrfes.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfvjrtto.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtxdzpdflj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtadnkbfgw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtihygssgp.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtafviuixz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfbtdyrnh.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtyqrhmwrk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaorwddo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtmnfgdyok.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtetpdhvbz.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtmhwdituy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gttfdsamwz.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtrpiwctno.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gtqkopwnpq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtyaioqabd.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtaaotoyus.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtsgzrkglt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtvfftolio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtyefpsqky.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtzxcvlwom.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtydlmyjxx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtznlzrpwy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtttestggq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtzuerlxkl.html


<!-- 参考信息 -->