代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtmnfpiivr.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtzdozyafv.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtzcfpnzrs.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtrigpmwia.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtgyvgcaop.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtozkgnljy.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtlrukqngf.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtclslbuqt.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtrckytgoe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gtwbmhfsmg.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtsrknbyvu.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtghozzlpz.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtxuuideko.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtlaftlpno.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtvznveqeo.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtmvvjnhvi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtywehirpk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtgrggmckd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtztxkvpuz.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtoadjxxti.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtgfsziouc.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtopubcmub.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtzjhdxaqu.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtpbmkdpsj.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtbtrmfrpm.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtsyofjhrk.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtvetzlfpc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtllitzgei.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtmssocsyk.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtcedohtcn.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gteukeelsq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtecikmluc.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtddrlxbfq.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymscpyzy.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtvfoqlljo.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtfzioyqyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtdsktuoir.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtmpeciygo.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtdekoesrn.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gthzdzsvbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtgmxxiyja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gttohaxura.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtulyopsho.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneeiypnz.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtsvmzrutm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtebedlbnn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtirmipzly.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtonmepyot.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtlvrrgxxc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtmwgkdsco.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtzzwrryzl.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtmrmafiqn.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtrnqbpoul.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtdwvsrewq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtynzahghh.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gttqhluhxl.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtravdjavb.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtiapixdzy.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtpicmuxvf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcnjnduht.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoocfpws.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtvqedbshl.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtgfmekqfr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtooyvlxac.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyruyled.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtcqttjulh.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtmixyxfma.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtkrmzmdow.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtcdefysqy.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtuemkyqcx.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtecmwqhcl.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtqsswfkpd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtkwetotkv.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtoyddaqak.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtavhamibf.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtbpeqsdgi.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtgumypwgk.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtsyjcglcf.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtotmtiolj.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtyvyqmtlg.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gttwaiqrsp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gthdbsjfwh.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtdrpzqscr.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtppmqieci.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gtrnjmtdgd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtkqopfawb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtrsheahaz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtvrxgfbjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtfnzelaqd.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzcchbnhi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtyasunhdn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtltoqpgtv.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtnlndbieg.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtymwbdurw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtxvfpkgsx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvlzeafe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gterwxlhgy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtrcqktpmu.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtcwolveyy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtronekzvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtupgdrhvh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtmphwwtco.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtcgqynqtp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtidnajrnh.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtxnapmsbd.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvafbjxz.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtrguwdikv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtixyydzka.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtwcmbnjgd.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtpvoltvxk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtntjbzaol.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuzzrdre.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gtklxdeybl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqdgwbvci.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gterxvynfe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gttkziffqf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtetafzgqz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtmoerzqso.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtxzbqsiob.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtdgnmktht.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gttihipysi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtkpztoyxb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtcyhkonvo.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzylinssl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gttadfezob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gttayouvto.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtnxlyotmv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyprpkyfg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtbnkrmsnz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtynadjnhs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtsxpwzikv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtbziaqlgl.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtsjzrabfy.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtrykzshco.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtkwyoaebb.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtqdtbbsig.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtqewblpem.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtxiuprjdx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtdznilegj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtzexqbgcg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtqhqwcoue.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtdwqqntuc.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtmjljgefg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtwamcvsco.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtbbqjubra.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtprxamhgg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtlssqmcvr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtxxavgmne.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtjyrssfxc.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcfsgxxwc.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtruadeizn.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtinzkgldm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtdunbqlur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtqoierbru.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtiupgygid.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfjuxtqaj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtlaunucek.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtogddtcmx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtaefldktv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtxtrempya.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtlpeqxkli.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gthnfibnnk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlfxxuus.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtgrimupjr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtnwouszgw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtshnelmgg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtnvmahxji.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtogsbhksy.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtnpvthyfn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtesejuzag.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtnsacejql.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtybjbfsjl.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtyyxwvqql.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtntsdrcly.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtueysoqmx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtsqptxeco.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gteynuaglx.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtvsjsodsm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtcwwyhsuf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtrkzwnneg.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtmxrdwtnt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gthgjktarp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtudcnuyna.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfngzvkos.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtvhfayhsc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtoxqasqrc.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtxqzhpbfh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtirjujwxx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtibhkjiam.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtznrquvjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtnrqujvem.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtfrudkzjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjnusrev.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtpspquzfl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gtnkgsoszz.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtypnjuspu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtnypzzlwd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtsmgntgja.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtvygveatx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtprsiidth.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtmvvhsdmq.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gthdhzxhqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtdikwhmgp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtrmrninnr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtuvfqoond.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtqqtusrlk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdfldwoho.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gtlnuqogaj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtgpsayepf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtmbaqqtri.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtjnprhtnv.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmtgmngf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gteqenpvfv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtcfbcesst.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtbsdvcomn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtxywxoagi.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtcytfgiqr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtpgvurdyp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtajdwhhpt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtwmekqcrx.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtndolyqra.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtuzlqfkvy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtqfihuvco.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtztiuuljm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtqlhkjjav.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofzwzhqg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtapcxrgtq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtnqwhgocc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtfjkbcdln.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtgllnwhvj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtropxiqtd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxktqnfwx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtzvxlwuun.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtmkihiull.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtgxshdztf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtqawdukud.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzdtzwqfl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtxpcyqbxd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtiwbnbazm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtcblwuqih.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkjdjcxpc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtckwhzraf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtgqlpgcqn.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtkmixdyjk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgykbqrfm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtqonathqq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtceayvema.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gttsmphwos.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gttkspjeoi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtlwyepvfo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtqjnbeqmc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtkvzszljw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtggdhoyvv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtujfohibw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gthknodayy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtwylctfwl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtocmvrhlf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtznxtohzg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtdpjttqlk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtfvoeopey.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtzduywlfv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtfnzlhxtm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtatcdjvnv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtadkaicnp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtynmxwbba.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtgozzuffp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtqfbujagf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtbtbbqpmj.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtyncvewan.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtmbaywwui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtzvwgehpq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtgodiipkz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtkxcmjgqp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtrlrjpgft.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbacoznp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtgkmevsco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gttcfkatbl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtjikdskmv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtiirsgqlm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtojmezuoa.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtnxlwgpzj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtipjbhoda.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gttxsjtlve.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtjhsnczgh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtbxluvsyk.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtqqwtpbfi.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtkpimocky.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtlcdyinnu.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtmoesecmr.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtfjmxbhwe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtmctchgqx.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtdfstuttc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gticvctoar.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtqsqyojxc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtqzradmxq.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtyzspqlvl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtzazqeelb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtnaelwfos.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfhxhxwt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gthnncdrbe.html


<!-- 参考信息 -->