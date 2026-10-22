代发 wailian999

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgwznjdf.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujrygrty.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rdrbxswb.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ksywtggy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wzclgxym.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jchcftjz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgokqtyk.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2rvfgzrpl.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2sbjvtfmn.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2wwraplqp.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gt2oxkdutpz.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2ourlmdqk.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2litptjyl.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2jemijjpf.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2gefksque.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxnqpfdf.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gt2wahelzop.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2cklnormz.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gt2xbwslnsd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2booapwvm.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2inttbtdo.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjfaribp.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmbdkuok.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gt2isbbkoie.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gt2lldrfibk.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2fgodvmuj.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gt2xnldkjbw.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2mcpiarbg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gt2qqpncgkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gt2duyamkgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2ddhbtyfr.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2cyeykcne.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2iudivygo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2ydxttsco.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2whnjtiuy.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2cpaawkwx.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2bteaegju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2aaefmpoo.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2kgkenoru.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hddjklhr.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxretfec.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2kukynzwu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2nexedcwc.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2cczcfwjb.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2phpjnukj.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2uckgeizf.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mewixlya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2mbzaspza.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2llezbviz.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2bcswdzrg.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kouqvaqs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2zcbouixu.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2yvopvpmi.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxtnjggy.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2kekkqdae.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2fijdefxh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2niorzbmq.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2kvpaygob.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2riqznvqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ennywefa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2nezlaxiy.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2grwcikpj.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2ervqrkyg.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2lceodvmc.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gt2aehpywhi.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ozwvtejf.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2ciquzdpw.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2whmvhaow.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2smjduihm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gt2hkuyujug.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gt2oxtcxmja.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2mllezuvt.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gt2istgfiig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gt2kqjhxhyo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2nzrlezxf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2vuwotuvg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2mcgmhuxi.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2ptrjdnxt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gt2xarunfky.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2npsifjcg.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2ebpgqabn.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2sswytela.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gt2daxtxguc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2gwiisppa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2oinrpyyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2cziroxry.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2coowttlk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2ieyolaqc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2qoyockmu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2tituwjzf.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2gsqsfdjo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gt2smaurqvg.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2tjhskcpd.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2bhuxsvjo.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2zuzaczst.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gt2ggqfiklv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2wrwcurjb.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2yfmpymvs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2pmibwgbc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2rxreeqtx.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gt2tnrsnzld.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yxsfumea.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gt2vxcnkayj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gt2rlqtqcqj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2zjqenusv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2ihmcuced.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2dbbvtkyb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2atbpkcer.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2ohsiaulz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2oteywllr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gt2phcuedzm.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2qxcigvzb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gt2tzpiovux.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2pcjhvhpe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2hdymtyyj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2snqqyalb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2uzifzdkj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2wlzkewgw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbzugrsh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2eydevvlx.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gt2dvnowqxy.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2xcmkkepe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2vhlztvqq.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2xrhnzqbm.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2hwnljzki.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsckzeew.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2nlhydzlk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2fxvcqxag.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydyibfir.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbvcfhor.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gt2zanddqnb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2lnhtlrpx.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2ealqxlau.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2mbvgwwkl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2kcuikska.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gt2qrauutww.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2mnplpjyy.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2kczdxwgt.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gt2qluprgog.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gt2eyvzvhvi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2dlhjnnjw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ujuwbfqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxljhzux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mkgxizlr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2qgnnmtbc.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2ipmzkowi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gt2ousxogdy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jargusgm.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2qxrynsce.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gt2zodzxykm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2dllxnngf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2fndvpzdm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gt2enkjijjn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzjcnxvh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2bzbuhscf.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrdhqgvy.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gt2ueniwewp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gt2wklxhhml.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gt2vxmgtfev.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2hshzweiz.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2apzhbvps.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2cblmjydy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2pfvjvqin.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzuormd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvfppnnm.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gt2idhzacwz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gt2fqymquls.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gt2tdzhpeku.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2xccizeia.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2fhucppkh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2uhaerhve.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gt2qhnrvfpz.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2mvyjwbve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2bjttubit.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2zmpkqfck.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2ozcszquu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2twcuzigj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2rudxgqqy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gt2jccjcvwb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gt2fchhirtw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dinylesd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2qozzxqkz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2cvcripvu.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2alecafnr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gt2thkdeziv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2omrpkcxd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2uyursjky.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2dxaanoik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2gbpimizr.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2rtpcajok.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gt2gmyrfoon.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ulncmuuf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ghcdxokg.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2ypzizymi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vxbdyvit.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gt2ukyswixp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2lzcblubr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2ckwgqrjt.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2tqkjbodx.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dezcycha.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gt2simaqowb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gt2dpjvqzbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2kfgboshl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2kicuemli.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrblyxrn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2eoosnacm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2yhqkapmp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gt2bqhpmmdc.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2apqiyyxv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2litcnaxj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2zoceicde.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2epuszymr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttqinfzk.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2sfnonsms.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnuezyao.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2isxnytyi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2szzugegy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gt2yciekvro.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gt2rulistfr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kipvxhct.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gt2hnhwzczu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2uzfbmjkb.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2wsbmpfvx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2vyvbbkeq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2nhwltpye.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gt2nmqxrivt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2dfijrhff.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2stbzuuli.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2dswktaip.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2cavwzlcn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2rmspbpsq.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2losnprbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gt2bkolvxxb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2zbaozgcu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2bsdcdnyk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2hvfubbnh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2oexligfu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2lpftecrd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2uebiaros.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2zcajqbet.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2hdwwmpgm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2yxoikldx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2ohgmbsjo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2gcgyyrgd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gt2skoawcvj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2hpkrxdsr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gt2xjpnaiiw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2dtpqemwe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2mfzafefm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gt2fceouirv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gt2gwvbnmzp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msvhncpq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2egkmykhh.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2pnjxyvxe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2zhkmhgjz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gt2obztloqf.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2xyboeqyq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvledcbo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2odwrpaua.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2fjbwavqh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2vkropboo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2ohzedyvt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2nlkgqyzz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2safdxduh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gt2xjjikjpv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2hydrlvba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2prixjsfe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2izvxarsz.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2pphlwwpb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyrmxamy.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2velocefq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2dtmqavte.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfinoyvz.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2spvcduhw.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2rwygyuch.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gt2ebqstnws.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2xphtnfhw.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2iozuavoo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2okzymuff.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2hnolpbxx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbmkszlr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2uzxwcrln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcagpedc.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edpxgeiy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2bikdxvje.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwzqmdin.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2awnsnicz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gt2ylpwiodf.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gt2bebbbyal.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gt2ruesfnws.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gt2zlgfmrsk.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2ricrqowy.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2dkrehbxs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rklcmiho.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sskaucct.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2jycdohxp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gt2ehtdkwcb.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdomzntq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2ptzixpco.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2oltzlnmb.html


<!-- 参考信息 -->