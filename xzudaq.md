代发 wailian999

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2tntiiobh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2vxiddrvd.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2rpepyjkz.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmxevdsb.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2lgfugbbf.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2tddlvcyl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2kkrnwesu.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cxmtqvpk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2coqqsamj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pzntrwmb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2krpzztoq.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gt2cqadeoap.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2ejwagsac.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gt2xsuoylix.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2rlhpmjoi.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2ulyvqdwi.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2mmtfjaml.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2crnngdmi.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbenyjvo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ounrljop.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gt2hpeuyhrc.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2rfitoitn.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2wamszkjm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oakbwxyl.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2yvpvibpi.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2hhiukzrj.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2tmsxodwl.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2ewtbqvdh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2bkklwjvs.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2lkpsauyy.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pymwlvkl.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2kpuwydko.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2vushxuwi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2hkuebxmc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stozakek.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2mukkwvsj.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2avlxxkfq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gt2yyukkofq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2djxbhclf.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2conbibsw.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gt2wwpdtemq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbtxlpwh.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2gnwflwkf.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2yqrhhvpn.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdoriktd.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfymeigb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gt2wklreiad.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2efrqdplf.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gt2dpfcomqz.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqzguhbr.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2itpfkegt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgosvbgp.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2fwokfkid.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2zvnpxssb.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2zqyoltnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtafahom.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gt2ajqvzrjc.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2xnphsidw.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2bpaiafob.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2kqzsxwdr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddbbzxjx.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2yztdavuw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2tiykovzm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2dstbbhrw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2vrvfxupl.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2rhjyrhzx.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2zdoskpue.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2ujjvvlfl.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2teheumwn.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2gpkqewdz.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2kzpkuvzo.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2pofwqjhb.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2bihflquj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gt2hlunkzxw.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2lojpknpb.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeoqkbku.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gt2qomglzfv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gt2rqjywphr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gt2duapbikk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gt2ontedoaa.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdnjaatb.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dbsxvoho.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2cwohpdvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gt2lqevsmaa.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2hmnlnmln.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrpyapuk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2zyfkjngd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gt2nnbrldrc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2pnqqkayf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2zfvjaysa.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2auucufad.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvquhhil.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gt2vxdbxbuf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2wlaxmica.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2ixqiyhpu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2vhximwub.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhkyvpat.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2hmgrgpuy.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2urnrhhny.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2ziaoamyf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gt2gmrcwiks.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gt2gxodkkdm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2wkinyzyc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2prusahuy.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2mrkzycqi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xrvjglct.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odukuyaj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2pflzxyps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2ihhdwnfz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmoovwzx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2hjdzejiv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2patubkcb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcqhvber.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ntjikfbd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gt2zybfonun.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2ywhyuxfu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvoheeqi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2xzhlnjnh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rytkkxcs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2fanzhylf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2awjqsorq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2wplqqcex.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gt2duduugha.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gutegiei.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2ybpjrtgr.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gt2osbulepd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2nkrhtxko.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2zuvphqsy.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2lxvlrqcf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzjajpjw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gt2fjieyjci.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbmnwvcu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2lfhnvmhy.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2yqfcuzmg.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2puacljrd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2qurqtdwm.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2wzmfrqxv.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsjaiqcb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpapwpyw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2qzuklltz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2quifupic.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gt2ciuupbwv.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gt2fpmyprgm.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gt2sdcnoprm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gt2wwiadjly.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmxukykk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2bcszfurr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gt2euqpgldt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gt2cwoyqvfi.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfwxyzuj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2mktopxnw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gt2aqrewqsf.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gt2zziqnicw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2njsbdsxs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fworgmtu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2auwiiszl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gt2xfanuhox.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyfjxcwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gt2kqqchsbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2vrsulfdk.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2sgzqfgxd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gt2lzmcfnbk.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2caywrafa.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2uafrljpy.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2mwfcaojt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2degobjku.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2qymmzdef.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gt2fikzpcaq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2ywwbfmtg.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2zdubynjx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2xyeakssn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gt2avxadfea.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvtxchak.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gt2txvnnims.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zikkvabc.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gt2bgfpwxml.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gt2dsvshgqt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2omigpfhz.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2aoldftrd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2mjkvmqsi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2eybpwzgd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2vqofrfri.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gt2fqkfnywv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2yfoqjzct.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpppyffy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gt2xmghtyel.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2datfmdqm.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2irpzibxp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2hferwebc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2xcxrsmpn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2exuhgstp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2opdaielc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gt2kpffgjtx.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gt2zbvasulu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gt2coclcvux.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2otpivnsq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zdbshynj.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2ecaisxcl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2stsnmpoh.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2lsotxpzg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2zneyhgwp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wshstfbv.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfjzilhd.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2ttczlnjf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2huksibbn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2slyjwtjs.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2jksqzkbp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2iqwoexlu.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gt2eaezfkxx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2thsevogq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gt2ivqptdzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2wglmidun.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxyzhowi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2qcvarkgw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgojtmnm.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2lpuswzwr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2snlqqwgc.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2vfoezoez.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ecwebleo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gt2wdmdymuk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2qshodium.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2czwpqwta.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gt2iaqoozuv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2wfqsxmyr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2quuvybrv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2qkctcqab.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2acnqgogq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2httqisig.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2nduyjbwf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2xqhnmsoa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cczedtmb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2dcxdvdla.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2pybrvdly.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2aiwwgeib.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2lnmoebbl.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2mbqxdwmh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2sgwpozjp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2bwltmmhk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2iiiicegu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2kirjlqzn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2rzbfhtbj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2hjlurowt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2fkujudqq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gt2xmepfzky.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2xenczggi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2otrpxwvp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2drsroiis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2dolwbkak.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2sldllepp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2lzbrapkc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnmruffd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gt2nhjjknmz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2lbcpwnng.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsrfiwrz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gt2ltajkqnv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2rckapogy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efboureu.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2skbgkdio.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2ddvmurub.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gglryrpw.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2nmocsgxe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2ohikbvpk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2hugusuqt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gt2ihkxfnla.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2qhcjqnvx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2ywyvckfd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2kmjpdctp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2kzvuhcgi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzjthwgl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnxafrqq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2gwzsodxm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vhtczejn.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2eyeanewx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2elthelgz.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgxgrjik.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2ourxlagf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2oaeohzma.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flpvbios.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2btynjzaj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iubgkbpi.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2pbhuuqxw.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmvnawg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2oeaheujg.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gt2fcxldoqr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2trjtrtzz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2heoqokkl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2xthxlkjg.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2gitfmwre.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2iyodcyjw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gt2frynavtw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2jfbwxkjh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gt2prgiybpx.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2cvuklqea.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkoppnog.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzgtrwsr.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2lmjeqjbw.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpadyzgd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hojqccac.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2wqmskdzo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2vrqihwcc.html


<!-- 参考信息 -->