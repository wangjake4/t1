代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gt2dexseycr.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2gxiygynr.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2tlzwiclx.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmqjltte.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2jsvjasym.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gt2suqvgues.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gt2vrvypxdj.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2ueknadzn.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2aheppnri.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2cjbnegcw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2pnazibnx.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2khcrxhme.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2jvhnapza.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbuztvru.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2ilqaqmdj.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2owkkqylt.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2nzlgvxxk.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jofvskod.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2rycdhjcq.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxyegnax.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2uxtqviwv.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2xqsgqcpk.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2hfflufnq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gt2wyczyfos.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gt2vubkhffa.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gt2uptuiwjf.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gt2detsvasi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2rurxlsyi.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2ydaldkit.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2hjtopdkc.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2chqryqig.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2suycmmhx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2spmmgqej.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2jotjdjus.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2lncqevxu.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gt2wtdwkrtt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2qsvqtbgl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rzdqrfdy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2fidramoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rezhvpfc.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2wnumwfrh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbmaqtlf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gt2ykktsaud.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2hzvagjxp.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huhcvwtb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xttoubkq.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2llzsuige.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2tiprdjyb.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2kqrhefsf.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flnpopvu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftnowkfv.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2yjpehspi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2afliospg.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2aiufkful.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2jsvembpv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2geilzuug.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2xetzxdnj.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2ykmbdshd.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2hzfnjijw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2whgguvjj.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2hcomhmqm.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2imtdzgzw.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2lchsynhv.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtopexyj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiwmruym.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2lhtjtlii.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2aycmdczq.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ysiamasq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2qtqdhzcr.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2ptlskzuq.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2tktqbght.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvzsfhwt.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gt2ielbuzmx.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2wuentanz.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2qjmamrab.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2ctfudguo.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2udcdowke.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2hwknihye.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2rrcqkbcl.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2uogqakki.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2zsbcssrm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gt2bjbzwven.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2xpvhipbk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2nuictdyt.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2bjjwpftc.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2siyfouvw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gt2zsmxufon.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gt2jadounto.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gt2vkyjboaa.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gt2khnhdmqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flczgpkp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gt2zpxkkqtc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2tvpurgez.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2jsjnqmrq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2rtfqelot.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2tepjshfe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2eryunvzp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2szlpqhbc.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gt2pmrcxxib.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2zdnlybib.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2ulqebizt.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2uqnlkoig.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2zgishkkr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2fvdhsqdf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifkchluj.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2vrxiaxql.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2sqzqvbgk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bqlnmmtt.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gt2atmbojvm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2mbuzpdcz.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2vfrimrko.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xplzskgw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2ciznbtcn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2qjrfvmff.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2ssylulpm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2icbtfvhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gt2bfyidmrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gt2rbshtsui.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2fgiwjzgx.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gt2excmzxtq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2blvgbmcx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2ddcvwkua.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2vlnrcpjg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2ezsgyaza.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2nzffjrrk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2skmlimll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2szearlgl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2pzvsilgr.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2plryuugs.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdyzxzrz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqayqnue.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2ljrmbhed.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2vpyqafya.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2bzygkphw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2wznyvqca.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gt2ctlszsex.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ctkfixhu.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihcjklsi.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2genziebk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2uyhfiskp.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qzfraciy.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2rxpfvbzv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2njrnokim.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhballsl.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gt2hsqswofr.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gt2fryiobna.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2ixmcpdwa.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iklbdmux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gt2slryzqcr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2mipwaxyc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2kdmfwlto.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rvbipqzs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2ponnryxu.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2cdxatvmt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jrjqpgeq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2enmxbqwb.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2sqhmmxbv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2jcsyompd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2msgozoui.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaybebda.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezrnoznm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swvopkyo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gt2pxoqihxh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gt2osmikbqx.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gt2nbzuxkrt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gt2olbrtbkg.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2xblxxtsn.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2oerbnkcf.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2kmeoblzq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gt2owovxlvj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gt2kmrkisnz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqmbxdlk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2sydvdjly.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gt2tfpqcqft.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gt2desllnhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2tsztmfap.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqeozyho.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gt2jfrvpyzh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2ntqzerui.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2lisrfrbm.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gt2raggzywr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2uvehsnfr.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2uvmhbyab.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2kanjntvp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2lrgneyka.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2qkxgucxp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpstblpd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rimydwcv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gt2xymttlgy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gt2udejsfzo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gt2tbnpxezt.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gt2frllmrki.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gt2rdxxomvp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gt2wjmqtjta.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baasykrm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2dzhfmjqk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzzlqubs.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2sdowapwy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2rpwetppo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2owmmmmrr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2npthwrrg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nuduoicf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxwwpusi.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2pskgmyig.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iobktqrk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygyzthbi.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2uqmqmygo.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2bhmcozbn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwzizqju.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2yfigltcm.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2skmhmpmy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2ddhhxylm.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2jvkrkpcl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvmynlnj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2bxftcnrt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzoocez.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2wjdwvdey.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gt2lgixmgeg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2xoitcyiw.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2mltgmavb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2iavmeakd.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2phrkhtdh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2dxzfybvt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2zhnesryn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2nkkdybgo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2srfjxrca.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gt2yybxispk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2zboecqbo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2hjdhcevw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gt2jzvedhau.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2gthatzcl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2cxvdmgyn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2lkvydpqe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2jwpymvee.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2ohwovonb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgsmyhdm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2hwtyijub.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2jgflbwpw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2nshgzmge.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2rvhsffth.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2dxytbhlb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2jeogihbo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2umjqslmy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2zgkrddlm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2krpbnnfj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2wtiowsqg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2xmcpdzju.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2tgjzoacu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2flhfocqs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2tozlsrls.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2tvsiptdu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2zwzoineu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhojrttm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2evkpifxr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2tayksflq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztttaqvn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2cpjficds.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2knccmarc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2usevzieu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsgutntu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2ssppyuhd.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2bspkahpj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsirepec.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2elhsxcip.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gt2rpyizfbc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2qiuaxvqw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2nvrwexgh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gt2zmriydry.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2pxggkusb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2rcwijdok.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2bsogtnbm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2fdksvayc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2cohpihdy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2osdnpqnt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2xghfuebd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezkltekz.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gt2fwfuxqzv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mhcnxywh.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2ftillpet.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzktwxnq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2gahzihmo.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2htlckeil.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2trocflhi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2lkbnsape.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2lbxivnpd.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2cbbriulf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2wwnkiten.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2whgtmwsx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2xzfxokzk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2nazbyadn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gt2oxuaeuwf.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2epmpqtix.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2dohxdtwk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gt2synnxulj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2fvhbizdw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gt2stouoquq.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gt2scltdmqz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gt2omixenyw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gt2wmagpbge.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2uuudnehq.html


<!-- 参考信息 -->