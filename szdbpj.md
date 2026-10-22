代发 wailian999

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnaxagvy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gt2tsvotcew.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2vjohutaq.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2gqzdhnwt.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2sslqvtmj.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2dnjobcuk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2glxvbbra.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2lfjsljxo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vplpyplr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2glpujicm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gt2amdrmlet.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gt2ychgqcoc.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gt2ukewrnfr.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gt2ywsjgdlh.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2eldezlzf.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2iadkysbu.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tknlfsmf.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2ymyiyugb.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2kdtmelfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2wmgcnbgy.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2msvupexi.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2eqatbbxn.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2qwvbntcq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2twfvvsyt.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2mcukkuhi.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2hdejahyf.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2dnmeoymc.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2aigmqbka.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2dygyvtoe.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2xhynsicm.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wfypdetl.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2bpzmadjs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2ceuxaaut.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2mwqufegp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gt2svghhwmy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2vzkbqbkp.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wbahlihs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vikpwgoa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2eocxjnap.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2bqkmoyjm.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gt2ljhznouy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2syhopdpk.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2pwwlonpn.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2dmwspmss.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikjvfiyi.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2voatadzv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2zgixnwmr.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2lethimjy.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gt2aeiatnfi.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gt2wwhhwrao.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2zwjbfmhw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2afgzetbc.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2qunqixfn.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dkyzpiah.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uxxynanj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2wbjlgtqp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2plswxmiv.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2oopomvyb.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gt2abilffoc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2vfpovpmm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2vgllkkye.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2pvhmzqfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2jfsbawvx.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgfillsj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2wqfojikv.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2fvoyapic.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2vybubnjz.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbwerotp.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2rtadnmcd.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwdmkstv.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2uhxskycr.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2fvfkbdry.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2csizzdnb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gt2icosmjov.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gt2svjveblm.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2jmsrcikr.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2pufgggjk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gt2rhyuajrs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2rhfbiqfc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2dmpoehxi.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeonbaat.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gt2maetdxbk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2lbbfglvo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2sxfjesnf.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kszkjdce.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2oorfjkuy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2phnuysju.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gt2nzyixscr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2vymjckqn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2ttyivnvk.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2jamhzlcb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2vksgbphe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2sftumtcq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2rpumpudq.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2ubfhtigt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2jdajivfn.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2jojlwlbi.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijmppdbx.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2jtogmpjz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2utygaedo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwixygbu.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2dqezauqz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2mjpqeynr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cpqleyvt.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2pewbsgvr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2drasoksi.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2rqfomdon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gt2wbzfamcn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bapfyeky.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2icigktuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2ykbatczi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2yocwmzpu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gt2tueevgno.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2ecvvmelq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2efjbrfml.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2yrilhxal.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gt2ufhvtizj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ttuavvsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tshucnkp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2eyflxeql.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2yfcjqrik.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvdyrnto.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gt2jkuqyhzt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2sbhrrjrb.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2zzeveftk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2diddgyqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2hjrsbegd.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2pgrzioap.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2nyzsoezi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2cyfbcswg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfgrzows.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gt2htljrljr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhbnipvt.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gt2rxckzatv.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gt2dbpstxvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2vgxcygwn.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2taaudxtl.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfjcdmfi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2jgunutei.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2awkskwgq.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gt2eaxdbyqs.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2ddfodpcg.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2avcumbyr.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2kqndhftq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gt2hefyxusg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2vlzyujqr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qlwdubyl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gt2iwibaqwu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2wcqcomtx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gt2aitpclmi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jvenrjcm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gt2gtdfjmls.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gt2avegyvkz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2paupkxgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmndepop.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2rdermwmc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2hrmzyktt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gt2gakzxzog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2inmauiwu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2ilpvkcjm.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gt2mvrmjpoo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2pubgvork.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2esspbrlg.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2metbippl.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2exebxzyr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gt2fjhzqmlt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2cjcjakta.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gt2fzfilzai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2ucsflkgb.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2dmdboslz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gt2sjkurlgl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2upjfppxh.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gt2kcqjojch.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gt2thnwsthc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2tmgnhmmp.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gt2zjthnsmj.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2mcbltjju.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gt2qowrncaa.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2eowbrjxe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gt2efwklphj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gt2ludzrrmm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2rlodhxek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2pscahihb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gt2docpipia.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2xtpsvjgw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gt2pquhwphn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2wlcyiaqa.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2bsnybxdd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gt2njptnxhs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2ecscioiv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2tdfterkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2fzxypzgt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjxthnxy.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gt2sszgyydy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2tpfbrfeq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2slhlbbuv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tkcykaie.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gt2jxzgxqbr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ydosmfrp.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ttmyfkgs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2oeywavgs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2pnegrgqy.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjavizew.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ugbuaban.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2adyzjxaj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2tptdlvhr.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2zwxjxcld.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2dyynmvvy.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2yapfmrxm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2nhuffzix.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzvjunoq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gt2dplrnqvq.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gt2cneegrke.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnbyptmm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2qsqndhqn.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2mlluylep.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2mqdcgexp.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gt2jhdgqzyj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2tzveldqb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amvnovnn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2zaxmkamz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2iauqfyfc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2xedwcetb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2wzposigx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2smggdujm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2ehwmxqnw.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2nlocrjyy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2byoiaxbm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbvvfdtj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2zichzafg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykarxbfs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2ojmqfqqu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2flqqqeda.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2luyifkgk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2cahrdhbb.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gt2hidcguca.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2odfrmfdk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2ujxvdohe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2arhkwwfa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2tiwkxoww.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2whaergkr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2wynvymds.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvngyjn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gt2dyfmflef.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2ajtioeaa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2dbbnqzjz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2czbmydfo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnipadnk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2kczivioi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2ygptecjy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gt2bjspfdnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gt2crcbguld.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2qejznzut.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2dpmmnsef.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gt2piuciyfb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2rkgazigi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2cfgphres.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gt2orkuplis.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2jacqednm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2hufdelqb.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2cibxsczo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gt2jboiosbe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2wqvllbmy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2vfhblnjo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2hoqrsuqo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2ytvoatqj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2uxrlpvqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2rwngeoja.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2bjatvdla.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2eikodyrd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2zrxwbbtj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vexsvgtv.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2gagjcibk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qcadqius.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gt2jlqefgrt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gt2wexgxdba.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2ktgbuocn.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2xayvgzzo.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2azeclnwk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gt2xnsdssqz.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2vwypghzt.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gt2azghzckf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gt2qqouwxck.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2lrjkhnet.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkoymlir.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2ocohecnr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2qcbslddm.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2xpjslprh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gt2lauyofiz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvdyozl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2skpcdnmh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsywqugo.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2ottxirnw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gt2nhddwxwe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2guybqvyw.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2jiihlert.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmtvytxk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2xhuxsfug.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2fxqwzsii.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2elizkdih.html


<!-- 参考信息 -->