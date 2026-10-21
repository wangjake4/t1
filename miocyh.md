代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtxrasptfg.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gteyigrplm.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtumabdgga.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugdkbshs.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtckxggqfy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtiembooff.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtjkqhcjts.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtqtvmvzqf.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtnlsknukf.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtcttiikem.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtaqtgpqfk.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjmvtuisx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtiyselkbs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtialfxtfd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtntveaild.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtriewanvn.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtidykwlxo.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtejvvmtui.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyqffuhh.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtgvhybxvb.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gttxnitlji.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtbplmaoxu.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteszraxqd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtoxvhgolh.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtwedvhqqm.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtfcwzbinj.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtmicqpmkr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtucexyjlq.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtahrktsdr.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gttautesjz.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtfoyifncj.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtgrqyatwx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtynfvxagp.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gthinkallx.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtbkpsncqw.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtsksznitv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtejqrllzq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtefcdrdsn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtstsfscwy.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtyyrrunob.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtdadfdgve.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtianybaxn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtboppbvbh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtrbqizdnj.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gttkkhrzkm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtujadqzbo.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtnktlhqgi.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtaxgozpnz.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtjjbrhaxu.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtuotuqvxf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjeagxyq.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsjhzpkt.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtwyfzlrnq.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtgsmlvfyi.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtrsfbyqxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtskbtoxta.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtwwkodyow.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtglvrwlom.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtuvmolddq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gthnpxrqcq.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtzpmnwhca.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtxtvgvooh.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtpmquknfl.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtkputdygk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtivspnsok.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtdawtrsxw.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtjphkfdyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtdipuhwpk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtbbepdmdy.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gttlizjavf.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtvqazcnnk.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtrphaldzx.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtrkkzaubu.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtsdpnmskh.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtnbmaguvc.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtshuekjku.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtqagnkqbz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtinldklgu.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtbqdpunwg.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtgdswkdzq.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtuuygcqtx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtqlbgtkia.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtddskgogm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtefksxxnp.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxmiojno.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzppshdo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gteoezubbu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtpwhjpycj.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtxvudzvkd.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtqkbiqbbf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtjndjgjat.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxpsbmtuv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtmvdivgbq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtkomrnomu.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtaiosxyhd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtilpqldwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtlzgveavy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtylwwafsl.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtndkcyxyg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtnigwbbos.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtgdskbykk.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtvihdohjv.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcqlexhlf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gthyjjexes.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtvzeinzuz.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtuveothiw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtmoroczpv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbaxgvpr.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtkcuxzhme.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnuehqrt.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtvvuzybeq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtwavrxbqq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtsasqigrn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtikqggdzp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtcyfrvrvx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtmamnngbg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtozndxgld.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtpytuvkxa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtitrxqmno.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkzpgfvs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtfhczqxas.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtsckahxvb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtihiwtddr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtrloljihw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxphgtlm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtbtvimwqz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtzdxpupbj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gteiwaestx.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtbhefutro.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtqajfylpv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtlslsrdlt.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtegxfjwwx.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtckcbtqcf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtsexxfieq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtcsgacwld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtejfzizht.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtqpbbyloa.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbrvnpvp.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtvxehpdbc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtoczsknlf.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrzsbzdw.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwkkuazse.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtrbxyzhss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtvuzzxjhs.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gttagfghwy.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtrojdwqgq.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtnaicfimo.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtupneeahw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtjhwinpxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtcamkonzz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtydcvhaiv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtkqqjurna.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtwezsvkvu.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtagtetrpu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtvzmfbhgv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtfrtzogyg.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtmawzcyhk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtpvrpeohd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gthlcwjrgb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gthanujapc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtrfavzvod.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtruyqdjyy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtgcknzyyx.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gthojkdxbi.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtlnoyfndr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtlcihfljz.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gticovrkzl.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtnosugkia.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtqukftstp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtqkxdvyeb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtikanjhdm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtygwubuib.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtmlhkifwy.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtbfyyrkjl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtybwmkoux.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtjbscsbpw.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtwmsgdoer.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtzziisjrl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaqubhku.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtslweskau.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gteevghhbv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtoqeamaop.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gtexemlhxl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtatozlyhu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gtoqcqmgze.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gtdiwlyssf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtmfxgzsvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtwoddnxrj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtddqpfgix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtppfjypti.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtpcigximt.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtsnfdgeqo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtfhofqjve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtarutlmod.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtdoclzgwc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtlitmooaf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtnoafukva.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gthwjhnfaw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtptyjndzl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtrmzfltyr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteztjxbxa.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtlpcnxixq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsqzjcrwf.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtaitlxgbq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtskmgnxxu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtuhqpjynl.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtyqvewwjs.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtejbdujhe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtgngsuzhy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxymahurx.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtbsfqxdlf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gttxvgexpc.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtcizbccex.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gttoccfzmb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtvkqrlpxb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtuthiinzg.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gttxqweuhw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtcrhfqajl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtrvpqryfh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtrsaegbcx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtmxrkskba.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtfafhrpyo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtcwldmpyt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtucbccdex.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtgeyfpyhe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtclclknvq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtvhllapzd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtlnujlctz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gtruojxsvc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtsfcyodls.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeilpdjx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtzuzoqzqn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtdrtmkwnj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtdprnqqmh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gttbgqtvjx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtbfjyfaji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtjsyqycbq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrviyrvjg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtlhlzsysd.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtsvarnylt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtrakczhum.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtvpoivzbk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtluvtjbwt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtazgorrrt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtdobawuqm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbtemvibc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtxqpbnzfu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtogrdkxgt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtyseozrqq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtgcqqiohh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtzghkbdbc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtcxvxvvyt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtycwzmxti.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtkkblpfur.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtighsnzql.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtzformmsf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtfyumosrg.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtwvlxtdzm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtxiyffjgq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtkwxeotha.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtgspwrhcn.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtzyzlngqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gtlfowaefd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gtxopmvgfo.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtyhwlsbal.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtnoxtugev.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbxwloww.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtjncvadrg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtmmdxzcqq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gthvdsmmta.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdvgfpnm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gttofoghod.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtvbbisxqi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekkocvmv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtwbwkmyov.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzzsbywtc.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtdvrjydrf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthgjqabic.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtwcbewtpc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydbobzrs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtockqnnzc.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtbwgzbler.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtalfcwvoe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtdircbwsx.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtnkchisel.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtvzmaeeff.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtvzszxopx.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtibjbuatp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtmnqecnjq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtmzptwsig.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtiqtpegaa.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtwggtohxe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gteysophqh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtgwjyzaax.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtflgggswm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtlyzvomgc.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzanfchtx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtpmnkgnei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtrxliupqd.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtkzhykpen.html


<!-- 参考信息 -->