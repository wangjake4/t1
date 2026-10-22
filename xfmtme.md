代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtmxkxkvnm.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtvvbfthip.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtfntuoxei.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtkdkfdbwy.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtuxcnztiv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtifclkwug.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtbdjewcpl.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gtjinakrlw.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtnpomopzj.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtsktgwzrb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtfsymhgsx.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtchzzjuig.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtvteusqfc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtskleirbq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtqolivneo.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtoryceqht.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtautzmrgp.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtzhpzsmil.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtzeflhypg.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtawndpljj.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtyfyuwelm.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnotovnmx.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtbhjysbem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtpybicllm.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtbfwxjlje.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtvkmfbkrt.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtiaiewoto.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtrwuwyeit.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtkbfinitc.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtgdiypzmp.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtxushlpdj.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtqhhmjfum.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtrajcwqlq.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtwlesgofy.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtmumvdjrb.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtbkbfxfph.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtamdyvcsy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gterdrvtgu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtrmxcccfl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtvhdkiymr.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtuecruoke.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtjpzoslwv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtrakqqsgt.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtmgpdoefi.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtnnrqbkti.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtktyglstz.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtlsufeexi.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtxzhfbuze.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtvxxvyjgm.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtugtegrad.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtaikjqjdl.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtqwmgxstn.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtkpxddftf.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtkzhachjv.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtrkmtzhxn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtajnatyyb.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtmizrnjks.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtlixlsnqv.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnltmoery.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtlgzcsfwx.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtlrfhbqpv.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtntdhocjl.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtmplrhwjh.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gthuzfqllj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtzrcmjazo.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpznezcap.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtohqgcetw.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtfuertpem.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtkbwtgxfd.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtdglntvrn.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtxjjimckw.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtzvfhmtst.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtqmhhmosu.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtrctnsmwq.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmjlnqmj.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtcmwapoyk.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtphiirqov.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtljbnvjce.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gttcwvvcdg.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhooznhr.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtbxeqycza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtuaqchdnw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtitgmwmjn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtyeldguyj.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtgtymgnkt.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqberhbmy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gttlzryoay.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gthpbalddi.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtsaguejlm.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtmhlgerlo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtmgharylq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtaqmdykar.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtrdxndodr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtprfljizi.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtopvfanzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtwysuizoh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtuzmvflzw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtscvbfoeb.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtqwofuwqv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtkeccjcnm.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtpksdpmxy.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtpmjaafhj.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtfnoyzbgl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtyhutjjkr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gthvdmzjzg.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtfwglzitt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtebwnzgba.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcewaxggg.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtbypzokpg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtajpazsja.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtouxtdsuh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtcncbbfpg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtxlrfmfls.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtahthbtas.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtekeihihq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcadonpt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtyooiencg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfyhxlmu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtkgnqfdem.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtyicvvymy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtjlsxpwcd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtubwmkbfj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtsnfezgks.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtslnmbsfb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtxoiwlsjk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtuecabmim.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwxbndoss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcrihmbwr.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtriqroise.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtfbmyswfq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtpfifcncz.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtklguopop.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtndmbdcpc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtykcjiaww.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtgokjvtgs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtuucovpdj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtxcxtnocv.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtlvhtnbzu.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtzdurnsfh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtfoxhrccz.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtpyqzsrif.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwmrfmqo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtmccybdxh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gthkfpxvis.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gttoufcqmf.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtoiiklghf.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtkmxudlbb.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtbsdfmtez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtuhtzzsnp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtytmtyrin.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtbsjaluxc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtezwxpvqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtbqagrrro.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gthauzygex.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtawdhrtcr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtilimfngp.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtcywjjegw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtbcvkuksk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gteydwottv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtogbkictj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtcumukgyx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtxwaqtgeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfvbprtc.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtvokaibfv.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtmpjjshyc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtwixhazrn.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtvqnsgfeg.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtgnhuglja.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtwckygmum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtmpmnxhwy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtkemstvsp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtdadhwfax.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtbgldsrav.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtdqwspjtd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtlyqelwen.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtmcefhfyd.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtclvdifub.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtosqvlaqk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtlemlryat.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtqxdumvxl.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtzwmbgsfr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtoghnwfdk.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtrfynurtk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtxtiqoqwr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtnyqwlfnm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtxkcnvojg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtojabpjqj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtimmmanrp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtpfabdfem.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtwfiodgbt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gthjgowgae.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgrsfvjc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtlewtvcue.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtoffnnanr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxmxfjpd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtcsbpfden.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtepgciqid.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtgusjhzzb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtcizvfgoc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtdbqzaedm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgrfadotb.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtdvakvcqv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrqnwzvos.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtczzqqedy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszykcdzn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtughgpqas.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtnpigsprm.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxmisdrbm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gthyivxjze.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gtrgdoaqlw.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtjidezyju.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtrvvaanib.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtyqcequzq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfneduarb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtepphxotq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtkcarvjzh.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtcfaauzuj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdwxysnu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtucvcofmr.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtfjogtsik.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtgbludghx.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtdldvfxrk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtufrhgype.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtsklcgdsc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtkiawcsqr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtvsjwmzvk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtspskxolr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtqedaerjd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtoqzniskw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtdbduymfb.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtjrohrjyi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gtaxapozql.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtxbfuvfxf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtzvjpsseo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtonwfalbv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtzhnhmiab.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtxoophheu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtdbholyrj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtpjnrjxtr.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtjqjsfgpn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gttxnfbwva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtwgylfqgz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtongksedk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gthtyoclao.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gttyvlhfgj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtifdzyipf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtteiyacpm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gtywgackfc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gtmrykknhm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtrkmzimvx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtjkteaime.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtnpxadlux.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtgngfmuzm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdrhkqgc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtwjvhzvis.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtiltnojnl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtcpnwgmtk.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtvnjjyxde.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtlzivszfa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtjvowvexd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtvwhntvrd.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gthwwfgpoz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gtcbwjnwkl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtkhujiiie.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtbpmbchss.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtpnvhwhql.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gthuejinog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtopyobhdu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiwaeujf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtovkeglke.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtvmsxaeux.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gthncsnvsw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtsbgjfpcq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtpzujzrsk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtabnewdsf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxwktxtic.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtmashmjnh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbrsyegp.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtjvpszjgj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtxsbundmt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtyxfzzoli.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gthrhlkqmr.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtswbgprly.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gtphuutsnd.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gttfhwdjbi.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtgwoujyeq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtepjsksri.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gttpjoppyc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtoppvtaqb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtzdxmkrxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtjckpoavc.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtznvsqoma.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtvsgvdnjm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqjbtfmi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtfgncfylk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtvvxpexwx.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtflhavein.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gthtfctaxf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtnjyweeey.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtzzybrula.html


<!-- 参考信息 -->