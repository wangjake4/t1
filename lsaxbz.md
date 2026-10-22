代发 wailian999

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2daucgvew.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdnrylpa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ocyidkoy.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2lbxzpyxp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2ktrpuecg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2groctaxw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2luhdsers.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2xgtwmaxo.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2dtftsfgv.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gt2eptvtmfj.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2hhqmqicz.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2whwcyzmy.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2vaobfwrz.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2kwwmmvpi.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ozhmibzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2nrsjpsvh.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2seovrddf.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gt2bqhzrblv.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2ksunkyke.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2zivmiesb.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gt2zcnsaywy.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2pjndqqfz.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2rtasahse.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gt2oscycmih.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2snotrqlc.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gt2kpgwrziz.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cqqgjmxy.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2zqhabqix.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgdlwhlb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2olorxako.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2dmyvvduh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2dqwavovy.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hsdxldfr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2ofgqqerz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gt2slnnykbu.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnaiuoty.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gt2ixhmtonj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exlejrub.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2oxhxndpi.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjjqfixj.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2ggwsnlpz.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2ivkvzlqo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2ezyystdt.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2wwzakydj.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2reerbhns.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2faqwlhgd.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzczmzyi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2akojyurx.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2vqqhtjim.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2qzczuhwn.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niojqvof.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2xggwfsng.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2egmnpftp.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jjxbxiop.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gt2xipnfyan.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2sububrxa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2idpxraby.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2ujmtcdlk.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2zzyftvmg.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkumtroz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2tvpllxmq.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2sjbtuqdi.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2oqbofwlb.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gt2qltprara.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gt2crpwrhon.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2ameiimki.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2kfcdhiyr.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2iftxwnsz.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2hhkzdkcg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxpbtfrz.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gt2ylxlhfoj.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gt2nqloqmri.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gt2wxdbodqh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2gzlljlrh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2iffbscdm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2ilvpkdgv.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2hmftmnxh.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2csyrlrna.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2xfdpzxvg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gt2zzmqtwkj.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gt2zlktvcwo.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2ybnqjfly.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2hpjccgmn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2qjyisthz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2mmfwbiuq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlqwqbnf.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gt2matypulp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gt2hxybtles.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zturqtcl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdlalmcb.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2xxmrrftj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gt2mwusceti.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gt2eiuzpxik.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2hdseiosc.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ufyxnvga.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2ezmnpojs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gt2wvddwzrq.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gt2ycwiflgx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2dxccaeqn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hotvrfij.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkmniqoa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpfedlog.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gt2tctqswge.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gt2ayhbxzno.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2obzthtrq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yoeiklrm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmtyjipp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xubyljhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2yxcpoisb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2zpphcyqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2vtxgjetf.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gt2bfezjrsm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2dadwrexe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2qlboryar.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2qbkeamjz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2vdjbffwf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiukekxf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gt2iezzuvky.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doasadhl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2jxzzqhkb.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2rnofqlps.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gt2ikyrajyk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2svutxnsg.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2razbayle.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2uulykmfr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2zapcuaow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2zcxorfec.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eulycpwh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2oowpthgw.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gt2uaulsycj.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gt2ajbmttjh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2btkmplmx.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2zexqmtvb.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2afknyhke.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2fkoemqjv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gt2oloxfnwe.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gt2qfknnaif.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2dthmitqo.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2puvrvuke.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gt2ykztkvzy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2vivnlnsz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2moafhyzk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2ausaelup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gt2brfwentr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2hjjmuafj.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2cujsguer.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2tlnaiafy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gt2agkdbykp.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2givoklos.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2dyaokkjh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhskgkxv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2fnwiqmrt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gt2oaeurlow.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewrxfals.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2xtbyndvn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulkwsahi.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2cwmdeifi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2scwtyjtw.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2jpjvnrxq.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2wfbgitku.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2qvskdbdd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gt2oqepuaaq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2bpplfrgy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggdzoywq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2minbvkfi.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxktrdhh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2njlovdxd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2xndubrnq.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2aiiihlfl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2dovrebgj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gt2edokxjrn.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gt2tfmchzqp.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2ipwlaznx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gt2zkhhadfn.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2vknprmtw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gt2ifuuytrr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2wapymlsk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlppvoeq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gt2dononukk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2oiatbazl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2xgvhgots.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2ztlfpyvf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2zoaedojo.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gt2efbwggvt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhfssoxp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gt2dmglpfzv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2mjhtbngw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2tzfxpxvx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gt2hyrbjmfj.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2yoevofpy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gt2uaxxswyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2csveczlp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kdvcxeik.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2quwqchju.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jyjtvpgf.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2koteruie.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2xwavcfnh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2ubrzgeue.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2oiwrtijh.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2udlsyizv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gt2qeueptym.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xgetexrm.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqjmwhvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2rcijpajg.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwtmkmdy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2xhrvjpag.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gt2zalhciwm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2jzmwrusb.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2ihehdkat.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gt2jvnnuwxs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2bmuchgaa.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tghgkghq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2jsakkcck.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2vxnewcvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gt2cpfvdeqt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2ajewcodi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvhdzhxj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gt2gtjzfuzw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2ryzowhun.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gt2pryzzkur.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gt2qpnyznim.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2occtuwvd.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gt2betkbhol.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2qetfkzww.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vahyekrp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2mppalysh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2hlqvnrov.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2hdidkjbz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gt2qkdfmuto.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2jjczdspz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2pacetnwo.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gt2dmxibxdw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2bbmdmdhn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2iuzaosvc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2zcvuipaj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2urnnoysl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gt2lyqyhddz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2qjywubvr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmhafnk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gt2uuleuvzc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2pjxpjatd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2yqkplcxa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olzriyko.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2yjadrjyh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2dulqdxlz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2aqykkqcq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gt2erpkqgia.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymjlpuch.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2xjjnhzgs.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2rcmmvuge.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2xjysomud.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2evtwamld.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gt2mfgqzcrm.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2fkkxqqwq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2imavcywe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gt2qutirsmh.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2enkfhzbu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2eqfxpxeh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2uimfxkrf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2ddhxiici.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2zyueghpw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2phnjteyt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2ccxtvrzr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2rwqgiciq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2afwuiram.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2syfhhels.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2izcjbvto.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lazranzn.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2inwuecma.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nxisfmdn.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2paotuhej.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2uhgxijas.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlgrhkzm.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2blszryon.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2mmiachwf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gt2gubfffdt.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gt2wohbcijl.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gt2uqqnamik.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2axfkbuxw.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mavgwqgn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2kphwlmxx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2xjhbrcnn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2gwahdwpp.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2mhpxjnou.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2nwohzkmh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2ggwndrco.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2dqvuxnnh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gt2owcxcshh.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gt2lhfxjgnk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2esykmvvj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2xhnvirqh.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2psgwywvr.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2mixeduaw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2wqotpolj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2krtnlkjq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2tudtsalf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwngpsdy.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxdrwvkz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2rnodwprk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gt2dgqgbutm.html


<!-- 参考信息 -->