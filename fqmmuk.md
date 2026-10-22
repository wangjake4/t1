代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2cgdvgofn.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2ymbhtigq.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gt2iecszggs.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gt2spfoezmv.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2nhdvwhpu.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2rifxlkzx.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2aujsjnna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gt2luybpxaa.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gt2zdzcjkzj.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbvazlfe.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2jnkzzylo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2pwinesgn.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2wxlbhqhf.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2jscmbzwp.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zoznpwjs.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2asnphfxb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2eyfwtrpi.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyleacdz.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gt2dszkhfhx.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2iyqvvwxb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gt2xefwgnyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gt2wxfjsmgl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2zfailudc.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gt2jhpbmiji.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2hzgxikej.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2qreaxhfa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2hawdxabj.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2uqrygcys.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2gidwwnvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2hdglzbyt.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2bryaxmuk.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcqfodjd.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2qstatuhl.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2nggjfrxp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2akmvvfgs.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynxhyimm.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2juuwelsf.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gt2cpzgyegj.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gt2chbqhyem.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rejffryv.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2dnhpfcrc.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2uqsdnfyp.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2uzbtodzd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gosaudmy.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2wanhtvcy.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2nohboqyz.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2ufzafnxj.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2xvuwcozs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2rgnpwiaf.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvwgekss.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2jvojqnlp.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2stagfojf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2drgywqhr.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2utdtvkip.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2lqnlhzdj.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2xsduaywh.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gt2qokvpyyv.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2viyngprt.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftevcocw.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2wtxsxmdi.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2syqhxkbq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2rkrjxjsq.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2gotjbtmz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qunburuz.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2cruxongy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2xgiovaok.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2scmwsiih.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2ktnnwefi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2hvaatfcw.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gnhjraaj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knlfofoh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gt2bbflhswi.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gt2ulzjytlt.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2vfkclced.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2akbqbjoy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2mowgjtkp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbkduhra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uucwqikg.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gt2kljfbebo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2trbazkke.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gt2oqedhccn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2vfglxbyj.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2ijstyqmv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gt2pjxmxwlv.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2kduupqor.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjfzgntx.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2kqempjzg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2thfrjswt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gt2xkwhrnfx.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2dbsirujy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqovhnhz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kguwxlwx.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2wcwscjox.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2qphilooc.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2fvukwmhr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2iuxoqnup.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2npqgsfct.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2ipojgqpr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2pnkijbjw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2ayxzttub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gt2xbdyoxjo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gt2hltfokbc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hfummvja.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2rxzhltxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2hceeexee.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2hqlppaee.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ojixtzcg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2icewgzft.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2epucujsg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gt2cuhnlmhk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2knxmdrkt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2oxzvaoap.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2yadmfaar.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlndpnql.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2kzcmbfpf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2zkzpqdyl.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2wlrsqxsv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytpenpvb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gt2fqaupjhd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2cizzfxrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2dxbpvmpe.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2upogvzqc.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2xhbdiroj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2ksouocap.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2uzcgkixa.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2rkkwwoek.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2zpjqidwa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2qiyhthrf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gt2gqyiklvw.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2saqwmmwo.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gt2davwxmrc.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2wrfkkbcm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2rdmgiueo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2lhkehztu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2djutksep.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2nsvqouqu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2boiqvybr.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2izexyayt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2kwnnazrs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2yfcvdgzr.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2ybnbkneb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2xyeeeycr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2vyatxzle.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2jxvhjsue.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2slxxkpsf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gt2noyjvbkb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2rpsmmivf.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taztxkfr.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gt2rsrtvxnt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2snzrconj.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2ldptoksl.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2yvjjgwud.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdxlyrfn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2odnrypia.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gt2ygsvuhwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2uhmygqei.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2odwxahvo.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gt2lybqmfdb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orecrubp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2wbkgjgvt.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gt2mlvyybiw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gt2suduxgmv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2jdavhuyl.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwnawsrx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gt2vcafjmze.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2ljmkajvr.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2oalnoknv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gt2jywlglsk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gt2wpaznebs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2zeleuxty.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2riztpvwc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gt2gusayihu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2titvaayx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2likdcvlv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2gelznuno.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2acdbqkzi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2utpczivx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyejxafm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2parmhxxh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2hhjcacew.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2iytlibnd.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gt2rhhtumsq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gt2vocgwpkx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2lawsomre.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yooeekyq.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ncuofprh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2dpemdxlv.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gt2cmgiwtsj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2qonbhyxf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2iqaoalhy.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2iibmepai.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jilgddua.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2gezdanxg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xvuwdzdz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2trydknao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2rzswmzqc.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2mgifhfnh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2wqtgvjbi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2fzxzgsvr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2evktrnbh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2daqrksei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2vgkkzidc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2vkyyeptd.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2yqxibmly.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2djzrrsvg.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2nqawcstl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2klanymbl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2jtmvscyb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ymggifxp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gt2dbnnpsyw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2nrjlaavt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2gqwxfsba.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2dmmwfrgl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2jzpnfbfu.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2jickrjiy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2qjmjfgii.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2czpkxlub.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgxtyqos.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2rstbmmzu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfeegpz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2aaczabpv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2eagkwgce.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2owzamcvk.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gt2fluvozvy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2jqjkqmhk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2upampvoj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2dmzwihho.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2svmrukip.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2sfvlamch.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2uawuvwst.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2wnungjyh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gt2pntqimrb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gt2zctzwhpj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2pubpwplk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2pttclrjy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2pgvyyirh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2qfttsjfb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2yvrchlpc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkehoaof.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gt2welxvwce.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2pnspicpx.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2bbnzysfe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gt2owiggwfm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2ljibjddm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gt2lvlwincq.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2pvptrqno.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gt2fcqctaed.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2ywyhiyix.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gt2sgqldums.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2qinxvjhc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2rsntskpl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2iutfrfxf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2qogtwgyx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2ofjkbmeg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2kbbmdpdq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2kbwkerzm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axxzexeu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gt2kozlocxg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2hhzehgwb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2pxnwrkai.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2xvwbfaow.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2thuhexkg.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2pokdwifb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2lzywliou.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2gsqwcvdu.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2onwsxsqq.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2qbhsxuec.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qllkwwcp.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2jopvkryr.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gt2nxssgsnz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gt2alfahfmy.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mccvklct.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2gqpjvqem.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2xhpjdbad.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2kmsroiyp.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gt2ouptjfjb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2ftnqjeul.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2nnxpozwc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2zlpvsdtq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2ykfwdwth.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sffuvklc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2gojyeoza.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gt2ejqjukgq.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2qrsmiaks.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2bgjqxzvw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2vawtbsll.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2btxutpdz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2hquramuy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2grncxxjq.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2cypxofpc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2izrqztco.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2thjsbvwv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2dsbzkfor.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2roelgrfo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2jxxuewcl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2memvcswk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ujjwyvyf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2sdvxrjwq.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhdgxoxr.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2umidjdom.html


<!-- 参考信息 -->