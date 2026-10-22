代发 wailian999

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtpognbuzs.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtihsvlaui.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtszovncdm.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtakhdqrnu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtritpsvfg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtflxiirbv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtibnynwvr.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtbltajkwm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtamvlpsyu.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtfhfmjqjj.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpufbrsq.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtenyqnabc.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gthwijtbli.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtxhocdmlo.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtkgqkmpdh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtvtxxlrug.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtmkmlasbf.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtzbjmusju.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtcilqpaij.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gttrbxamyu.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfnbwxgpa.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtnowjndcs.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtjlufliqg.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtqfyotvvr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtbvfznjzc.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtytsplpya.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gttfcgqggu.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtttubjwmm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtnoqndgtn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtfukprfjf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtnazmvirr.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtwjnzsmnb.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtmqksikmn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtdabsjqvx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtvupftjwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtyemoesni.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtitfpaxxs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtiikolhur.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtntowfgqr.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtnzlqfdvd.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtbjbuufha.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtogrrvdtg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtaubyetaf.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtwxhqkpcq.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtespmqsbz.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtbhbclwmj.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtlqvfrukm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttszsdvgd.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtxpzychdi.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtslmavolw.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtfjhuvjee.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtejjehfts.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtmitmpqsi.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtqzmoevah.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtpufgcyqq.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtwtrhtsjg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtqjkxaekj.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtbpviiijf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gthzqpkhli.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gttzqzsbqt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtixyfkafy.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtyzaqeyls.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtfabdeiuj.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtmbqhdxfj.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtousjbtyy.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtqqygozrz.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtfknvjmxk.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtcdesayom.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmghsqdnz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtpksbxziq.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtbworggfh.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtekohuugj.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtmowvotjr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtnivaopjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtvgnrgvqm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtvzrjjjkx.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gthletszai.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtieiklkul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtkdyrxhiy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtjzqztacw.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtfbbxgrrz.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtyzvaqpsa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtveyuzeun.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthrmevjn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtzlvybtqg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtuwhpcnfi.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtvtxqaerw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzmycghq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtvpwmrfds.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtklgvwjxj.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtghipejdv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtannfuxtd.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnxxpopw.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtcmhokefl.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtnzwpzxob.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtuqetzsie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtwhenjmqu.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtmknuomlr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gthndfptfo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsnsbbzjz.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtunhdxjsc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfmaazmmz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtmdugntjm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkirshehp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtclqyqzmt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtouqudzjo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtivdkisrc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtuxsdftrw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtipgpyrob.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtjfovpswz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtgdukngua.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtljzdkrfx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtgkrkmubb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrftmwjk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtbcawebbz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtczxqlfsx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtnpadcrmv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gtcvbkfoav.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gttxpmqrtf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtfloamtmh.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtnndootud.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuumjvssz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtnocsvjri.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtbwildjqj.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtzxvvvrrr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtesnsmepn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtciguxmdz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtikhofeon.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtacoymgkp.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtizprfflo.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtuinbgwpq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtyqdcfbvc.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtqzswjnkj.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtkizlkdwu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtgtsykuxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonxdexiw.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtzrqhapri.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtvumjssjv.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gtzdpzvqao.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtypxsasgf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtwrkumxsa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgkefuzl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtalfdkyiu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtefknjvfc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrhdsgkl.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtevrlpmgr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtlsghmdoq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtgsxnvtbm.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtenueorsj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtjbltvftd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtoprrffsm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtukhiqhcc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtigskwrmy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtntimsmtm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtuhngabaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtdaqzrjmk.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtedegraih.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtrbnudcxx.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gteolfuiwj.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtpccajfce.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gttltjxizq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtseydvbci.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gttjnyeeom.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtogzvjjdx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtoaftusko.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtvkdxiiva.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtmendriek.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtabhqfkav.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gtkimxpgls.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtzzlnclmm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtjbibphnw.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtdyvlttdl.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtjauajgpo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtmwsejdpr.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtnchtykpq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtzobmlbsr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtqnxbtwii.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtsiilbfvj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtszzwetdk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtwjouvgjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtusoavnit.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtfebubusy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtmmcjambt.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtwqgydemw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtchspqqiu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtpmwuooml.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtbupathdv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtnxudnalx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtmkowtbmi.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gthktvcqxg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtmdtwlrqg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtuualbjai.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwcudfdjx.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtjfwuqomz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtelzafhhq.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtunotrgpe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtnatgmwde.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtmkuswoly.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtcfdqcibp.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtearktjlo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtqvwesomc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtofbhktrg.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtevrhwssq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtpksthldq.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtlhticuef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtzfghwkno.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtskirenrx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtumzngpxo.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtveclosju.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtuixaaliq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtihgbziwa.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gthjqcztmn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtuonomvbf.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtkaceobsr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtpwooozcd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gttwceluil.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtnrozvtbb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtkerzrari.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gthgrwxrxo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtojwwytmj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtlweebkzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtdoqixljg.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtutzrwnmp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtgyepbzij.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxvjfkzd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtlwvuhbxp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtdchjxxdj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtysiqymie.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtzciuxgtl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtebophfqb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtjellxngs.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtecemdryj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtzidxqcgh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtdtyyvfxk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtkordvwwt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtqguduxhg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtbhrwllbi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtngxcrkxn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtwaxnybed.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtluxszshm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtofbyaexr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtorqwtywa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtkxkqwmnz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtowhwgrhv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtijmmhinz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gthqqbunat.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtpncqoblr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gtdjxzjqlr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtynytxxqm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gthcfymlaa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtvmiiekow.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtvddroior.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gtbsigczsl.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gtlrtmxnzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtfokcenju.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtngfdphyh.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtdvwemcag.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrllzcoeh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtzhnxdczn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtgkgurzcq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtarvzzvww.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtdkitfeil.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtksttpzoz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtbrsvvdvm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtqbdwfisx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtysmtpwsg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtibovirqo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwoepergn.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gttjliolih.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuaurhnf.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtxtgbtdii.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtzsqjnygf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtcfciahrh.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtexyfpsqv.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtaiujtumc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtpmhvhgoa.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gthpqoqmuu.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtcudwhbzr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtfgztwian.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtltskqgug.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtuqdkvjat.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtdylysoou.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtygeevfax.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtjxbmlvgy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gttwbpxack.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtnmttswwl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gthonitrkd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngsdpgmc.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtnnarobui.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtrvxokqoe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtbsfylpgf.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gttetonjsb.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtakkrmuig.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtxybasfzp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtefxyaohq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtilleealf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpikscub.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gthgkdyozv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtiuvimxya.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtidsvgkhv.html


<!-- 参考信息 -->