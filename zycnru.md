代发 wailian999

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2tyhwkzpx.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2vrebffcv.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2fsdusrgz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gt2qhqydupt.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2jsppgumo.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gt2gkpmdjck.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2qdxyujjc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gt2eburjozw.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwaucubu.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2lanjfyxx.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2tsesmopm.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2komnkqfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2azpmpqov.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2kbbvflvc.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhynxhhy.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbhtzhua.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gt2ksgmbize.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2wpocaznq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2cndfodzf.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntxgbtln.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2otriioes.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2pbsldoxn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gt2baosofsi.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2ybfafahn.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2hmcvbwqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2bzyhpsbt.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzogesxi.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2mcesgeod.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2cmbwpyjj.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2jgwlgrzv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykzrnsmh.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2bhbjgdxj.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gt2abohzawg.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2qmpeckbh.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gt2vzmgbseo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2hfumxbrj.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2goapssfo.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2wlwlfxfn.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcrafxsy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2xziwfxud.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2hufwcvta.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jaayrpsd.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2rsnmklrc.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2uevjlcmy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2webuklef.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2huqaubvi.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2mvxqgbyj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2uqsqqoox.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2lbcsyxpt.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2khovuozi.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2cotzlhka.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gt2vjtaxamk.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2qnximtkg.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2athsclgt.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2wdewbfoi.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2fuplvnmx.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2aahonrmh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2ljadyqmm.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2lvxhsefg.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2njmupadx.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2gbanbcdo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqjkoowr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2ekzuxfiz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gt2adgzmhwf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2bhbwahyu.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xlauefxp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2mixqzsvz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gt2zdsewsxf.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gt2mpmkgocb.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2pcczsndt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2imcktpwa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gt2hsrprqxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2gxnjhybb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2wimxmjnm.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2geuqkanv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gt2fjaooqou.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2tnhjaykx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2mrjvrntu.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gt2yxedweqi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2lfeiwrgj.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2dzugdwqz.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2ccgvnqnq.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2qbveafbj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2cofhqnac.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2ekaqimoy.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gt2kycqoina.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2ewbguuuv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2fwirzjzq.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2zwcrwitl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ldzqdpud.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2hkqcdslh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2iyzxlkre.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gt2rrhpippr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2acmeqzvf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2afooskjn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gt2yoiqassr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gt2rxmvnyut.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gt2hzqsksfb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2jdciuwhe.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2wkehunnu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gt2ljzaujyd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2qpyrjxnp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2wznzqidm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lydsxymi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2ruyrcaml.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2mplinkay.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2ucvkofkf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zybgnvez.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2cosktzew.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gt2xchugtyu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2mibejxbz.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2tpswuibd.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2ryxoiaal.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baxjskgj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gt2gmsexxzl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2ljjmeikv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2zfezrfuj.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2pptlmrtv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2jxducqyc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsvmmjdk.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2fuvxbqgy.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2kkckrgvj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2kqigwppy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2mipvwgtu.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2cpnoivhi.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gt2vbsqzldl.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2ulqkfggk.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gt2czeadjvo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gt2ilfpmesl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2hphrrjzh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2lgjpwpse.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2yoqnnjsn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2zzufhkkv.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbbpzrzp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2djolthsk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2gzksgsbs.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2ayqootuy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2mzpfgpcf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2rzbnysyt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stponygl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gt2xdnjghub.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ultyznjg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2umghkmot.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gt2gdbpmegh.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2ubmwecqn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2fwcsgxqa.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2kbnhlrhi.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2qlqmclhw.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2wazptyxh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2mlcqneqd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gt2iaihyjia.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpatgzzs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2scymvetb.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gt2wjtwbnrn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2fmtcakss.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gt2ksglstwe.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gt2ewojryiw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2bbphidws.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2vlncxcgz.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gt2yfhivsiv.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2sesirczl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvxvilfc.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2odgjcgwe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2kvasfzkt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cchhpzzy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2ebobhzwp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2alggkjhs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2wrspakyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2ftrfeqyt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gt2tnwmadls.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gt2rxmxwlwe.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2arbvuorg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gt2ublhscxp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2vjmjndtu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtsvsioj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2gblzjyds.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2wvevycpx.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2kzcosurv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2qwhohmbv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2dtbjksww.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ycdkaafu.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2pnqmhhda.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2urkgannk.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2lkavrzku.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2vgymodwr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2ygwqhemq.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ahrtyqpq.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2zoojtyxf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gt2zqphbide.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gt2pqmcsjqe.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2yvpsztnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2azowkauc.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2layuiobj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2xxsmgfyx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2powfqvxw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2awodgizo.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gt2rnaqfzij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2prcvcfpj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2shkbpikj.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfpzzbvv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2qohxwhqa.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2ccnsykfo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2crgoacdy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2heiyfqhn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2qjhrcwzo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gt2uhfeocgn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2stbeoilm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2kenpikrk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2iwctvuzq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2sjkmeojt.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2xlshpoou.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2namcfoae.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2akcjgrqw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2sazcznjh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2dovugefd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcftmmuh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gt2kbghatmg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2oluorvsh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2zdgovpcu.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2xybnwgya.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gt2qmawnphi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2tbaxehvv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2anywhzfr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2nrapdzrv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2yexlzlra.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2bugxvutu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2jrixrdns.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2akunpxds.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2ppuikrms.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2qcpqkbrm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gt2wcxepmpo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euswyrlc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2fevyacee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2ybrrohuz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2hzxrpgad.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gt2kznmhkkv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2ehneqwdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2fzezdfyq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2sezcecae.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2msqjgkqm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kecwljfj.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2ynxqsgnf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gt2ppmphizt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2pfwgktki.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuayidyy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfqdgcxn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtsuevam.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gt2jqbalwge.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2ttshdsjn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2qaqnwwdq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2vvhohhce.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2grckvkhu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gt2pxhzilxu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gt2juebuwzs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2tithnadt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ljujtqox.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fohiksgg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wtepdaik.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2wuoqjkaq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2qqzvxrtw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2jybexser.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2ugveagsq.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqdjuwxh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2qsihhjeq.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gt2rhyvetes.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2inhqvidq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2xmmzpteg.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfhwftor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2uywkeboy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2ywycgkys.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gt2bmocxkvc.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2cokgubik.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2svstbcln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvdoabbz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2botozhie.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gt2vfxskscs.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gt2hbrepqeb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gt2dvyhbmdh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2auriwxjy.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2podbkury.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2vgzxlagi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2jfvkhepz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2dqhtmuiz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2wjcbkzsc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gt2ijewjcxg.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2uuszdiaz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2fykcaqtt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwykzxms.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2azpfhprd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2yyjziwje.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2wzobznri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gt2tjvmogar.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gt2qfljjyyj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2xpegtpnz.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2xxqfiznn.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2oycwdzra.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2qrjpjdmg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2doqdhkim.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2ustdrfvy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2okjwolfa.html


<!-- 参考信息 -->