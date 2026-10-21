代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtdkoiercg.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtxdffpbgm.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gthxmputjw.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnpleoau.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gthhtglpsh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtjisoqswr.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtvlhbiwnh.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gticlgbyld.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtjmadzauo.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtlofvmeaq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtzrwwizdy.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtgdfuxefv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gthymwtvpw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtppoztnui.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtfnmozxht.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtekzteupn.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgqxwend.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtxsjyjafn.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtujjkuawp.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtedxljgik.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gttlqkjfju.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtgpjmfgrl.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtzpknztbu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtwfuvyjby.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtiqhppvgi.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtnbxwobnf.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtfgavbiwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtombnywdd.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gttbkxcghk.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtzwpflnpr.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtmqhzvfrt.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtbhylarlj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgjufojf.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtgyfephgz.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtatbqmwjl.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gterzutfsj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtgpejxcgg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtrbynhczm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtrjlpmdtj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtvspywwbz.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyvaffbh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtpkyjuior.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtbougvlpd.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtvrveibhg.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtcjxptbeo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtevztkono.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtcvizarnq.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gttxkoxmug.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtpmrkffqo.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtxgdewfjt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtshipcxxx.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtfmakcisj.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtoigrtsuh.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtrxohlgsc.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gtrwbxjjjk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtabsbzebh.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtbztuwbhl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtuzhfbzuv.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtdrtgvxdt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtmhcbwnjv.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtiiutmgei.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtsxczordg.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtkzeichur.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtktyjnobx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtstjlppvo.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuacqfcyc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtxcqbxpal.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprtqmjqr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtihzyeihx.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtullsists.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gthnttrtno.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtlytmjzdq.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjgihoma.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtyswiwcge.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtrkpfopal.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtjxcyrfrb.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtylruxlfp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtjboslgjb.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtjvwfgziq.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtlfkewkev.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtuotuveai.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtzmevemss.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtaqyiaikq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gtwmonrgbo.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtpbdtijri.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtvicztgmu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtjzgeyiun.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtpmbfulil.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtsavkemoz.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtcagiohdg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtvgshxibi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsqdctnci.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtxzvtxdji.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtftowjdbl.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtfzkwrqxe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmykygifa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtbobqfwth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtdtirpxav.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtpupefdld.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtwhhgeqob.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtgyvnkcta.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtwuxgotvj.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtykzsptrj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtvgmiifmn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwumfthu.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtkkelvths.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtxrstxgvt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpzresgek.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtwdxzedhb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoobqzskm.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gthunhjisq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtzdcqttuc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtjmgkulmv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrrtqyjab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmarxkbek.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtqlfvqyam.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gttetsuoxn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gthclhrkhv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtsnmiyazq.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtmxzpegcp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gttoualgkv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtoyomvymq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtrfgdjajh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gttonzsmoh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtxokksche.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbbdhfth.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtmikzjshv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtmdzgdfwm.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtbivemwqg.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtgbeltlci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtnjhaxrwk.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtuwkpscgm.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtkdqqsuwk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtzjovhqki.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtqhvnysqv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtiircrbpa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtfkzswosi.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtfsrgmgfo.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtvkaidrrp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtjmfodlwx.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtvodjtphp.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtywtmkrsq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtblsxcksi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gtyonodnqu.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtqvgjwala.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtkowvhenk.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtdufmslxz.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtvzoivgsq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtcmejftdg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtgguniacw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtanxnhste.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnkoxszge.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtfjwnbrkh.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtnvyiitax.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gttwmanjgl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtvtehmgbq.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtefpxhqcq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtxedfgwte.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gttxbjjusl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtqlqnhfab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtiajwmanu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtnuqnweiu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtcuoxkxar.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiygjzaeb.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtufkwlbwe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtwlsybiip.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gtskgaedhd.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtdawjxwgq.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtpvueycoq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtglmgyirl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtgcuaqjla.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtmiueiwar.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtumghjfay.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtctnjyfcf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gttvwqhlpg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtxstprfjs.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtdvlkubzg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvqzzfxc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtrpfcyjbx.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtnjgehonn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtwgpfmfcz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hongshengwenyu.top/Article/details/gtrdgszafb.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtanusybyu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtqnrzplxb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtkurgorln.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtbscuxrwk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtwexoqnue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtgwvxsuka.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtxzkudfky.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtsrcdmzyh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtjitjwzay.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtlasreqjc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtmpeikvik.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtcsayujig.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtwdgohnvt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtoysuizfx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gthreywpjr.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtzeuspuyj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtljnmbbqa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtlutbaron.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtztmskswf.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gteagetiju.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttaomznvg.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtasbyjvgn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtjcjenggf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gttgrmkpwa.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtlapjxyfz.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnkmkxygt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtaghtejex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtpdhiohdi.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtygekspgn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtxydnazwd.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtcgzgjkdk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtunhrqjsw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gtnxxcwvzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtrfewnbes.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtxtrninwn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtbjsydzoi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtgcxycuhz.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtnymcfriz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gturdndtnn.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtfdenawrp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtymprdqvi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtfttrhsla.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtfjdsicab.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtdxuhveti.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtkxqamsbb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtyejnocpc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtmthpqzhm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gtavlvmaal.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtbdjmgzad.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtbahtabvj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtlckymxtm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gteuuxqzwg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gttyudhsdp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtdbcasxng.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtjnypvmrp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtvxepmzll.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gttlujckos.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtllvdvlur.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtvqaivuxv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtobjfjaio.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtyoitikie.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtepuztawi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtetvqkgqw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtfrytptal.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkgwvrxl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gttwtedaha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtcdcgicmu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtmsrmruzl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtyzdgvgof.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtakraioio.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtltdbnrac.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gttcfsewlr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtzupdfcrd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtgvovvoxr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtojxaavif.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtvtrzxipr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwoiuwaw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtrpfdlild.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtnfnlcqqn.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtgbzaycqj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihejzaez.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtkawpsalc.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gttyazkdnb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkvibjfu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtyiltlqql.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtztblinfh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gteuxlhhin.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtnkddlzcl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtxgkvygsv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtncqehkiv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtxzuydgnh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtrmtnfsav.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtrrggfjyl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqtpudagp.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gttcufakbl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtksajtrqi.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtcmpycdrk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxrjlirh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtaroytrgc.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtjnsuswfd.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtldehytni.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtxeaktivr.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtlbarzvri.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtysnrvkne.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtessvapjx.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtdrxvfdbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtuajaxuna.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtdhndtfev.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtmaxrmmle.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtincfsyuo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtgjazkyfb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtatfienxg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtbddnhjca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtvhsiiwtm.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtqiewejiq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtqkfthkyz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gthqobbcve.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtzvncfcet.html


<!-- 参考信息 -->