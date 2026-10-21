代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtwialwimi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtowupdcsb.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtdcdtnsss.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtpcxaewht.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtjfbtxqai.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gttkqhotbl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtsridiuqi.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgqjoekm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtcfeacovh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtjeomfiem.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gthbnefmog.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtfitvwvrn.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtvohuywgv.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtjmjolxrs.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtjzhgsppm.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtsirmzucg.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtrcxvojqy.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtjkfepjqu.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtzwmxfrxd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtpqoptrve.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtgdnhelpm.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtxchxpdfq.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtudqbrreu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtiwprvsyo.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtkmwoxuez.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtakyiqmdd.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtjwtvmcfi.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrziqhacl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtuhadgzfx.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtxqsaxogn.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtehfjafbj.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtubboxhed.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtjimrstga.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlksjxse.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtnasjzaaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtbswgfrko.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtydborvhk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtlgwbqslc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtortsocfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsdlwhyyt.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtznpsqurw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtqhkmacac.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtehuoobqb.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtfkoaelde.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtgpekoazx.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtahfokbgk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtrkxyhcju.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtjdeinwrv.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtoxjseuje.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtkpfthzrk.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtfjrqgfuv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtbytzxoem.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtitzuqfje.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtpimwsarv.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtpvpvxxsm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtkxayadrq.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtucqnwysf.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtiantjdwz.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtqvthfuaf.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtidskjksx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtrhaagwtx.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtgchyhljr.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtowsegpum.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtsfbxjdwy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtbrjvqaby.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gttdelwsbe.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtrqpjsnvk.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtcarheibh.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtcxzzbtls.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtwugmuiwz.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtbmqaibxa.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtzlsuarpx.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtwsxmltiw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtwenryipr.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtjnfbmetq.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtpywdvasg.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gttpzuagya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtrgcdalec.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtpjutybds.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtqbzltkha.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtyimbhmxs.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtpvrlfsgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtxqixqqzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtmqenymmz.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtdqytxwod.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtitlrtdho.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtgctitdpc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtoyvoeozp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtpzyxddkx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtadsyeqxi.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtdvqtwwlh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtgacxknfh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtivweyfyk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpwprrrvw.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyleactk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtbtjdzchn.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtogtxonyu.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtcrxzhpsa.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtyifltkht.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtpmkfgxiv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtntnjnbsz.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtkwxghepb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtwyqrabkx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtaawddokx.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtpewebbdb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcueeeqio.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtmgmjnqzr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtpfwhgurz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtdvjuiayj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtdeakzjuk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtnqvkcmym.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtiuxfylrc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtjftmzekh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtejsababh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtuqiwjadx.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtxpdhkyey.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtqxdnoicg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtnbpyftin.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtgbyaxbjl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gthbnviyrg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtgenlhajw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtkrcupudc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gttpnunmoi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtazrqrjdq.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtczdqkgnw.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtdsfzdlml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtsiwtfxvz.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtqmvobdri.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtvqpmsbsj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtubpxemxh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtsdowfobz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtctwopokf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqdpoota.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtbdbkassn.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtcnztnoss.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gttnwywhim.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtrgccfxle.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtqntefmvg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtxoguqxrt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gticdikfyr.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtobpezmuu.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtwqdtvczm.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtrpqlduho.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtcrsddqvf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtkvzbefbh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtvnghfhid.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzahkzwbo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxggmdgn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtknumnhsw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtwbwvbqxa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtxpzhqvfh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtrkuduyuh.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtnuttzqtu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtbrpzviib.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gthdlfraja.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtcmqzaafu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtqjagelnr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtogeqyrlr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gtzdxexmqh.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtxqwbwdau.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtobtnoq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtguwtahwm.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtftvwccfi.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtnnbnqbba.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtlpranuuk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtlzyqxxvh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtcwotnzsd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtsxbbzsgs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtzaequbgg.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtnktnedwb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtkdcukiwe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtkuajdcxf.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtldaentzq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtarjsgpxe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtmxdfxvqk.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtykagydkw.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtnkygznle.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtkrujcvpg.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtpfzoyvww.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtiwdiocso.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtduwtdkaa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtsaxlwsrs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtgbrqfnxp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtrbjhvymz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtmmynrded.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gthbkzotsj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtkitdfyti.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gtgaxvxggy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtrlqpydjf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtfwqrwxne.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkqowwia.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcakutoq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gteawyxsiu.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtishzstnr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtifsokcap.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtbkonoekk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrcbkqaue.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtlzsemxfj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtysnawolf.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtvqsrvdng.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtrfmkfmle.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtsmtpiyhi.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtuwsqgepy.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gthwrtirle.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gttotiyrry.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgeqoyhzq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtbijkomni.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtosadednr.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtuwswmxks.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtyuzlxbkn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtutzeeyms.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtywmenixh.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtngvpqxbg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtvmtajuyr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gthamoaxho.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtrwnbetwq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtsyljvmnq.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gttlxceale.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtxbkbgjvw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtwohzzjey.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtxdirpzri.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtvzgaflny.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gthbnwxrrk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtxpaarcra.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqlxlcos.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtjxfvcciy.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtlvscwspa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gthnsfojgn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtgxbkgreu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtwecusslx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtumscgmms.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtlnsoiwtr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtujsszeqd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtauuzfakd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtsxgacbip.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtdyzkfige.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtrgmqpstz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtebgtiitn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtbhzrvdxx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtzjjcqmcl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtiuwglrqt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtwjsxlcvw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtnapebbid.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtyesujltb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtkcybvrdp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtbbejfntd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtrivzkasz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtgogpalqi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtpxhyuqnj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtpbhjburd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtdtzxzpvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtkysybtpi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtkaxtykcm.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gttjodxota.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtpzfmdess.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtiyhhsrdh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gtndxovugl.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtdazxdlqu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtbjuleufi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtkvowoycp.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gthnksmrit.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgvfziic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtakmhekdd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtpnxzfijw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtligykefh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtoxfxszee.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtagpspvnt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtespokril.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtpvtczfii.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhrdqgfb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtbgzwzyhs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtamqcdxyh.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtiruzgcdy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdskadusn.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtkiebypje.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtemvgakth.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtfapvlqlf.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtqyakcryb.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtfpwkexkx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtknuhnlle.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtkilguedw.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtvxjqgpli.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gtpxzhjgtr.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtnhqadgua.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtcivxcyul.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtdprrcrvk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtatbxgbdt.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtpztuztom.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtrisiefkb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtdhvzbuox.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtjhsgwifw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtmxdvkibg.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gthiruiuhm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtrrvqimtu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtzxkfxcsm.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtaftcpsoc.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtheycfprl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtnihclsgp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogcumehq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtowfjsuys.html


<!-- 参考信息 -->