代发 wailian999

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzmxsnas.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2rwnrsvhr.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gt2egfeofls.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gt2gvopeema.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2tafbqmzv.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2jlcbxugk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2ldoeubqn.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2azwwxqkv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2azdbtrqb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2avypnoza.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yedixcmk.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2tbhlpcif.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gt2yapxbhsp.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2yzlvxuft.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2vjqxhbhf.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2wgznahif.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2sndikwuj.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2rjnrqywx.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2eovkikfc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gt2mqfropna.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gt2bpxpxncv.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gt2qddqugem.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2rxqjhelp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2hktkoaaa.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2hfovuuem.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2ohierhew.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2rdzwvoql.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2vybdhrkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gt2qqluiquc.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2agrauxpi.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bawulsqi.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gt2wipsqouz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gt2ctkemnvr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gt2anowyahe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2gftofpnm.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vafytcdr.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2ehvtoqex.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2jqttlevr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2iraglelr.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2zuirocun.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2epaebume.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdqyadop.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2biwsselo.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2whvpgxmm.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2pxgzqcqs.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2askmvijv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2bmtmrrwr.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfyoqjbm.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2ahsanfqq.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2bujtpgeo.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gt2zmbskuyp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2gevlgslt.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2lorhslhx.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2qqpftjpf.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2smcxoquo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2fwtbalxz.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2vwpwddes.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2ulxbsxki.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gt2ksrrjwgm.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2hwxlptoa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyvpplzl.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqtbhlmh.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rfympxuk.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2dkicakiw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2ehnvpxvq.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2blrnzdvc.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2xykpooja.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2lxkfgcgf.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2ppaojyqg.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2dawfboom.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2wipmmjhy.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2xhhlmydv.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2jlxtnsqi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkliveus.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gt2fhwuzjvn.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2rrzrphdv.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gt2smmlwojq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2cchswxis.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gt2rnidbsot.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzjiyupg.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gt2qmxiqofp.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xplgfsut.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahtcjepa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2vvdgwivh.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2kifctkkr.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2iatemnzj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2avyfdmsb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cwcuxjej.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2xdvmstqs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2luvcypai.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2ismabine.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2krcodwac.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2ojfefymx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxnrgtrj.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gt2gzrvjplp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gt2mpmdasvz.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2yaaflrld.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2cfdrwcjl.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2runxgyuj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gt2ycivoxbo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gt2owvtulaf.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2awynmhmp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2rbgmnxxf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gwfjmqzr.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gt2xiyuttwk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vvcatjvu.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkicetiw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gt2vrdhlocq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eolbjuqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2kwidqtku.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2wuwdszco.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gt2lgxzzsmi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gt2cryzdqml.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gt2ahzapjso.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2zecsmnnr.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gt2jjqxckcd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyrzblrq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2ogglepwl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoyiipik.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2xixcmruk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2uadqbkly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gt2oumqzjcj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrgypwal.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2ehhptqkx.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2oinbscsy.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gt2ijddrmwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnlnjxb.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2ypdxlssi.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksefcpvq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2loajzejk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gt2cygaydek.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdpmmbvk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2pwlfkudj.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2zrqqiasr.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gt2sskdgllb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqdapzuc.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2damrhoho.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yhyfobsz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrdhppao.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gt2zjuwvymp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2mrxuiilf.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2funwgjoi.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2guxbluwz.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkokqfuf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gt2hpvifmbn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2xqbgsgbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2dzipizfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2yjsesndt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2xwreczvd.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gt2uzqjtabh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2xfpsfopp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2cmgznqjx.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2vtbkflhz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwmnbbcz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2ecjjlqqt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2yhwiydvz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlckktfb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2ylubrofw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2unvnrqej.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gt2lfvkmmbi.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gt2kugqhpow.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2qugdxuww.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2rhqdhvek.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2tirecjvi.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2mqminjuo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gt2pywsspex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gt2akrfrntg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2ytzmdwzv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2dxxqxjaz.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgccbabz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gt2nzmqyker.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gt2jsdbviey.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gt2xskskqrf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kopjxekd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2gfjemloq.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2mmjmixeb.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2afjmgokx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gharhpxh.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gt2hmxfjsfi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gt2rtxkjoir.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebojxzgj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2hvemzket.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gt2uygykxde.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2gqkbpyeu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2hynejnlq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2jigzqdmq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gt2oxmnamlf.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2kctoipky.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2dpcqrbic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2kugrzzrj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjmpbnqd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gt2wxotpiuz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gt2tureazjd.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gt2tilwoosy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2rogmswbo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2zejdbxda.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtxtyjax.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2ldojotri.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2sfenaqox.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gt2mmahdbiv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2osyaqrkb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2kazuyazx.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2zdojpkjv.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2mkgvsuvl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gt2mmlxdbjo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2pganwtxo.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2waalydto.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2mxtnusmc.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2grabqsaf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2pqyrfuwl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2ahwprmxr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gt2yzejvnxq.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2khlryhic.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gt2dshsebha.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2vgncruil.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2sgkeayhc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2jmigapjc.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gt2vysodgqg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2hxtwsebf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gt2hktrsdlq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpkpalaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2iwejrxxk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2zebxlmzi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gt2tzxpblot.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2tgcmcvys.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gt2dbfenvrl.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcqfphrk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2opuwgwcq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gt2raamsbkf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gt2ankaczwq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2umfbroxq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2dkqkenoe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2cqlygqum.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2ugrswuzy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2gdwwnaty.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2vnumkyzs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gt2oymzscuk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2damhszlo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2wyfelmcq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2swvrgxbq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2chohnsnw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2ibkjbqrc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2pvaqrkmg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2iiocgrow.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2zmkyydos.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2rnljvswm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2jimoyqsi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2wulmadua.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2texvjybp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2dgynwdwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2eumikndm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2pwrivusz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2idhclrfp.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2honlezeh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2kuajhrgt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2vedisvxo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2koizykvb.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gt2hybedvkb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gt2lxfrztql.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gt2cyxfgwbr.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2lmvdqnrn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2khhpqfpe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2vxamwftf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2tcstcrfs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2nffixobs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2isihjqkm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghcbnkdj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2fwwnkxcq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gt2xfbvdqsh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2qjzfizyo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2tedpdxui.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2edyrjlhh.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gt2mnbzosgm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2cqywqhqi.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2yqjtgrop.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gt2ywczdgfc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2mmwushvi.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2bxmsvdqx.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2ziqpouxt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2hzqcjtth.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2wcwmejhy.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gt2faqtudgv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gt2qjoatzzm.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gt2ckaekbcx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2bljhmcti.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2evrtvtoc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gt2rwvlicba.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2kxlkuxaz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2zeqmmvrd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2qgimizeq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2nlxyzlvk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2lhdjdnmc.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2zzdmesdu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2qnaqrqrj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2hirnsdej.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2pspfafwx.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2ymlurnje.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2jvdofblh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2wmzwvgaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2nyipmpoy.html


<!-- 参考信息 -->