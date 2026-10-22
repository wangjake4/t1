代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtciktulei.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtjxjbtsdf.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgmrqcrz.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtnhhpnxtp.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtcxewffxh.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtgrvbxudl.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtdrnbdlvp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtmxciindg.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtorjkvjvu.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtsabbmqxf.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadbfulmo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtuwtdsjbi.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtxhlzmyde.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtuvcldhxq.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gthglhvqew.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtojetadga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtazmdnlwr.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gthsanyyhg.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtvxxgnuns.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtapymyhiw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtzbjydjsy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtaxncjixp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtxmckfomi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtejiifscf.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtxxcjdwyy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtmiqimbmd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gthihhkmiw.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtpddjfoff.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtppntffhw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtoefdkcfx.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtmiliebji.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtrzuufmmb.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtpkdudues.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmukogjzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtvrovbsfb.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtpwfsggpn.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gttbmivyhs.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtkrxuzzmb.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtbahejoeu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtymwnaqsp.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtckjikilt.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gthznhiqwx.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtdxzwzwou.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gthyinqfiv.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtrncenzdh.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtrfivcsbj.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtbdsdfobg.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtxpkwyqqd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtybpsnfxr.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gteimfqjcn.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtugefwcoz.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtajceulfc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtgwgvjphz.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtxwktbqgd.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtakytzdps.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtairpucqm.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gttycyjcsb.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtpcumpqvx.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtqtdsytgd.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtaapezjtg.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtesjjgebk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrsupdcl.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtlnunocnf.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtyngedjxj.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtfupakslo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtnatqjvkp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gtvrruafrl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtwerktwff.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtuakzuhms.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtadqmuztv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtxhhcemrc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtzoopfmtx.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtiqqmziep.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtnoiporuc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtsyrwrgrh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtzaoajnca.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtnidtkcmk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtkukzjxza.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtslokdojw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtyyiwwryd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtxwdqghmg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtmtnzhpae.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtclkjipvo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtfpfwdeem.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtmirpzhqd.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtoibqieeo.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtjugkkuit.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwkbrcvn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtqevqpwgr.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtfvgizjan.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtyzpvgqqp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthwvtujia.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtmxxnovrf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtipwoegiz.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtdpqgpueg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtglmoxkxn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtrwnlagdt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtttxfsotn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtjggcafiy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtozvdmxch.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtiuyepwuw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtjwxgmwyc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtloinwrcq.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtupgkkrif.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtuxroqugt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtlnpawuao.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtktmgyohl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtezbykmfv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtynafltpf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtfdvtcgjv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtclkxbsts.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtqgmqnryx.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtkzafpvkn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtrxlvvwsv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtvvglkckv.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gttrosktof.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtofpgaxdy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtxhhwwwde.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtgzogrgxr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtaeckjclx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtjtvxmrai.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtyubuefjf.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtsycsxdkl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtbubqywqv.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtfvcaecyp.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtrxaxgnuf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtvcjsxzjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtxqqujdnm.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtiqszkjvb.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwljnwxrt.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtzgwsfjhr.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtpzqlmnvi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtpbzvcisl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtetetxugf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gthdrlyymq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtzlilwvnf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gttknqdkem.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtzlvvkxzs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkezyiomb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtoocpqmxu.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtlluskbch.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtorqwmraq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtkknewxuo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gteqibvpig.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtwtpowjpp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtqbrulmlc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnsvdhqns.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtjyevznhe.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtecedhttk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtizxrpimn.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtabfragdl.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtakvhpvom.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtuaoexmqa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtacuvipvn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtqcofydeu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gthhjpxccz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtbeggnztk.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtwksuqqhg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtzxnepzro.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtvgjmlpsl.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtjodhnbbe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyluytvu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtthwzfnmn.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtfuxuhzru.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gttmbchpcs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtyzmefwkr.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtdgaqdcxb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtyyauvoya.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtxgqadylb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtmohwtuxd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtexulylhs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtqkdyafan.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtfdfyzpwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtsnuyhlnx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtwrvuawvy.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gthhjhbirl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtnxcyrldu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtmujxmvur.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtynttszrl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtmejxddjv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtpbhwkfaq.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gttrjpbbli.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtsxyskgta.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqsiwydpc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttobmilwa.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtlpwajzfu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtsamhuhyr.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtbzmrjqnr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtwhdokksc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtwdjirayc.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtmicfhuyh.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtnaxethny.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gteiyvzarw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtnrzdjcso.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtmjwronsg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtxjlyfevg.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtykluvftu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtigwlxunh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtnyvcsklg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gticyxadal.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtxisbrmxk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtpvqwcgjp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtirnupssj.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gthafbilzm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtxelhyzig.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtvbznnvpq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtvnxrrrtf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtxfsuazkq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gtuxakqgwm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtfjxupvly.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtgabmskar.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtsohukuvk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtfelfivym.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gteurtjjwq.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtitibndfg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxccqpjs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtboupfdhi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtnzspuios.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtfadifudt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtdawgjmim.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtmeoecrkn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtqjuvzejq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtidzjfdkh.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtlhiziaks.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtgqomafzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtipbdxufz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtufvoajmo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtzqtymsiu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtbzzuachq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtywpzhpqw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtjskwxm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtswkqaifp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtzxfiqxny.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtylgwhdzv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtjinstmxn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtcopadlni.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtcvrcfmtn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gttkgdosup.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtngblbaam.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtxtuzqtjx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtwxmnjmpe.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtdoxktmba.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtclzfqhsd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtvxawdfhr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gtjhwacpoj.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtxyrkxxab.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gthxuanwje.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtrtdqgaij.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtujjylfln.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtmnszpfnc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtdjcfczsn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtpnzjyfky.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtpjldgjyt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtnaxvkirb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtuywpgiof.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtzosevuxo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtzxytaxrs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtfvyofiva.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtsmhinhrl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtiqwwcjog.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtnufobhdm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcqaaqwx.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gtyhdemtde.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhwbhssd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtifkpgwxt.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtgavepeux.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtekgqyotd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtjsjjskxy.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtszmpynrg.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gthbzpiemu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtrmxrfswx.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtcefdkrrz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtjhxqfxex.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtskbyqgua.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtpflhwowx.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtgihwesec.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gttplfyych.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtbmdvklaw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtzqysvnzx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbjztxtz.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtablsnfsy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gtdfjxqmva.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtdnlzvmxu.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtdljyzybk.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtwykfckyy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtodubghog.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtbowezhkr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtjpjlqzke.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnyzrpkn.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gthadiiaig.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtclforaew.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtzupebxlh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtzycifxlz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtdkjprzng.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvdsrfmq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtokpwucco.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtcmdqrkmp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtpsrgkquj.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtzyokrclg.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gtbwscnpat.html


<!-- 参考信息 -->