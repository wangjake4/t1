代发 wailian999

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtycawuuvp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtmnmwovyx.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtaqjarhsh.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gthmkqkmqu.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtouolokvo.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtmhxhzuiv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtbdkmkibk.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtnsdvddxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtuiiwzlrj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtcmhhkaer.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtwhruaouy.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtbumxlpns.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtqayqhclb.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtojsbrskh.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtmxezneec.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtnjvyword.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gthrhaeuxu.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtazpgfvsc.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtcbvtzsdt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtdvfinyuy.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtssfshwuy.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtfshnnmfx.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gthtieoawx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtgyjvbrah.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtdbpernaw.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtpnsfyjrz.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtozhhjayr.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtpkdvociv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtaeuqsnfm.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtqupyhesj.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gthcsajigu.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtbnjmruhk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtqepicmjy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtfzubxpkv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtvbrrgfzl.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gturinlurr.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncberioe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtefzfglgk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtjkpnqdmu.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfyzsawo.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtufbrdxwq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtfeppgxlh.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtwkzegdup.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtcyfmzhpg.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtynvmsjup.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluxirwup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtumkyguys.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtgcotbezy.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtjclzhdjw.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtorztwvvu.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gthnnjhkwn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtbevlbxjy.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtoaquocku.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtkepefsvj.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtlcexnaqu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtnwtifuzm.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtinbkwsus.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtinsiwdif.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtjuzhdtpo.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtrjqmdnop.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtmrtqgspz.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtbwphoczg.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtggdeljxw.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtsrmoocer.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtksxjzxvs.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtnhlhcida.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gteolprdpg.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtkabjzcci.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gthdqhtjww.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtpvnkykav.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtbdqmvfwh.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtghkdzglh.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtmgfatsve.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtntlaeynp.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaglwnsa.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtsxqtwrxv.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gthbgtcobf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtegnctzku.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtmxafrryj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtnyywsqrq.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpzclsnz.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfdomvmkb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtfjlnficg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtwyqscwdg.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtleathvlm.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gttvounqic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtiuofbvfj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtbckayxgy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtcyohukvz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtytcmscpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtmxidhbjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtfspvgcqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtpehsirps.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtonvhnzjy.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtkdauvslu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gttaujbkaj.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gteavgolaa.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvatetsht.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtebeuhjbw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtyzskvxls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtwqqftjux.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtlkirfjld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtyrnaduyo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtesadgfpq.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gtaarshlxa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdncwqub.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtzgrlemvx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtxjadvigj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtnuctrbaa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtidulgkqb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gthnkpubvd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfdzxmuo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwibqopp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtboqkoyqc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtuoqwukfj.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphcagtgb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtbxyitnkm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxnacrlrl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtjcjdqyjf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtcqztfzhb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtukmiohtt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtcteyqpdc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtgmyhkaym.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtjwlwazko.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtderzmaps.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtlriimjfz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtsyybvkdx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtvrogcenx.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtrvpfieaf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtevzvbmmk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtbnkhresk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtznhggucb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gteimjpvwc.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gthuszrlio.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtciybvmlo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtdlscpsdg.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtqjzlbkkp.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtnqmuxbey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtsgnzquie.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtgfyyorvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtrbkgdibm.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtgjveaaze.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtqourmwcc.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtpvosrcyq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtvhiizwmn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtzbuvftur.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjudgrjvf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtfwpqvtor.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtmkvukytb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtqyrzxpqq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtapcssrug.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gttpchkfbk.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtdnvixofw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtegprfjzj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtscvazggf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gttzwtreyf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtozdtavfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtdjuybrwa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtlduncqjj.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtdyqjdaul.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtatecepgv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtoabchjfl.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtkagsdwhi.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtrdfzuvey.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtqlquecqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtbfskueyx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtmfkvoowv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtplelfmqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtipkkmcix.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtcasqnykl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gtyzcqdpzz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtkrkbrloi.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtefxlwifz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtpepriafp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gttqhndefx.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtjlighsub.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtzwttyban.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gtgarjtyvu.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffcobyvo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtftzyjkew.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtpjpsvccz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gtzryzainy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtwcvktyea.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtzidvlabq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtifpdnjwu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtchquxwsn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtmwqydikf.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtiuisfwxj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtbywuuz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtakfioloc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gturulinny.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtygfztlsl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gticijxljs.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gthrhhatgy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtuifqcvez.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtauywvvho.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtelwpocbe.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtmisnugec.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnbyqjeib.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtdfvynsmu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjpvbyqlo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtmljnxllt.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtafblccnb.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtyqdlfpdd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtjsjmnsro.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtejsykacn.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtkhowzlvp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtsnrqrrdx.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtyidhtdss.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyuqziil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtrelyqutr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtedpokawi.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtebjfuhyc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtjhnblual.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzscdufu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtkbnfecrz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtjlzkhneo.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtifiazjob.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtzozpnlvm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtcmhztyia.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtehxfbzcm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtoaqjwowi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtffrlytue.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gtjxlunkeo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtoyrthqmz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtczbbbynj.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gteegqctds.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtmfipathh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gttkggzqhs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtbikwfiqb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtcwjvgtgx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtagpyeyjc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtlgxbicth.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtcxrazlrv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtnvedrmfj.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtspatmhkz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtpupuhswj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtxmlexjhn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtdppxtmtc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtvomlbaak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtsgxahsrc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtdsdfzxij.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtdlwokqss.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtuvwnquem.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtrdjelvvs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtzjeyutko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtvootojjq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtcibalvbb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtianhjokp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtmquyduju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gtapgugpgn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtthkgaukl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtebeyosxg.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtktutnbjk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtctgdxaos.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtrzttdrzz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtyywaybkt.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtbssxfupj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtzdldsedn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtbwppaucv.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzawbhuhy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtkwbgcoqz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtvlcdzpdy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtookoswoo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtotxlexfk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtfrgzjutx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtksdnruav.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtoqewnasx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtkfebwdsz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtkfmtpson.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtszpclniu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnlmxuoyj.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gtqunpdnvz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtqifrek.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtltmfpuzx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtrjotzutb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtmzbxstfd.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtioipplkz.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtkxozjiyq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtekrwfmuy.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtctxkootp.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gthonfefgv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtwsgbojwm.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtwrkdauea.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtmpafcdug.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtgpycdzva.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtcjovihyq.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtysivzkaf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtkqxwaesj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtrrpnemvm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtnfqqkiiq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbsvafyz.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtyoezhkqx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtgetnmvzt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtxnjldamj.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtjzqmykqn.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtsjgmyyur.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtbqqxzepb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtzivmwxio.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqaiphas.html


<!-- 参考信息 -->