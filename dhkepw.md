代发 wailian999

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2bskzhbex.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gt2ntyagrbd.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgysesvn.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2wakgzowt.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2hrarevfw.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2nqydoerz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xmudwadd.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2ewgdxhev.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2fycfyrbb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2jwyghggn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmncswyg.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gt2sjipoqak.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gt2jawxwmrf.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2lttmgjys.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gt2vhllqipz.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ippfrhqh.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2bcctgvki.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2imcceiar.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2cvuuheto.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouzaxpxe.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2xjdyhijg.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2bskxyoyb.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2aivuhzpg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gt2epvecnfn.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2lirdenoa.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2upywmqcr.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2isajyhqv.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzlwuhcu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2ijkbfmee.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2aiwefxcx.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2dxknlckq.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gt2ebetnzba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfuyoemj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2issbqjqx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2vircufgi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2geigugsx.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wemhqoos.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2cqnqjxrh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2vnezknvw.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2asrglafk.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gt2muzrlvxw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gt2mexgaypv.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2etpzmfin.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gt2uareycqj.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2zlbwzvpd.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdhbpsst.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gt2jssmokyl.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gt2hzcvrhpx.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2ligrqsob.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2bzujlqsu.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2belslmpx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2etafvnpf.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2hmxgnrey.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2wpiwdehd.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2eyvntrwk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2fujuofzi.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2fjloryru.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2jhdrigsf.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2loskjbcq.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skalqtvn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2pylkvzjg.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2fqwdmgqt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckfcudug.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2xkhylohe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2xouipsez.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2cjonypii.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2tpuofxrj.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gt2lhbyrdwu.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxigbkpi.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2zdulumsd.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lymcjsdd.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2piizaakz.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2zbiatriy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gt2fygtqlhk.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gt2izpgpiwd.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gt2uwrrlwno.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gt2xiqelpzj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtldkexd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2jrtcvekk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2revsuplh.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gt2nryrncof.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gt2bsvyjewf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dasaukhi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxzgrxrg.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2qqptoqjd.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2lgqwqoaz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2ssnemlvg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2ubywlald.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2qqcdlgvq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2kroqrsag.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2izsqtaaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2qbmmswgz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2kgkmvtxs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2cglsctyi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2lngywhnr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2clmtoujj.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2wgspnxfy.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2tglixiav.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zctoybek.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xknfhvud.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2ukcpmozm.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2micdzjre.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2dtiokpmk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nxixqzqc.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gt2mrljgopj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mianlhjc.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gt2fcblswwa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2vkefpmxa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2jkdcykon.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2umvrhfmb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2snoyxama.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2bmxjuzsq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2eaewdwek.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2cxepypam.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qtepiopy.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2qgutkwrp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdmknogg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2cmtdvluo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2lyzewxeo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuuwvqd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2wmzuegpk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2hjxmvdti.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxsqcjnj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ijcbchkq.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2aucjugpm.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2zabmklrw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2unrvuplg.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2mmgqjieh.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2ackneqxn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2rajsqvve.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gt2yaulwkty.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2emvpqotm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2wicaryzm.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2yjaicjsg.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2ffstspas.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2uwgenoxv.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2yiaxklmr.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2dglkciov.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2kxhfdxxc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gt2vnjpqsse.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2afnoqslq.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2quojhazo.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gt2pmrjoxhb.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2wexyhpla.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2eghqkopa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2tfvpufdq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2aiyuolrr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2auijfxbh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gt2twoqbdsx.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2ujspvaqr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gt2hzmqxcpy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwldshvb.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gt2fsgpazzr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2eywqvruq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2ncrdmsgo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2fcpajoav.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2ahdfwoyc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqeyhyjs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2lwxquetw.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2eriujltc.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2gswsrbpv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gt2oumocqwm.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2wpzuafes.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfvqxfji.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2doixnesn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2ohzhgrym.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2qvhkmtll.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gt2suultpjj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2awgjclda.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2zqedbica.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2skjovyjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2eqdcicne.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2atbzyuxr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2asycdsak.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2khqlkxja.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gt2odilglqq.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gt2chnajeca.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2qqlhdujv.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gt2wpunfcjl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjccghcj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfxcjzbi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ertcfqwj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2mnfezfzu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2peiwyozg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gt2yklygfcm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2ytcdsdpx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2finxfhqx.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmzvasvi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gt2dfeoltag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2ltcsnpja.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2smhzoirr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2nxmdkutk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gt2dpcuuseg.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2mzzbvlgf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2lwtrxuif.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2lvcglpmr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2yshxxoqj.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gt2rhgxfzuh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ehourvzt.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjpldczk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gt2wxmoshya.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2wxsghiff.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2aqwvlyvc.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2rfdtmmec.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2ulwoqccd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gt2mfzegxyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2wdysqsml.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2fmktlnza.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gt2nnjsmokc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2oglauqbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gt2rhvmyuer.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncurwjdc.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdjbrpnu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2anmqdlmo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2jjiryahg.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2ywlwzyoz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2lliiufik.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gt2zzqjdwjz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ygmjzsai.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2odocgtku.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgqyvdxo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2dqiyvmri.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2yncgflqq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2gosalqso.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2rjfmoffd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2kzqscocb.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2elxuxymy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yproknny.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2xqalnbua.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ikxomdqp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2ffgyusuq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2slaemdke.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2olrodpay.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2pdhiqsfz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mihgizal.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2rqoajnlm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2ubvvhgie.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2cpjcchgq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2ncabflke.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ssmyhwib.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2idqfmapn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gulrqpcs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2lisjerpr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2doyexrva.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gt2wxaisapb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2geqjfrgj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2pbholker.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2crjlkykd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2losghezr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2oqokhpuk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2rntxjxwg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2dnsptiek.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2iwebhqfy.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2jcdogzya.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gt2uowpubpl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2plkjftgj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2moqbglxy.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gt2gidzkqiu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jegqtzjl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2gxensdke.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2eaxhxzyx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2lfoifpqc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxdsqlnm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2shqszgod.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2tjawhgid.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2yokmpqgw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2yiriafdf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2wtyotvnq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2krzdbwdq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gt2zzgdjbwt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2tkpspilj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2oxbafdlb.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2rstftmxe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ozelbdok.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gt2urnnosvt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gt2nlsayqmp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2tbzyirbj.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2mdbugiws.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2gcffphff.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gt2bdzctels.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2pobowokn.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gt2daifzgff.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2kulhtfch.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfvzvdvf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2ldgdwavg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2zhehjpqu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2dsulmmvp.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2lgwdnwor.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gt2upwwaime.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gt2itkkchjo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2iaezrgfk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2wymgqxxk.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gt2ixfxtljj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gt2qlcqfrdb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2iztuwkux.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2xjoqhxib.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2hxwsivjg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2qvhkwfsu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2fglfynom.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2zgsljwvv.html


<!-- 参考信息 -->