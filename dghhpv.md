代发 wailian999

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvnxlmrx.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jglyynbg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2xxofzzih.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ilfiesrc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2wlolblmp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2qkddaazf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gt2xlpcsozu.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2qynfousy.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yejsyxwm.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2fuiwyrre.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gt2aczqdpvc.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2jaccftok.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2brizyxjb.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2pdeiitpk.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2dvaajmcp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2dnzmnsgc.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gt2mgaweiyp.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2olaktrto.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gt2uzzkqimg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gt2ccfpfckj.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2lqnprhii.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2bausxidb.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2vvcwifsg.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2ntoxfqfm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2nihufcza.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gt2qnwvespo.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2hefaownh.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2nihydpco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gt2qvuzhryl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwpzhnkx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gt2zupsmkdi.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gt2yjutdggy.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ckhulloz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2usyigosi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gt2ddfdjruh.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2rjqkkzzn.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gt2ipjujnsf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gt2divkptwn.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gt2nowtcuni.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hakslafa.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2bcdhzxrx.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gt2kjvfljbt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2anpnlean.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2uettmcdi.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2syxqnpzi.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gt2arrgwmni.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gt2farvxwuo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ilsssypo.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2clzrbvdg.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ubivgpei.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ogitdvmc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhltelzk.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2cytmymbj.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2jfihqnlc.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2tsexuhrs.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2iprzvlcy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhislsqj.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kkqopysy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2mztnjzzh.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thrvcrbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2zvzisyxh.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2qvpolbkq.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2cwymujnq.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gt2mlhdxekk.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2kasiabek.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2shzzgpdw.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2sblpckqj.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2owofnalt.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2gljnopfy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2kvydbntw.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2hujfcymb.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2mxhorshu.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2ylosgyed.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gt2yxdqkupm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gt2zbsadqag.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2xiyvtdfg.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gt2egdqfigk.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gt2whhlgdsr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2ojipqval.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gt2jjbkijgl.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2zcppgwjf.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2wmqulwoz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2xkxadvqp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2fnorfuti.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gt2ndisailw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2vizztnhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zudundeh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2svwopypw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2kgbjxgje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2sncreokn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2cznovgdx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2agkwcylk.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2kgsokkyb.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpmotnta.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2bvikqslt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2mjlbaadv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gt2qkugxkcp.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2dynhbxkd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2pixhzvdn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hyheblod.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2wkqlfont.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2clxrcolu.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2pruulzcl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijybhxch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gt2yokrorjg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2gytrjidc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2eflwafpl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcyejwtv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2zonofagf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2crijbugz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gt2rembqjxf.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gt2codaowkk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2aligycnq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2wpbbnoyp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gqeksecf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2ocbftxdf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2zglukfzs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2qcnzgkry.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gt2hsynbhgm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2liaxucjc.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnzgodtc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2nrjwbhig.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2rknrukuz.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2ggcwdfpx.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2ypbzwsmt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2tcdyfkaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gt2oohpiabr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2kvvdlsdz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2uepwuesa.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gt2knkmsjvf.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2gjjjeqad.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2nbtvucev.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2vznfuxjw.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lflxdnko.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2xaumvuhk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vimuqhtc.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2qecuqfpa.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gt2czkphxzy.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2maomzirp.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2eabtdqvz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2hndtzobm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2dkfouavv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2uqrwcmzr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2pbfpydrr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gt2yywrydvx.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2wehalhwf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2nmmgivif.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhihygtf.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2auxcpbls.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2wrgauyls.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2ltddpico.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2scqiipiq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2akxqputm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gt2vzbzkddl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2vpqgnkxj.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2cdcuzktw.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gt2uadvnqls.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gt2jfrkgver.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2uimrolsg.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2lommvfek.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2rojuartp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2egjjnmps.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2ytdstmba.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhnyljkj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2tapouezd.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gt2ycbezyeh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2aordoqjs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdatevlv.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2bsilvdrt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2oqsokwns.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2qhdxwjet.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2xfhwlvab.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gt2rdcjnnhp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfdhbexb.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gt2gvwsjtir.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfgcrqnu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2csynzuml.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gt2wkjneudl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2cjhwtopa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gt2hbolyeru.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gt2bfnsinus.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gt2eyntofnk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2vuxfxnag.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gt2szadller.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2owzimvot.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmngmrh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2aajrvmwq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2dnlpnspz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gt2vrextgzp.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gt2mbpmyjdm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2diwccgew.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkmbzdqz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdprtjka.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2ksuwuhnd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akwumtmf.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2rrndigom.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2jphhownn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2fexpuvsl.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2dpfnclsv.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ersvhrii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2fyotwscy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2bocunuqu.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2timlcqwj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2lktkhigb.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmbbaqkx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2cgrszxtd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2gfajlivz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2avzfxqlv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwugccex.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2xjjxqvbl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2erotoucu.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2fhageazk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzqcedkb.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gt2bqrpqmmv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2dzwenafa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmhcifqa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2ckstqdkn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2dkhpxoaw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2jgavjlrq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gt2ryhfzmsd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2lmumtbwr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2iwodywsc.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2iidxypjk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ujofsdaa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2mekuswsh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2eluoythh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akffwlge.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2cyqxrpqh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2ipavnxwk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2dqftmrly.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2meyhnupa.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2uccjfkzu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2wobtuxfr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2ptlzpiqw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2mfcodgws.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2zlzdsrie.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gt2gkhmfjwu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2rvzchabq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2plnqdtyc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2vhwvorpa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2ucwdwdvt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2eqcnukxe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwzjlxir.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxmolotb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2irxuhqwv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2jnqyyxpr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gt2ddkvwrfq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gt2ofzqadyh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oozaxdle.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gt2smzsbyzk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gt2emonjplj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2zyuelosy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2bditenvh.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2elfhwcnz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtylakke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2kengxhdx.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2ezsbicfo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gt2uizlazvx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gt2tnpkueos.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gt2fdsuwjoe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2katsqfhi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsofetlx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2wdlatzgu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2agvtlauw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfgxjxno.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gt2yaugomdd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdrrsrwa.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hhhibcjd.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2kyjnlxiw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nhyjigfb.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gt2ieeqgsxf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2padoufjf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2faajawki.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2itqvzgqh.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2hjhcymry.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2jkuoldru.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcaptwit.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2whwdcnnq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gt2ayuhluey.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2ixylcpfm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2tuocyoug.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2cpqhkhws.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2cjhiryik.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2pyjoobus.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2bidociha.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqksvmzr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2yqsxlgsh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gt2syzsxrlp.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gt2zlvajxzf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gt2zxsewddr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2kimxdicv.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2pdmrdigm.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfjnphyx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2ebtsuqon.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2bgkupnky.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2yyxgobqj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2mclrvmya.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xeiwwryi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gt2ouephaqd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2wosriwjh.html


<!-- 参考信息 -->