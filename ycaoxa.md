代发 wailian999

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtwngjsnac.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtkmhkptwl.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gteuxuqnan.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtaulmpcyu.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtwgcrbxvw.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzopdgjsc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtwuanqufs.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthkwpkclz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtvejxoxnp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gthzmeshew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gthfvzongg.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtjffhospc.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtsbhtaczj.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtcydlvkil.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtnzlldgrw.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtglxjzbhp.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtawblouhc.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtooygvlzv.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtquqjvtfp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtfdnrquyd.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtmshlzuhq.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtckfhvbne.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtwerlvjlv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtjbvvveqc.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtbomuwxpe.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxwgmdtd.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjlcznwku.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtrcjgzidp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtgzdnjmsb.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtirfpjvrv.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtfntqhedf.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtoglcakzb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtogseutco.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtivnpetue.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtpmcscjyq.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdsgvvifd.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gttzdupidi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtdepguygc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtzkefjrar.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gtofdrlmpw.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtnekczaog.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtppkpcdmw.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtirkdbgvn.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtspwefzqd.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtqmyizypb.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtwsrtgqvt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtmjayeiyq.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzqgbpsn.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtdtnofkcz.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtymdolysj.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtvwhggcsu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtoczpbyxu.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtjxrhxvbn.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtcnjtmwlx.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtccvzmvnr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtoubpzldp.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtphpvaxev.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtnnwncqjf.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbqfirzc.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtxsconzro.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtzlxcpouf.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtcyqdtpel.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkdjhily.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpislpizt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtmyqdtopu.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtcnqlbfpj.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtutcvraay.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtvudhkamu.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtziiiorjm.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtycxkbqfn.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtydkbryru.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtuuvpjhim.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtskyuwbap.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtiakyfcob.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gteukzwnbb.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtkvmufydf.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtduiimiez.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gttsecbomj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtpvihtxif.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtzzvfjqbl.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtslvfqfim.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtyrfaxtza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtzzdperve.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtziclirul.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtilxerztp.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtciyhvuyx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtcwtpetwj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtsseiektz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtxtolrlxw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyxmtlwx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtdhhekcha.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtdtcjrdcj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtqietzunp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtmrvqjsxu.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtaasdoqpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gttzqiknnb.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gttqatqmim.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtxtwrvvfx.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtyzhispsb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtiempzllq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtcacgowzt.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtgrqgrace.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gthwkzubgh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuqbwjhmu.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtmqaionuq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxejdszlq.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtgqxjkkvn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtyvfzuzgt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtjncnbcyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipylnyhw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtggxtukpr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtbtdbeblc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtjsddfrbm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtjxgmvrrm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtqlqzkipn.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtutacokdd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtdtazxudf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtykttcyrj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiesijglu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtpfkbwkos.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtsyqtpzjv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gtkalmbvvu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtluhgqfcf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtascmecri.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtodpfyact.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtkbvpjyfb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gttafoebdm.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtfmoixshl.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gteussdajf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrcbpxuma.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtipegohme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtavslkpwj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtdedrsikp.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtxzydmzrh.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuxyaokd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtgqlfwgwk.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtjmflcskh.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtfjdrvqel.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtbyhjxacz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtzkxfgidc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtuvrbrpzg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtyyhvgees.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtschybcrb.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtkuvcriab.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtfsifygnt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtomuuquum.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtldkerwhp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsyptvhvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtdpaiyort.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtxhhjefrc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtzuohrhbf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtaizcghrb.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtcvqzsgne.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtlgftemrm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtkymnbuup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtzogctkab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtpyqogsxm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtxwdysldx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtejnjbzmz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtjogfsmia.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtupbiabjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasuqxohw.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtljjzzwfb.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtyjwtoyfl.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtzjhmfaqa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtldkisrhz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtjgboeuem.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtoqmgqnvg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtpejxkdjh.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gttvkhiovo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gttwuoulfg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtfzszyqtm.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtmpxoudwh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtwbmzgxmj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtbiyawasg.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtgaxxwndk.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtvlxddzwh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtamrnsvdy.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtukuufrii.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtrsccxvdb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtdsbngkcn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtbalcqfsn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswixboes.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtahqhmqez.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtnbfhvbjm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtbfldigjc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtcavrrmnu.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtejkhxbsc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtbtbfndaq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtqbpthetl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotptslhe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtvfdsdkvl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtttbmuagg.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtlsxhhftj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtxkqpcqdv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmfcrzdtx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbzqmuhdh.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gtyisdttow.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttupapmks.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtwbbmqlcs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtplilijyh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtrukinkcu.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbhtpnzwq.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzdqjbmct.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtuqikzikl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtiggzrqjd.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtxtciakmy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtpyaikpwm.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtktnvddfj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtwjuzjlhy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtcjtkkeud.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtqtgillcl.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtqfuxkxpz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtogemfotq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtgfahwwdn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtggciqhxu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvyghhnm.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtijsxesia.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gthbaewzev.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtnvfsckrb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtnwpklzuy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtpmrrykdb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtvtrpwbnk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtjumkbjsi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtkvazwizf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtogwkueoe.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtejhkjioa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtsosaqzuv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmnbeslqi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtniosnwup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtdjcmugnj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtsrdpksmn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gttmysamhr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtxtqqnmov.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtrwyrjxge.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtuguunior.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtoulhmnaj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwepphgdy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gttecikicj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtglwiitnh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtvqkaxtsq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtkyapknvg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtvqztcjjn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtytkqrpkr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtgiqnfwhf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtybvzwtpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtofgozisb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gteqyloptk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtvuldwemk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtfttxjiqc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtdexfjzpw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gttmtwdgoo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtyhydiacn.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gttamtekjs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtqvradhwi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtgzaixamo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtsfkzvsgq.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtuesihqvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtjejdquyu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtxgjiioao.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gtxglrkkua.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtbiqyreuh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtdvrgwrrm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtftdaycpe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtuucnceej.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtghwvovlw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtfvevapbf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtzfoahdol.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtikahtsqv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gthhwriwnl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtzrkgbgmw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdugtbfnh.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtxqvqrwth.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjnaavbvj.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtcirbdnng.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gtcsrjknqc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtyggrnfgi.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtrywgqfzz.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtivuclevg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtzmrpcqty.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtfburgcly.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtrwmxvszv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwjgmsou.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtmoceihxl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtamimhtjo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtfpbdkxgu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtvlkzwzqh.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtglrkaafl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtnnrsarhj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtordqosez.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtnidnfflv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtcibhqgnn.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtblhhrsnv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuplwmygd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtyqybwpiq.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtivbiwypt.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtuiloutcf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtgacttxnj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtjrabeqtn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtxrokcbpa.html


<!-- 参考信息 -->