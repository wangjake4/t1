代发 wailian999

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2dhodqkoa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2dzkojmuh.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sinsctjl.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2soavmmvs.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2yayijtlv.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gt2hdgjnkqy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2vfcxujzj.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2kdqgvdux.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2nknkwrem.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2awnnwjtn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gt2lsdxrzvc.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2xesdefni.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2dgfmomhi.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2gvvbeljn.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2uluwxxdb.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ashqxugz.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2zztqwyly.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whycddmf.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2bounfjlv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2dkyxekdc.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gt2uhftjvtc.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsfcyxsw.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2otkqjnxv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2dkeferhu.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2gqxgzdur.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2ywffmnoz.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2ltwwppci.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyxzglw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gt2eoxqggpf.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gt2rlbntqrx.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2porbafxp.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gt2ulyckmgs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2fumiibcc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2pqaqjxsf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gt2tarxfcwq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gt2jzincyyp.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2ipubjwvu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsqoebni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2tglmguny.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2jebpjusv.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrctvckl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2npldqsnh.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxkfecje.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2znxyxavm.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2lhmfhudf.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkphhrtk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gt2ormizauz.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2jaovyigy.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2chkduhfg.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqtcrvvy.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2nllxeoko.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2mlvngwrx.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2avgjnkcq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ytlayzdx.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ewijzpuk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2hlgiklww.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gt2sjvagmub.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2hptaewuf.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gt2tdhoopga.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrctanpw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2mexawgjb.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2fnofiqvc.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2vbccnssa.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yllylabr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqfijiyu.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2crzwnzdz.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2puiegbmo.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2jtgvbmxd.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2xwvybpyy.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2jxowwryg.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2wrqdnuhv.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2uouurbkz.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2gbgbvjqb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gt2gejsfmyx.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijyboroq.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2mjoznryu.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gt2zaycpbbh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2qfveijxl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcnolfab.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2jiswaxrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2tusyymza.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gt2qlehjdmv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gt2jzwfcvjf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gt2jdbceozj.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2vqqktpwa.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzmimjfp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xnwunlvk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2mhromrcn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gt2gtmieznc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2zhiwbzuj.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gt2tjliuujp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2dhenyqxi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2eceuelwu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2jhjhskfc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmdbctpo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2ematskzi.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2saxnkrtm.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dymqjlbj.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ouloxlrj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2bmhowyjr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gt2plhpxpic.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2oyvftmls.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2ocwvtrmc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gzmweedj.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2ddpklvvg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2bwebkmwn.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gt2tyjazmks.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2tipfmzol.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2eueiwxzc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2hltmhaqp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2ilhbsrxv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2jizhneqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2dudtgbal.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2jvqkwpif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gt2jdwnkfit.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2crovycfa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gt2gjbdsqzp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2gwdebqnh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unnnuwhr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ouyaweca.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2zegddhia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gt2wgwqrdro.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2ftndltww.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2rcloehxc.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2suuzzvul.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gt2dyviklmz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2nhmtfbhy.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znjcnfsi.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2erygxjuv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2jizytutp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2lrflwqjp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2qgamkhwp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2qigiknpw.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2mimaanno.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2zxjtnhmq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2irpgsadi.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2crqhhkmt.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcebnnoq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baxuoxau.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gt2hohhzzmd.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2iluduldy.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gt2fkmdrlbl.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gt2xayeqoat.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gt2ncwhpifq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbglboyk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2nzpjlcyq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dumtwjay.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2poxtsqqt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2ayysbwyy.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gt2rmcgpodt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvkxmnhg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gt2apbsbfeo.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grbifsxo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2pjciyyhv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2kuiexlpa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2nxoroycq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2ihhmhpqz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2wlyfcptf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2qvsodkfo.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2jjpfwrtq.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2vptvvngy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2ahdgwmov.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2brkmeeua.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlysonvs.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2mcaaywos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2fjwbrvqn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2wrkwclux.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gt2jbysbodv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2umumrhvc.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2uxdhrhte.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2irtcooxx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gt2qfgimext.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gt2ntjqfujz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qctbggmt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gt2xebxopzf.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gt2flajdllg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2nqqdsuvj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gt2vfzojzpt.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2cyhboxxv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2uccrlimr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmbiymmc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkqsopbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gt2eqkqjlpp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2ewklkvoa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2cltpqoew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2squgamkc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2rmrezpyz.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2alprermq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2tkilxqjx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gt2uwqzmpnu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2buazochs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2ewgyevhn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2echhhbiz.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gt2qbliteol.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gt2beihklgf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2zulavdls.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cukfjfjs.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gt2bfpzahvz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ddfyadug.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gt2npkycqgs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2xfrvlxnp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2cihhtprw.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2jyjfuotk.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xfsyjejp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2tzitcvby.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2xaqkcjex.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2rjpvkjud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2zuiwenff.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2wcghjeie.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2vkwzzvbu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgzvyenx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2hycjtetr.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2epdrlpow.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2zfscsems.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2amlzhnwy.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2uctddvvb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2qorwafcu.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2mjwqftmk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gt2cjcchivr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2zcipxipt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2rtzafmir.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2xvytcqzy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2rtbqasmx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2kzcdkrns.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2nvqjpmtk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gt2voeacxux.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2hvtkzzvo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2tkkedaqj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2txwrgbnb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2nhhoywyz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2fffonqqz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2xfojfmud.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lshudqpo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gt2xsbxhmom.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2gztlupjy.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gt2jgwmaoop.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2jjqkfpkg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2tcahdgwq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2znammuwn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2lvpfazne.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxskbame.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2iamrotse.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2ppxrgvdw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2rkqxalmi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2kgnipxpt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2wbqsnmhz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gt2wuvhmqjd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2wnamidye.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhaomtuj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2spqmxrcz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2awxbddpg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2inlbqdax.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2pxdujqae.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfglpijl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gt2ftnrmwgg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2swdvfbay.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2jwzxabke.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2nklzodcx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2snmotikq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gt2qbnhdxvc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gt2uhlglvyt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2urmegftl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gt2qknridhu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2rkjxomcy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2zdbtynpp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2mqqwbrgv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2mdgeqxdp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2drrscxba.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2ibzldspb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gt2dsryiwwr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2zibfkejm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vpvzpuso.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gt2sksjrfee.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ditnoknh.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gt2bqdniann.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2docnygnl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2btmgpdqy.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2upkcdurv.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2ciquvlnc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gt2ksgftlpq.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2dvtvxwfp.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gt2ycxseztw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2olsfesnw.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2axezjvdm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2ugejsvtw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2ssfkonmi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gt2aflzybns.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gt2xxdtpech.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gt2kpkqrsde.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2eednfzdg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2yafizlkf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2kyqcltfj.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2uimomfsy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gt2egzmqdpl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gt2fdxgefza.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncofacjm.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2bozmiqvk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2zqyvarqx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2vholykha.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2jakeyyst.html


<!-- 参考信息 -->