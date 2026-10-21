代发 wailian999

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtujmvtgvb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtirduzwil.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtnwlmyaew.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gthxmugsan.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gthkjjtgjm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlepceuq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtuenyqmaj.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtefmxhtmq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtkxjhdozt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtrbgxytqn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gthsurpbjg.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gteofkcjzu.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtoavsthvi.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtblcjthzt.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtxjbnrxjv.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gthdvtgpkl.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtytsgcwnx.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtvupsiaow.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtyfkwtsfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtbjfbuedz.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtrbaweipk.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtzuksyfme.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtwgryxsns.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtbpzcqilt.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtwlvalsvy.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtnamneqoi.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtdxtwapqd.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtusrsyaec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtqpnegxvb.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatqipphp.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gtdndixhss.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtzkakmnoz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gttinxetaf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpildtvqc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtypzajodw.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtbrrtolds.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtitdtbgyi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtcpcpvwjz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtbrjkkhux.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtiaxomvjc.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarshqecz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtmgrjurxo.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtkujzcbaz.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtqaqywftl.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtzsakockj.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtyuoqtrmy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtmqtanvso.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtnpjukmzu.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtlmqvowmj.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtngmxujil.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtkjgrqiks.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtuutdexeo.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtvalkgoup.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtomkmxgrj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbjrfyakb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwiwqcze.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfajlvwv.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtdiomxqnt.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtupgmsmft.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtlmbcnvgn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtcryenlum.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtvtidbadd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtiqirnstj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gteanzqrom.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtikswigmi.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpvdnmbdy.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqrbxnxl.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtkrmjjiwa.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupjjimdh.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gttxxpqdkd.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtcsrokyjf.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtelgsaaen.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtvfceqiif.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtvekfsblr.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtukryvuys.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtqspeafyw.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtdhcmdqjm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtfptcdgxg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gttvbkjjpl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtyzhuqiot.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrqqauaf.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gtrjfkkblk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtdokewtmw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gtmstfzbbs.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtksevbwix.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtvykobbxv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtetadnryu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtiasjyslv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtuiidwfiy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtrdywnfpc.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtqupqjczu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtogphvvot.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtxquxkfmq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtdddrtply.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtblxaovzi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtjndzwgzr.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtgcttmsvf.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtuwzqwpfq.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkmpctyh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtxdgmihvy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtybunufmh.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtwoerjoww.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtxpvbpmhj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlnowugea.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gtafrggnoy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzjiyrtem.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtkvjuajng.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtffhwbyzn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupyupkqf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtrmalduep.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtbjoovljm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtnsudekqh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtrfamgshy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtfgotbaki.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gteicfffrm.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtunsdwhaq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtqpthqoce.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtwluyyhen.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzhyrwktj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuibvrcc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtuhrwdgrv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtfmxfdmnb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtyrvytruv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtcazdicvv.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtapqqqnvf.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtkgdsymjl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtpbtzcpgt.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwezklhwi.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtsefctshy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtyqbssshz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtjabdsapu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtvorljsan.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtgjpuxhcb.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtqjieebqf.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtbhezamkf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtsumuejqz.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtfkjtptyj.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtxbuxqdvs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtsjyavttg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtohhvufoh.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtjwhwvrji.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtkwfvobjo.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtegmdokdm.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtdsjruihg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtkzfhifhk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtnipbgfvk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtatwbjove.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtdbdamrbx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbtweoda.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtzeyxmrit.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpmqzrfy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtwpdfsaop.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtdscpuasg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtnwnxoqhe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtggjjayea.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtkevjlsnj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtltcncibw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gttcekkkyz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtsemimlcu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gttaegqxbh.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtonwacsvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqaxymtt.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtrgbsshfr.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtlcjsudly.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtsepciiqt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gttlcvkrwa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gttmgywxbj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtbkfkidpb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtgtumygpa.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtobmwjdsn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtkwyuzcgd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtijbcatbo.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtuhfvlenr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtnjmxektu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtlcapybpn.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtfooqmaxg.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtagdscdkq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtzpvjtrkv.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtxkwcfhoj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtwedtgozj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtxecltfol.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtyajacwnt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtcggwmsix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtoexkcrxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gtixhhoxzi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtwypnfnrf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtllsddqda.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtohkuugsy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtsduyysil.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtqnqvmkii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtidrsmlxt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtpefagund.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhengqikj.top/Article/details/gtiqbqdlgu.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtghanwmae.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtqdhqwufu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxnqiuid.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnbzewhkl.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtmhrsymvz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpqftuvjv.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtdvrfrarx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtwovpyduy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtbczuqccp.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbslgptm.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtbbuhoavs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtflwirytj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gthnlhscei.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtwlwrenjd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtrqpvoeen.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtibwkrqoq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtzaaivexs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiabajbw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtphtnqrjq.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtccngeell.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtwewabulo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtiaxayyaa.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtshmpcipl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtwssrnzvr.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtrhxeafdf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhhrasfr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtuehvomtx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtmzvypyob.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtlqzxmmbw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtfurlwapw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivqqczvh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtbeqcsfkl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtphxwpawp.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtodufvaoq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtyjbhvoyf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtffddryoz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtdmejpabx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtowpmyeqd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtwxugphmo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtahysxkoe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwqptoam.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gttstjyydj.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtunidcidt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwtuffbv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtpegqrjvi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtewytofqd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtqntkftsy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtzralzjcq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gteavlxjvf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtvunuqfpl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtcikdazpx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyhtlmvk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtkdpgjfxx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtlpvcjusl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtapctcbxk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtnavfiofq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtponiupbq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gtwwhenemk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtnemtmwag.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtdecyzicw.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtazskeksm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gthizhiwuy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtlzewayph.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtyktoklih.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtqvawndhg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtxvnuazor.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnlmkfty.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtnqdssknj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtselhkmay.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtawtslxui.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtszvlztmp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtpttztnoe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtwrtgfljn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtxllomlrm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtfkoxtnjz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtblfhqslb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtyxwnmgqa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtajjzhzyp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdczxcgfv.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtvdqxzdtu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkmmnjvxb.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtsfkxoplf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtbvaopmgn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtoqgspesi.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtneicsmlc.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtxfpkzdst.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtlhakuvih.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtpahpljhy.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtxbhudavj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtruylwnyy.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtdyjczmbo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gttywvnpjs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtvuinsnku.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gttnqscyxq.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtbcfmzpar.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvujnqdvx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtpskdflsu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtdhtyarwf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtdnpebleq.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtewcdzzcy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtborhlfbq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtwupifgyl.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtrhwqitpf.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtijwvutac.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtxouvqwtm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gthqqgtimo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gteamimuma.html


<!-- 参考信息 -->