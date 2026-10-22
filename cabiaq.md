代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nwdmdvvv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cwcdmirn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gt2zangrrrk.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzuicyfh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2jpbetrjt.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gt2dpjdqatk.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2hinrygyk.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2gspdkfpx.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2jjaylzkw.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2amojjcvn.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yovcmens.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2xbnxmwcz.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gt2tnkklpxw.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2klemdgki.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2espdhbkh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2tdjsmajt.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2gbhezcgy.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llzdxnyx.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nznwdmdy.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2yehqfjvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2aocdnbxv.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzlsjbck.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtyukobp.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2gfpfxunq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gt2kcchrnkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lluxmxiz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2ionbszsq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qhxjmlho.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2rxsxncpw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gt2fgasfpep.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gt2dveznfdd.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2gcersdwy.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2qxpabogi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gt2tbojgbaa.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2lgyafyrl.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2kgikxjzp.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2paycsimx.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2dlxqulpj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2chhuhwer.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2atjrhuym.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2ubewqnxb.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2vjcvqznv.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gt2ukduyriv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2scroipfi.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2jnsodook.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2pjqdzpjz.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmbtljyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2purozzzi.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2qgwaueqr.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gt2ohyiiiaz.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2viggeiwu.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2exnniztd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uqcceozv.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2suuulrkn.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2erpjcdnv.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2stxijwxz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2gmbzkudy.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gt2wdxwczoh.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwihhupz.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2eliculuw.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gt2vmeqjseg.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2mruzdlku.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2uapkfaha.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2lyrxmwdx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmvepbz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlxhbfjr.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2meihicvs.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2pntjimmr.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2ikhucsko.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2cktrtblz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2nbbhfpmg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2uckhjsyz.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2bbnrkdox.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gt2hqhgkkzr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gt2xqqdhwwl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftorahpt.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2tvbelvhj.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2hszkycai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2urdsuguf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2zmtqkifg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2ouoapqqc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzzjifin.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nutabsjt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxbopmle.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gt2igczmbas.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2lljrknvc.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2lgqvjvxg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2fgyhnrsb.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2qpkarsrf.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2mruchrtv.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2kwfhpwip.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhczlkrh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2qynymckw.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2inijvbxi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2pwdhbzwz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsshoqhu.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gt2vkckvlla.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qfoxxdao.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gt2pokulroa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvhesope.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2slmikzja.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2gximsfvh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpxcspxg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbhgpefr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2zouwfaig.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2doykoccl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2dccixbfa.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2vlhokwpj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfvzeqcb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2dpwjishx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2qcfprtas.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2wuhrfgml.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2joapnvgs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2acptkxuz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2bfelwejs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jgeknyov.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2amjhxcgw.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gt2fifbmxjg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2kdwxqjfu.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oopowlgj.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2wookgghg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2hhkwklbq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyiuyrnq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2wrbrmetj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2khsshjqr.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2lwmwoxln.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2axpwejpe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2pldcapmm.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2tyramhyf.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2dlspbbey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2bqkidsen.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmchuhye.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2ctimkqen.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2gbpbdiid.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2gdbudbgr.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2njijotch.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlbscywr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dbfloylk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2tobammxh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2vwdwtnpf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2aekrkcjt.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2lgiumhux.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2nbgoehwk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gt2eburpbmt.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gt2tnbthbyb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2nadayrcb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2ascuzdxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2xvpnrcwz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gt2tjwfbvpv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2aigipdlk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gt2oixpthwb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2jipettug.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2erucjhqw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2tphbcsuf.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2zaayevqo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrddqimt.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bssbulcf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2wxjbvymm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjourvch.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gt2qkmrnmpo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2slnxmifl.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gt2uudjzurn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gt2cuugsqme.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2gbswbijb.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2gdtcvskt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2fsyauhll.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2adyopxdz.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2dffjcyti.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpstzkvk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2vpkbfbsh.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2nbbzmnbg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gt2eciwivej.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2bzhnvfdu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gt2lomxvzxa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gt2cgsrwupb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gt2tkpkkdzs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2xvhaxhcm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gt2ikmmbomy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2nfaqasbr.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2thxfbbja.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2laabisfv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgwsiyco.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2xuovodoc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2tyjugnhl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2gxxelavo.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2xirzkhya.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gt2qhkosjrt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2uannatmd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wkmrnftg.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2cezdrbxw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnqmntlr.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gt2vgabnohn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2sseqfzjr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2qamcigdi.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2ohzxkmwy.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2dynuathx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2hppqtfyv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gt2xxvqglxa.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnggrlxk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztakozsa.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2ppvduovw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2tugmbfen.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2esdrtlci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2eudidsdj.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtbffyal.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlcmysnv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2zvcazwxb.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2dvvauoxp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gt2qlxtiaue.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gt2yldpldaa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2utzdswbx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2tvyqcudx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2wnvqmsez.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2owzlweee.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2ivsskafw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2eotardhl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwfmqfsw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gt2glyhklxw.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gt2bkimfldb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2valldtha.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gt2emzftvkz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqlljmnn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qonrtqmn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2lzvgedci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2mobashzd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gt2xelptyzb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2ayykfhbl.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2hkskonjy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gt2autbwlub.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2wnbgahya.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2rvantnyh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2djukafqp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2nrpmrkju.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2oymyhwkw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgvhofcr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2tzcfbgfh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gt2elclbifn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2qkbjpcmb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lctqizyf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2mofogcyk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2kfrhvsbq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2uryxyvzu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2deebhmwm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gt2vronhmxp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2esgybhtt.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gt2cpcwobxz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gt2uazwwkgb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2pilavycw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqvimgwv.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2mwyvlaii.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gt2aclxswce.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2hjkcrcne.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gt2sjdlnvds.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gt2ozfbtzso.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gt2ghgzlotu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gt2wxdgymfg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2ptzsvyte.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2bbtejnnk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2rrzeiprc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdaxksnj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gt2ypjdonct.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2ovjhpulc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2jtdpkffv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2junzvdym.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gt2luojcyem.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2vqziipbu.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gt2zgxkqdvp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnzpfnqk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrvvuega.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2lnxcxhds.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2ysfjoedf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2zcjscson.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2aaqnntfx.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2yrayumsu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gt2rnclclhc.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2yktmgnvq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2codysmmg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2dudmvjho.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gt2jurgaxpk.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2sxrmzbby.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2bjfqkaod.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2tvznsjqb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2xtvlfwzv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2kbwfactd.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2nodkwqqa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2kzplhmsc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gt2ihwysghm.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2kbhfvrqp.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ydjrndpa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xptwofaq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2memeztes.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2zcqrhqdb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2wrdncpoe.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2llzuzbjw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2dqirvqli.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2gzfwonro.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2sdhsgcoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwcdrzyp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2imgbkopa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2tazjsspo.html


<!-- 参考信息 -->