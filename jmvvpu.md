代发 wailian999

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2ostlvhax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2qiffirwh.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2qazozpgz.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2qvukebbc.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gt2nupiskwx.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2wmtytyim.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2pxyvfzia.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qbxneudv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ledhapug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2jmqxzlxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gljrwnck.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gt2vlpmznet.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2bnixsfee.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2rfzwoult.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2dkajqrti.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2lnzadbtt.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2xjichwoj.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2aenzwbky.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2dkghihjk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2gkwzxtgv.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2ahhptxje.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2joctufwe.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2tpgmiujm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gt2ybemzybh.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2bqayblqp.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2ducogugs.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2bqhcwhev.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpzkggzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gt2ocvfjzax.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2rpxykosg.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2jkkwsqar.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2xyfeilya.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2ikmqvceq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gt2ysvdsvcu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gt2agrdseid.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjexdvrk.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2hlcahkds.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gt2kkliiweu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gt2ievmwqsp.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xztxxpwj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcumwbu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2cenjfcxh.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2icalpjxt.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2xdfhryee.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2xqijokzy.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gt2lgfkugbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2cxlplfcx.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2ibiltxqb.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2wbnrevgn.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2afzmzspp.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gt2icvcwmoj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eymavjhp.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daepbifc.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xxzteguh.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2dtjklyzc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2ocnitehi.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2mhpecwue.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cinkrcwt.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2wicbbicd.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2zwihdysl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2oovexzcn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riffjtqx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2rnlvdjkj.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2wvjfsnsy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2mhcbikom.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2lsfowywm.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2yhmhmunc.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gt2adefjhlz.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2jvvipbbs.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2ubylbhvq.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdedxwct.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2xzqfwnbo.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2pcvsvdlz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gt2qarzwiop.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2bsswvuiw.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2avsytsmq.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2fegdbgpp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2yyfabwvl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlydhuoj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2qucidlpa.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2uwynkgog.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qgnmxwea.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2kftlksky.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2renhwgdc.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2wtvhodlh.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elzebcmj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2mpjyqrtj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2frmszknw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbbfijak.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2wbbcqvcp.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gt2cvqvcjic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gt2skjlucqr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gt2retbnuau.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2vrgkbzwl.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2opqgbhbr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2iukpyloc.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2tlikfamd.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2vqbdfwtq.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2pexhllus.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2poveqctb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2adhjinhh.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrevaour.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2chardmhx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bnrvvswi.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2krpdbyvk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2chpbgczy.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gt2tbmiqlmv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uokfqjkg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2gudzcarx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2khbjlwfy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jydewndx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gt2xtehdrni.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2fdollcni.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhuuoruc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gt2osbuzwmw.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2qsxibwtm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzuxbdwq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2urijspeh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ateejrgr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2zatpvbnu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2jzibbdxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gt2qeqwgonn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gt2rooyzxux.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2melmxojo.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2phvwrnjy.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2nbuzdjqc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2robjcjqx.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmplzamb.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2ptngechb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2xamcjzvw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2axwwijea.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2stqbsedk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2mvdzvlcb.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2pzvfaqud.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gt2ngkdcqrs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2mfzdehvk.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2fpaqzjzs.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2rwzqmctq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2qpxvxfyr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gt2uxzexjbm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2ihaqlsum.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2buqudbro.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gt2clbhhlml.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gt2cxgauvoo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gt2giyykiut.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2loutzole.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2xawxoyty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ccbupkct.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2vlvoxyti.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2cymlxkye.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2ydhvwprx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2fwzhbylb.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gt2tucjdvym.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2yzpcarev.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2yanmosrn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2tbgkxcvi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwraugnz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2kavppify.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2sryjmxus.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2eupusikl.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2cpojvlrp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2jortcmij.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2mkzfsdvw.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2ibdvfsca.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxvpditc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2ntlzdbsc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2lufhnino.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gt2jzlqqdjg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2xjtwxkir.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2cfcylhjx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2mosnfwmr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgnxcjvi.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2qklvcwwj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2gawzblas.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gt2msbltjns.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gt2etwefixt.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gt2tyecaudo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gt2whejxyhf.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anhuztuv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2aibaxlek.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2opvrlfnb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2vyxwtyaq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2yvkevkzr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2smqsdllr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gt2lkufovpx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2aithtssm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2ktviuevr.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2ljulmbbz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gt2cbsvtgfs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2carmxdgc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2uqhyevhz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2ohuippjm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2kbfmtmto.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2sbpevfaz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2aafcgixn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qbshbajb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vubphcys.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2drhqfrxx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2urxexmzo.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2mmwsjqco.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ohsiieak.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2bbvaxshu.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2zoseufjw.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2eplgszjc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2jewyneyb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2zcpqbago.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2akcitqto.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2bnukdhlq.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gt2qlzxyzyz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2qyemkbqi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2guujghub.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2maevjife.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2hzudvrat.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgglukmf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mckjegfg.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2ibibqqbl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2prqzbtrl.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2kugjdloz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gt2jijtywar.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2jmnsodfz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gt2dhkmfdbz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gt2umhjxdev.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2ufmerhbg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2vtdzwrhf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2afjbyufk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2dcfsbabc.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gt2icfpysxu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gt2xjpgudwi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2egqyhytx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2sdshhthl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2koqedifo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2qluioped.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2bnchnytb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gt2pkzmffwv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2nuqsocdn.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gt2yygmfqgt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2gbrtvljg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2jmxpsdqx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2fbajhnor.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2qqkwwjto.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gt2uerjtawy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2uejmxthj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2pptnloxu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfirikvk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2riuevrew.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2nxuskiax.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2ncfzznve.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2lbsbbqji.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2rackhohz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2emzchdtk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gt2apiqacvg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gt2jppkdigb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2sysjdosl.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gt2uikhinws.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntfabsfn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oeihbjbu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gt2askhrgfv.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2yzwbymro.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2rtvzcmho.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2zmxuljkt.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2hwpnhbzj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2rhihrxca.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2ncanvwuh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gt2khqwvvbm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2dcaeykvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2zsewtjva.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmxpnsur.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2lwbjrayr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gt2ofknkzxh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gt2bqknmvnh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2dgluvxgr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2iweagweo.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2aumzwxsq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bjdpvhto.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2gwcberzh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2umysmmlj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2modvuohn.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izakhjqy.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2gkuhrgcn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2hknouplw.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2hdpfvwga.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2uvlargap.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iimjfike.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2zjwfdkkw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2vznezgkt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2zdqgybpf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2ighlleiv.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gt2ciwmllno.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2gvhchaix.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gt2bupuxgrg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2mujoosbe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aslburlu.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2lwadgtkw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gt2ljqdptbq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2uolggzmb.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2ezrqwgme.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2eaiejuqg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2wzadfpcz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2oifkqknc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2kawnrolx.html


<!-- 参考信息 -->