代发 wailian999

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2zzabahtn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkpuggvq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2jqnjbdap.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2nyabcyxq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2cnnmtfle.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2ztupmuja.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gt2nckjxsjn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gt2qlbbmdjo.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2vszoyzib.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2hzuuxdjp.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gt2tntswirv.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gt2irxqjqqw.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2hpnwjwhg.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyfjhrdj.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2qekxffhj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2xsltqnqt.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2wfoybfit.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2ckhidtqh.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2vhohhrar.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gt2rrfekcbg.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gt2fzlulutw.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2gbfjdzvp.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2xsrlzmuq.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2znwovnxf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2swefaboz.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2kefuhapd.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2fyupzoug.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2vhlnorsm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2gbflunyw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nazfzkjs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gt2yrhbieup.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2huywbldq.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gt2jtkvekrw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2qnxxcwgv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2gudfasub.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcrvrrvf.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahgzrwbh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2ufjzvtpw.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2xcndlzpp.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2sciczyip.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2mijymsfe.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gt2oprcxvvi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hammf.cn/Article/details/gt2bwlumtvd.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2erzerqwa.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2kviughhf.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gt2bzihzxqe.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihbqkmja.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckculdne.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2xmdghdzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2ssyoywzl.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gjgfkxla.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2pkldfmus.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2dznjwjtt.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2akyneusj.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wjmrpvrb.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2fjmbqthk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlyyshkb.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2laznfwrv.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2cnnxtlag.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2wczqoqbj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzmzxfpc.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2eksvsnji.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gt2pqydejhf.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2qtpcuyeg.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gt2ijxypwtw.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2uubdnkax.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2xuajwjjh.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2yhkelrds.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2fwgwqfug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fokwjtzy.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2dynfdjdi.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gt2lgqakxhb.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfewpcmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2tvlbobkc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2somruufq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2qguznmkt.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2oasflrsb.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2kxekqsxf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2bffjaidz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gt2zntxkrie.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2ddjqvldt.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gt2rcsyuftq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gt2fskoyqjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ovcctyfz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwrkerth.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2zucwqucg.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gt2flrzbpug.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2itlqdasw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2umzmxudr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2gwdjsziv.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gt2dtfrjrkd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2wnogboqh.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gt2eyldkuir.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2shilwhue.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2cjnkiknl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2bvzrhhec.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2lldtcwju.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2aymlppxv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xepxiadn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zhbdlpjz.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2ulhegnfc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pjeecezw.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gt2umjrssgo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2cwavusmt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gt2jjijcryg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2cthtiswt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ndkubrjp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2eqqiktwy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gt2xxdbotxt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gt2xnqsvybd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zazisasv.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2dfhofqdi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gt2wwyewciz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2flunajtz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2kuvlvlrj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2llwicvkr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2olpzyoeh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gt2kygoxrnj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2mbhdprbu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcpsufua.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2qxdaaslu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2srwkjsge.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2fpidaygu.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2slrereca.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nevolicg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2zszbuvrs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2hrfvbhnj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvpyccyd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2klqpvoyq.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmfuwpzf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2macompgf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2aehzqykb.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2uzjuzwqb.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2numgtdrb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2agwypwwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2pfjrwbvc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gt2aenlotdh.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2aijtdrxq.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2nxzcsnuf.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gt2efhruzzm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kurhiwgo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2cnwxtvww.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2znafduqz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gt2edafphef.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2owlwizco.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2vndzhbrm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypchzjnq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gt2ugstvjmr.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2xsfpbvpn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2sdljkimz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2aempiwsu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2osqzqayl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2dlhrsrqe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjhxgryg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gt2vlobqryc.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2vwbvfsey.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2kcqkhcte.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2pbplwpjn.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbtwojxx.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2mtjgnhdz.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqudhsjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2ozclwdzq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2olbsiycb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2bhumymxr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnaqcuur.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gt2qnxxgzmc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhgsrasj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2aazvrqfh.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2chfqntgn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2vqxieygk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2cuvjkrca.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2swtpwsdh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2bfpvyort.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2xonoslug.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtnauhai.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2wfxadwjh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2pzngdthd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2ihhbsihb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gt2aopjzlzo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rgimavxl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gt2qgojfnam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2xxqxxcvv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2wcqrsywb.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2zhdbnbko.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2rksvyjas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2fpiwfmia.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2ljarkgue.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2tvcemxqx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnbygigj.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gt2czwvvypx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2jwcjrask.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2aeqdisfv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2simuvwpx.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2jzfiawwl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkdbieic.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2coiangtr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ngxevwrf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2pdjnhvnq.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2ccvhxfmz.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2xyfazahk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2ybrsrqhk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwldpxld.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2oewipiil.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2tfuetqcw.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2skugznwu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2jxfpstzr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2jtflmjnj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhbbyvqs.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2ayjfskuj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2nuajapdq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2gglgbnmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2ldpeuxsv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2ogebwqjz.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gt2pwqplqae.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjylpfnc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2pusipmrn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2fqsuywiz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gt2iobbnolk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gt2mkfqxrby.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2ahujvsii.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2zsjsswbx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2kmjorqpz.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2rfwqizjh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2kbtknuoj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqaihrdf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2rrfbtjat.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2hfiqzbsx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2sypgodpm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2edodsumw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2epjkjkfz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2nlklncat.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2ibhhrdvl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gt2sexadwez.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2wldzhziv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2jemxfyzz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2zvvpqfqn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2jovimnto.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2gjsedhkt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2mhxkiosh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gt2wxzgndlk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gt2hdoulsyb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2colzqpxu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gt2swybtyya.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvtbmygb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2yzhxlwvf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2itxjjxmp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2ixyxkqvy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2zpsuoefj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2dgcvmhbv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2owaljprs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2lljdplxk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2gebrglxt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcjjacot.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2nfqldcsi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gt2saxlzlve.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gt2yyqpasid.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxnmjfxe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2bctrxcwh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gt2yjukagyg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xspyeghi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2hagvgvjk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2vwnmrstb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2uvxgygqg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2kszjyvqj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2bkthssgm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2akyrxerp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2oazgqibk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qwgzulcn.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2jxnzqpqm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2igfwwvhd.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2cecipeun.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gt2vnoupmvl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjwzmktt.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2tvfpvtsm.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2xlnshmxp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gt2mqydhyim.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2yppihcfi.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2uudcucym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmpreefo.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2aulfwxtn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2ygnwcpdc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2croqvuvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gt2aqhcbcjm.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2gcgqntqi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2ypkvcnut.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gt2eiwefwfm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2mietuovl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gt2zerxisty.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzbgnzgy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gt2fyapaucn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2rwszvzwo.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2tjiufjqj.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2occmflia.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2akqaqzfj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2rggwjusv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2cmfojuaz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2lisazomk.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gt2jmeltohf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gt2adiwgpje.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2ucuuhqqn.html


<!-- 参考信息 -->