代发 wailian999

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2oasmkxmm.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gt2bcigalxv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2vucuqmhk.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nootsugb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpwtsxhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttltcrbn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gt2tkzcnwev.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2pmbbdbso.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gt2dghkthcl.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2lhkslewc.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkkrtofb.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gt2fgeipweq.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2htogvyxz.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2lubfjwxm.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2mtfcsmca.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uifldixz.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2ppnqrgvm.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2igdmijfu.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gt2uxgrzeci.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2tarqbkab.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2emqolcle.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2ubfsuzgm.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2azynbwsp.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2zskrsruk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gt2qgjnzrvf.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2ryvmihcd.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gt2fwjmrvhz.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2rqerqzug.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2lsvttswh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gt2ledktcik.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2ontqtfbm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2ujabpexn.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2awoxbetc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2zpiioqkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2kechonad.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdqnstkc.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gt2fhxppobn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2jpxdexpf.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yertkbho.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2nafuskhs.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2gvymrwow.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2dscqueay.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmchiokl.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2wumstiuu.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukjydxkk.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2kqeozyqx.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gt2lzuerctr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cifthafa.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2mewtcjtz.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2esjpmocw.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2ksolwinw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2qluemtzo.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oveujrtf.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gt2itdsyrvs.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2yakzyces.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2yemthusc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2qeqljdgz.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2kfjxbyln.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2gxrcgtke.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2jbxtiqwn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2rfeiwyzs.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2atkkckoj.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2xfxyctgu.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2uwkaxoxh.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2ypfnwtwo.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2hvpoazuc.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2zdasbmbh.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2radekveu.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2yuknajjs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohauhvid.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2bzyafjtg.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gt2brvhxndi.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gt2jchfsheb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2qcuepfzi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gt2gmrcyunk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2crgpylxc.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2wkkanjyr.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lagbvwtl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzrviegt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2yppeinyh.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gt2sppectaj.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2fzcodkyp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eokpezhx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2rpzoaedk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2pycuoajr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2otuhxmds.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2hjvvuxke.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sriujeea.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2joenvpek.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2kuktbpwl.html

[G16] 对象转数组 / 字典
来源：http://dali.jiagoushi.top/Article/details/gt2xxznkwpn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gt2zcuhqsxe.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gt2pzhiksec.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2daohbvlv.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2fybklewq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2kegwljdu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2jmudeoci.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2swaycpgw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2msrvrglt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2eeqxkvob.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gt2rkthfaqh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rdrtqhpw.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfawgzjb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2kthzldef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2rlenrobi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2pdmyjucy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2kdqjmkyj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2ndtlziiq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gt2nmtwzikt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2vwhuwjaa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2yzlsdxhr.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2nwcxmbdc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2oruzcsxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vxayiwrs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2cwpmlult.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nizdghuv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ubrvnchq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gt2lmqshisu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2qqxnzhki.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2yiixxrqk.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2ndkfeuca.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gt2hsvhawvm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2wgxrasoh.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2rpcwazoc.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2dqxdquiv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2ewdernbs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxjwxbvz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2fxhmrmlh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2wztzuddu.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsayfewx.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2cyqghrtm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2xndaujcs.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2hdxypreg.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2hrznctdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2zwviommt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2mgqtkmta.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2hmopeixy.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gt2yvikpbhg.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gt2mngxphje.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2ffxmulgn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2ivcrqpyw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2ttqlrumo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2vpzpbsaw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2sksvxnea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vykilyud.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nskiktll.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2nbpfdtut.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2ghyswwyg.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gt2oqxjzbzo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2rgdmsdnd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2moimxqxl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2iegiumor.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gt2nmddonwf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fouzkjhe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gt2ittajtyg.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2yfxbajbl.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2czeuwvsk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gt2oofeljlp.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2tcxiumqd.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2phggwohb.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2hqdxfrhw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2lmdmbluk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2otnjhnso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2ssmhjndx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjbukkrm.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2xafmrhgd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2uavufbcm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvikqot.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gt2fewwegna.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2aaqqxvha.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2zacztgpv.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhrlucmm.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2aifkotvy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2zwufviln.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2ctllzaai.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2wlomimnx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2ttbtreqd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gt2vpitxdnm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2mffaxrmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gt2okppamko.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2rqmsrefw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2vcnqqhed.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2xtmbkioy.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2kryhbazq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2zsgyunab.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gt2jdvcdyoe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2ruqeojvc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2auiflrdu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2fwkkgvln.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gt2gwoszidi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2zywbexsl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2hdcvxyll.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmlzltuj.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2busiculc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ljojmjhm.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tihxocos.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2oddovgva.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2mbyodtiw.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2udyxswgc.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2llcqdmra.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2bjxeyyeg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2xlowtzih.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2vjfdwhdw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gt2akdrlvoc.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2rapnawth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2lsgdjyeg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2isxspwjl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gt2cwwycqja.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2qkulvmyk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gt2fdlamsuv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2iqwrmeqh.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2icgtjtmb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2gydremlt.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gt2qmeaebhg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ujtaqczx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2hftywkqx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2yvvjdisx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2ktpvbpkf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2nxjdiete.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gt2fqzmzbnb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2loudplic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gt2gbksbonk.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gt2ptwjfqhw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gt2syotkclj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2rvrpqzpi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2kitqxzzn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2aavgnohe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2lcuwksbd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2kvimapls.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2trbpjdrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2riixztiy.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gt2cbvrshqo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2ycemlkcv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2kjsbltxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2fwsgdacb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2iqprfxqh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2sawmxaog.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2ubuefxap.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2zzkmibva.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2spwtsoky.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2womaofgy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2nmjzetty.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2uucoljyo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2uolathac.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2hqtejkjc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypeeuhts.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itpwqebq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2amkpknkq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2ojlhvedr.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2dbyujiwv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gt2ynnrlbvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2vxtxbvpu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2igqeqazo.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2azwueznz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2ekxabgze.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gt2pnlruaxj.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2wbnqdldd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gt2ecuuthbi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2mmkmmpri.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2btveflsi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2gzwpvmve.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2lvypjbne.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2enigbfjq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnupcjxh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2thsiontk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gt2sdfjtsql.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2qpvcjtzv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2yemjuulo.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gt2piggbxyj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scbkcbbn.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2vmtncbic.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gt2nfjwonmq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2tdrvugcg.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2ktihxzcs.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2xqmblica.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjckxurj.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gt2qrugjvpk.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2hjhhebfo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gt2djmhsqyr.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2ocvdhilc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2umagtybk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2euavjick.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gt2agialzze.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gt2mrbgzzce.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2eaobceia.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2tufntdru.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2etqtziyj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gt2bwgfyqpq.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gt2ewwmbqqu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2kehzixne.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2jjdaxnea.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2utehvnvu.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2jyvivwjg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2kfzkiugi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnpvourm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2cdmfzaer.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2gedjtwpu.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2rjzanvln.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2cfdzcore.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2guxfwonv.html


<!-- 参考信息 -->