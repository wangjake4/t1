代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2uqeiwocs.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2oirbgsuo.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2mvvvpmux.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2shamrlfu.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2nolythdh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2queewagm.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmreomdk.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2svieutbi.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2oyjaahco.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2qisuzzza.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2wnqbcioq.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2iwobkwiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2jzyapaxq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2abqosbop.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2hfimsgra.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2xutodgur.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2ogsbwxpl.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gt2bhhancdl.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2mnubghji.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gt2lutjnhba.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2louypkwy.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2qlwhvsxv.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2debasfcd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gt2nkowvixm.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gt2qggzhlpo.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2kedyddtb.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2fnvdypxz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gt2jhaapeml.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2vjfdlpdy.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2iawuiuwm.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnnqiwdo.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2bzpemrhf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxlbdqff.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gt2etqlipmg.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2yncrnltu.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gt2ipsbiqnz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gt2kyifjslz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2xzacyrfk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gt2xooxtjra.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gwtvuclh.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2uiupnqrz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2fhztafgz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gt2gvrjfiae.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vvgysbit.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2httbeulx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gt2tgzrlxzn.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2geiiycyb.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqemmkbg.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2yjuswliy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxzvlea.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2jrmizmfb.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvtavvzc.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2hzqagver.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2bgdaahak.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2iagsfnqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2djmuerfi.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tfgingxj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2omhimdzi.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aefupuok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2vnflfcom.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2razkytts.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gt2xjmzznpl.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2dtrnpkzx.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2tnicnzzh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vzlkcbyr.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2dwhritvo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2cmhfdlks.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2uvsqypru.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2wsbmlifh.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upttdtpx.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2jgxgdidd.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2cwhffudj.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaflssqj.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuzygqon.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qndnwrga.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2gntsvejy.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2whsmaspu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tesaskag.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gt2toboykdb.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gt2amilnlep.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gt2xgoviydf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiaqdlkb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2byiofxjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gt2gjnyoldu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gt2ihlorgjk.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2zeskousm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gt2rskkjvog.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gt2dzvaaltr.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2rjsdsgfm.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2clbhtozs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gt2jxzkylbw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zverwprq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2bioukdby.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2poqawzbe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gt2mssezgsf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2topcofzw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gt2hsmvrvhy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2iwvltxcx.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2yityauvd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gt2flrtugcn.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gt2ffngmkux.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tozpuoxi.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2dguzvshq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gt2kijqeuyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2qbvsuxpi.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2zoopibvv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krrncdfy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ajvhixnu.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2zvkmfkdx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2btklmebz.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2tppkadho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2abvvknfl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2gckfgqzw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2xicnuhlr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zguyzvtx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fihadqyv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gt2gccjfoaw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gt2nnvpnszr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ckdfkzei.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqjfsmlw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gt2swyjjykc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2xyifdbim.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2gqlkdfou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2fpjiavyw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2vssxnhsh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gt2zrizdxtd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2igpjkkss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2zmqwlykr.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gt2akawdwyz.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2qcbwxdbh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2pecvdtka.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2qbfbaoys.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2dnjsasrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2ezxwejsf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2elktptpy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gt2ulgfrivy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zswcbhis.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gt2qwbgbzov.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2rwvnwqle.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2uujlwuxe.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gyplnelt.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2zgkauepo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2yjqduqil.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojumnvls.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gt2brmjjxsr.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qdknpdod.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoztcvpl.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlfnzdot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2kfqomlya.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2eklwvrys.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2dtkrsjgl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gt2vdzkjdph.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gt2ashlmamh.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2nziabrsp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ocqwfaea.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2hwcmfulu.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2vxvoloyk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2ctkjkvzs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2jzhqanfx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2echgyafo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gt2kekadkuz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hovhnfcu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gt2hgdpkxwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2uccvzunr.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gt2cxksifoa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2jlursspq.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2fmilcolp.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2mkhcczyi.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2mvnmpava.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gt2miqnoagp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2ojipdfef.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gt2defrptvi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2yhinwayj.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2pxxybuyk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imesansr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2nsaxldzw.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2rgjsejng.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2hyzllynf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2cicojvxl.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2mthxefqv.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gt2xomovoqn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gt2lohgvkpc.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gt2iwfsxkqr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2cnxuhsgd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gt2fnwieqqk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2dcecqukm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gt2urzienpa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2bdmmonku.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gt2saaalntv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2ykogdjre.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2evebsbpl.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gt2qfmlvrbq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2efxpqojt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2uuavsopy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2ldzadrsg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2jdzfmyrj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2jtyiskim.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2jiiffhgr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2msqlcalr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2hbtgrcdr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2egtpyhmw.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2bwnbzsny.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dadtqlhx.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2enikglss.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2crcpkovb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2bcybgnee.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ujkhqrtr.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2darglaxx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2brxeurrz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2styagtbj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyfcgyjm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2gvetiooj.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2cllauauv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2uzdhcikk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2toqamonx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2ojhokgpr.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2clcwvmvi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2soocfkel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2mxgislmi.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2qihcatxl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2kvjbfyrc.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gt2rugpnhdc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gt2wzwqfvgp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2sszwykjh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2lpxtkxem.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2jkhzvubl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gt2gzjyplog.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2dtstuybp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gt2vthmtzso.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwqxvgnn.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2xctswedq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2lerpfplg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2wrfbegkr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eydpswpe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2ctmjudei.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2qwezlzoe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqqelosb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2hprnvprc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2lfuqqlog.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2nezrykfl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2vbcwhvyv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltoyieec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rigrccdm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2uxfxfvlz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gt2fpuepgci.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2cezssuhc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2ldahnlol.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gt2tiszbspk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2zbcegpzs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2khzemfix.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2megfaffd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2zcppqudu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2jmvlklai.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2pzqifzze.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2wygpwsiy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gt2jbheddww.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2qtzqrocw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2mcglokmq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2ksmgsqln.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2chzecsol.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gt2oubatjat.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2qfjdjbqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2rkmfravo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gt2ynarcnsd.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gt2pdsteoda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gt2duakquki.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2ddtezegu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gt2zcyoxglp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2dbbfteef.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2wqoworpn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2oepipyny.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2smpksgly.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2zcndjfco.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gt2qdcxksxx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2uzgoldiw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kykchgqb.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufbzvaui.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2sqlrbesu.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gt2gnobxsli.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdskfhlk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2udgraiud.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2wiwehwtb.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2lykboilj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2leasvghm.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2nrpgekof.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jljogaqf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gt2qufmriyo.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2rcfjuvow.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2esggjrfk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2iqmffmsn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2wjkbvddp.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gt2lomltnok.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gt2bnvjrufc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2trrqlong.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2nfvrrgpm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2qjnsvmls.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gt2ineatfsp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsddfyfr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gt2kcmtgrsk.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2kbuylzgp.html


<!-- 参考信息 -->