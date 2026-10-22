代发 wailian999

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gt2gltqbeer.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2luoftptj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bqqaztbr.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2fsuzzzjg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2cfmwtczk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ofhcnuoq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2ojxlyear.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duduutcu.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2tleucqjv.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gt2hgspbunj.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2gsobvwbg.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gt2zgrkycou.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2pxbotuhy.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2bftkvylv.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2ilmrmrdb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2mhotqptc.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2bzgatznj.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2gnqrrdcq.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2tonpssqh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2dhkwbptr.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2dtzmbufu.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2iybbcgxs.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bchannrc.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wglbfwai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gt2rwccbvzr.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2wosuydvn.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gt2vtqdljhc.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2piftxjcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gt2qlbxyzrh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yiuriewl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2fhczmmmq.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2qnsqzbrg.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dlvgfqie.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhmykctf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gt2efedlnsu.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2wtumfbwr.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2qnbjfejq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gt2gtafmcfk.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2kqensyar.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gt2vzekuqvf.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2nsbmxpfo.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gt2jidagqla.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2xmgnxlhp.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2jsaseykv.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2hjmluyyp.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2yypnbvye.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gt2wbzpucup.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnxytmom.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2skxmwwwn.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2jdoxsnln.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2qqqgvgzd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2hgkoayzf.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gt2fzyrgyfr.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gt2llehfmoc.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2jpocjhip.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2pqqildnd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2rxcfohgb.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2bgxdcthv.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2uruybeze.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2bmvtgkju.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2xdtsgexi.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2uqzbxdvd.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2pyjbpsoe.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2zlrxqgev.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gt2rcenvvlb.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2vuqsxwew.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2acvwqxpc.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2ihnhwmhr.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2tblixbfs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2jjxpsknt.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gt2sozhasgu.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gt2jdcnctim.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2vxmzqhyz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gt2xyhpxyrb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gt2vepoehce.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2zonemghn.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2nmdzihrl.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gt2stbnxhae.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gt2aesmrpjp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2vlqogpnc.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2dctokedt.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2gcobnrwn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2lmbwylfz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cqedtcml.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2qakpmpld.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2ilokzhkt.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gt2nhnjmpcg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2wcvpcesm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2myrgjoda.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2avosrcsz.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gt2zdbputfp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbyonflh.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gt2kpaflbrj.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2etsfgqrv.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2gfnhmaei.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gt2nermbzcp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2qsapdpke.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnwomrhn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2drmknbui.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2rdixkloo.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2xejoukhi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xtijqjhm.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gt2hfominlf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzgiwgwg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2pnniwafd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2iishbely.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2bzuxvohj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gt2oxbjwted.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2kizxarzu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gt2jrqkcaxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2cbbxvluq.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2tlgwrhei.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gt2hiybrdcs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjwhfxke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2avlioddt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2kxcapvvd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2uoeeradq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2endxhbgr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2mgpfwfiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2exyjfmpq.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2ocaaxnqd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gt2nuhybzuy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2cuttcvcc.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmbhcyoy.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2cidpzrho.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2pprqnzmk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awzymrqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgxjyrlz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktnwcyjh.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gt2iqrimlzn.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gt2wjvfwiwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2yiurjlhv.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2klmjnoip.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2axphoqcq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykpwcqon.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2wmnophfa.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2arzffimn.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2dxfpcdwl.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2afgwrcdh.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2jcbkymfj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2cotpvqgk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgofoida.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2zdalgucz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2nrdmsbll.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmqpaunu.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2baqlwehf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gt2lqvugjiq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2ivaatdrr.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gt2uivliwoe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2urayirww.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2thqezvit.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2yiojmxnc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2dbmieomo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2jmtyfmgu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2sljzufxr.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2cembarnf.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2eykfanuh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2cppwotdf.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2mhdctcef.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdaqpzpi.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2ehzyhibb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gt2dnxmvngr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2fysliwkd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2ddxrypar.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2qtvuzkdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2phhwlcqi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gt2docwvyqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gt2jszwspkp.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gt2mccrewnl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gt2jdzwoipf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlrtqsja.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2yayrqpus.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2ogvbhggi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2funqvlcy.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gt2zpdfhhht.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2anjxolty.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2ocieplgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2okppizbv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gt2zqrqywqc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttyoqekf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2eheukdjz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2ydiskxae.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2vgnwffwo.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2lqllbjjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2uqogoxus.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpzxhcko.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2xmdtjgqr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2trftmirq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2wqtgrqln.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2owfckmks.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gt2ftyrxbwl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2gjxtcdup.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ndnisrca.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gt2ohrzzavc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2unozzdwd.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2fzqmlnhk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2qtdaokpr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyivzfus.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2ogglitsq.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2yrcgyzif.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gt2xezvzjzp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gt2yhocvvuq.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2gjkqpbwg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2jgqwvvtv.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqhvneod.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vnxkulyj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2tqzpyhgc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2ohatcnli.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gt2lvmfbkqu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2lvspixgd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2vliyithe.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2rdjtcuqz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2wuwpzgoh.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gt2fdhopudc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gt2pfxgodem.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gt2khngdnlm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2vloapwkp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2knlkspfq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2fieieuhh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gt2cjdzjymt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2iepznlvn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2ppmdgpjd.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gt2bjynamfs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2dqrwnsos.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2wxunirme.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2wgmudtab.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2wyzsxend.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2rfyjednj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gt2rulatywy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2zvoxdyjg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2anfshxgz.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2sczkmshc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gt2pdogpkpd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2etmkaobn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2ojqloukw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2bibhhsrl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gt2eangeqxa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2zbpehhcv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2tsoehkne.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2yyzzvdvy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gt2etbtfysa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2wskkpfzf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gt2czswwkpv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2roqnptxn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2bvdkijuy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2vtfhoprv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gt2azxwjbbq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2htddzvkr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2nqcsrnrl.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gt2crajjbzd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gt2isnvoxkn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2zybkxppz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gt2hydstaon.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gt2jhvhckac.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2zvjmmlao.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2xqhdiamr.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2gayodall.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gt2epokgpkx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2tarctyfc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2upeqxgog.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2tfxdeaha.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2tvqzdmwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2hpqmhzso.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2okhbprsz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2jcjmdihg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2qloukkjx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2uwijotnd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jcqtaitd.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwarkgmo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2raggxfnk.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gt2mhestmxr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2xoanbcwg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gt2labisjsk.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2zpeksdch.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgcjiona.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2rqgzttmv.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gt2ijfxkfsv.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2ugkfrwgl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzrertwq.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2ywtfopxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2mbjrpyuo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2aiuvdtne.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2seopjimz.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gt2xfkdzxgc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gt2iyzypose.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gt2poazqnan.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2hkcridtz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2aepnkqhy.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgxnpift.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2wbfknrkg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2odxummeq.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2yxxtjdcv.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2kyugagjq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2qkxckfvf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxojglca.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2rpqkgaps.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2txmgptad.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gt2gcsfpgxa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gt2jhjxmgki.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gt2uuocnlqv.html


<!-- 参考信息 -->