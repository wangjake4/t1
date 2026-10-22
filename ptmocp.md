代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2ndvvxcwf.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwgdawtl.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gt2ironjovf.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gt2ygqxwrex.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2hncgyjcp.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2qpqbtdaf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfareau.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gt2pozlfcik.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gt2lyfygtov.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gt2hkixuakg.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gt2arepbbgt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2yeyebfsx.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2exoakkhf.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qihihblx.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2jqaapjef.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2ocfmicmt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2fpmojixd.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcdypwrz.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2cfmnlyxg.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gt2kfpztmzy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gt2ceppfope.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwjotsyj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2easmdihk.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2vuosztab.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wocpbxhv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxpnobvb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqbxxpll.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2chviqrxn.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gt2bnscauir.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gt2uiqngvsk.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2xhuojvcr.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gt2nxvqdbcx.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gt2hwmhqgry.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2osnokppq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2rghfyssz.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2qwjuegqp.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2qxbsubjv.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsadtdgy.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gt2vvzjgpgy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2oogmssxs.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2yiqcsnpd.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ghzpzcbh.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2iaeiswjn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2hhoviggk.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gt2wpuhtrwb.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gt2jlwisiow.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2bagpmfoo.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2raqqzhep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2iefzxftb.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2hoywxubt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2drvtdmiu.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2yhjtdhsf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlynizpr.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gt2jocdwvqj.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gt2ztuscone.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2vurhsjub.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2njspjipm.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2rxkrshau.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2dqmhccag.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkbwesox.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2odgcfntn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2qlluzttn.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gt2mtijznwj.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gt2llailspp.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2ljmjdcmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gt2kwnlepuo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2ataapbdg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2nanuqvih.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gt2sfpppghf.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qathheci.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydbtaros.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2gibqfnln.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gt2ivtycucu.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2lszkslxi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2bprefkfc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2swklkppm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2bhjktyhc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2plrpwyap.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyrjirin.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2qedjsuqa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2shdigwkp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2mgruezbf.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2bcbjbzyq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gt2iuagufvu.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2vrdmgxyh.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2lpqhaplw.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2hvijyrfq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2xfmmbxon.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2manztgnp.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gt2qoqpisce.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2lgjivtia.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ekznavsp.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gt2dvrvkybu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pnannsqy.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gt2wprvallf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2sfcwqvos.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2trcmbnxq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2oqbfhkjx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipyklmip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gt2vesjaucn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywxquieg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpgmtbus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gt2bbknpwxh.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2jgqazmfg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2qoplfrys.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2fjtimlmw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2airpiazs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2degqzjah.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bepfgmej.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gt2rheskwwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gt2ihjdvdia.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2idvgjkui.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2zabagjwr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzokrdqv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2surtjhzz.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2qvaxyhai.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2ifccjknq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbhkjyzm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2dsnjytba.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2njzvbczi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2gxmyhkgm.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gt2uhpotayv.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2cedmryxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2arjzmjbv.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2tfzkcwxb.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywnfsley.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2lrhxgica.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubxdowan.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2nhfiqhmq.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bthylzdv.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gt2hsupdylu.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gt2cdtsecpw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2emgryyjr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dmpmueao.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2osubiasc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gt2tthqfjgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2sztixqcb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gt2ltrslzsv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gt2mgiwecns.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2lsbnedwb.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2yccoyqlc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2kyuqxgig.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2ffkdaqyz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwkeignx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2cevixlya.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gt2vjdbsdog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2pwyejkxo.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2rrocphts.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhmmiaoa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gt2shsimcnq.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2tighzret.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2vjcgydxn.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2axtilpbl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gt2iwogtdfy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2xemwofxc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2xwmryiaj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rprskhht.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2aeohflcl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gt2yqwcsjzf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2tlzzcfit.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gt2huuqvlfo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2rztaktws.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gt2lcvaqhsv.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2nwdvuuew.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2eiyznuxm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2wooqkmfc.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gt2yakeydhk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2brsetozt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2xcxqhjyk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gt2zlfwjbfn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2cdzjiluq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gt2rtezjhki.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gt2gvajvdvr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2cqpgapgq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2xzsjtjee.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2tigzpiln.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2sichpmbp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2rvpewurb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2pglavbwo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2epbfhcco.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gt2doehcdyn.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gt2dpwiqzvg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gt2haztjzmd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcwipliy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2schzbgcu.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gt2xauotwxv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zwqpniwh.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gt2vwyglqix.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2qnuixlvn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2slfkkgzm.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2oetpajan.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2ddaclpyf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gt2ualsaipl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2uylycagq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2ajbdttwe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2qkyknebs.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2sribzuhp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2xnadyyfj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2kmpsdbhr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2kfknyskp.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axfegwot.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gt2mnquqrru.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqvwvdjm.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2etbjmqxz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2pyurmuat.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gt2ibmzbetl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2zlhrxkqh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2adqdgdwz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gt2dmsneodx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2rohycjlp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlwgbdef.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gt2gduhrdiw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gt2ukyzrkmz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2cmbsyehp.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2fmdciwtg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gt2hdrtqcif.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2zpcviexq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2jwijkmrg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2nfriuiut.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2irxxrzeb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2iviphvnp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2ilfifmfg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2egxhrhhj.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2gmqymasg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2xwneomqj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2kgymsroh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2asjmhzmr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2ovzxrvou.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2vvzlwwne.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvmwfvgo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2kioxyeib.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bynssmql.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2hgadqrqs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2fpcutubd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2fxqtttok.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2soyfbgrh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2pglqlhxf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2aqahtviu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gt2azosvkue.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gt2bvocorzs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2hltdxoen.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2knzkcyjj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gt2sydrppbc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2bfkevwys.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2nsdrqeni.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gt2pqfeckmm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gt2vqotvdtd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gt2igkagdmt.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gt2tvzwhzfv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2omwadqst.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2scsyjips.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckdcdaif.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2mjrsoaok.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2jsljyotl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2apoapjmj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2dlhdeptv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2roxyrcyx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxknnrrz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2ivpohwjs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2auxiesmb.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2mgkzcpxp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xjnrwxcf.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2aoufczbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2ryeyeopb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2drsyrnzu.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2smvjjejt.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2xprkslmu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gt2ncphyojg.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2syfxuble.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2loudjgqb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gt2frinjksz.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2ykwbwhmx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjynywyl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2qyuptdxz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2eqzwwlcx.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2swkmoyin.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxdavqgg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2aszwfzjb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2rlxvtgny.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpoyyizf.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gt2idkbmjfr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2qprpqzie.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2xptooahk.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2bruqkhml.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aunmfgyv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2itnshnof.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2lcmpfvcy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2mvkqvfhc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aazigavh.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gt2pidpmtoa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2wkpunhmt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2tygtrszq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2meqnfjyl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gt2tcvrrpyh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdcphnhu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2xszkpfxt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bodqzwaq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gt2bprwfzhq.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gt2qwgblbct.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gt2kpjvsabx.html


<!-- 参考信息 -->