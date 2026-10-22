代发 wailian999

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2tpgjiumb.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2vojmthnp.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2yuvayhme.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2afmbexwe.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2chepapcu.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gt2igmqondn.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2thfzkkyy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2rnoskjas.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2ivjkrtxl.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gt2ltgevxth.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ueuuqmjh.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnuidbxz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2luruuogo.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gt2mmlomqab.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vejkcigj.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2rtiupbmy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2wqxirpbq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnkwngyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gt2qvfkwcyh.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2xcontnrn.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gt2iadrkall.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2nfvghgmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2xsdfmqzr.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gt2equwmnyx.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gt2ufuduajg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2ffuicasg.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2dsqcpeac.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gt2akueoqgo.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2sqcdllfh.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gt2kixlnkoq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2swetiwpr.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2pqnyloza.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2asmegilr.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gt2mtfertgq.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2oeydnpla.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2unactxcj.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctistuot.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2opavxctq.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ugyoirmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2rkawdqqq.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jahvnhvb.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2kbrbbcrm.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzbjteht.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2apxqgydf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2aqsrqoid.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2flntijan.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2cxegnhvn.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2twtwxkcs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2kafevdiz.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2ekuknapw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzjccoes.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gt2kfruizwn.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2wseejnex.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2vawxlqqa.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2slugafmm.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2ayrwldfz.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2oeoscbms.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2irilcism.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2mfxstzgm.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gt2mvbfduet.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2imiejfmk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2zoheqkjg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2yjhtawig.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2lswqtekc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2kxbmgyuz.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2fvunvquv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gt2jpnihksh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gt2nxbpteaj.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2gzttnrvf.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2quewkzep.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqbpivye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2idjovnft.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gt2msdsvlmm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2lhgasvta.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gt2gyhryowi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2ceyvlozi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2jzjkadsp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2ripmywir.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gt2tufgobjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gt2qvpwoxmx.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmtutken.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2gffzlnxk.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2nnxopxkw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gt2qfjppwzk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2vyffjkve.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2mvasefow.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2dzdptuog.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yxhtapcg.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2iqbtkavx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olwnlhsh.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gt2fcvvncmm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2ahphcqcp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gt2sjansxlc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2biifwocf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2lebjfuqw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2bmwcrsih.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2znjvcjys.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2jdhrxcos.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gt2tsxsixkl.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2mvhrgxog.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gt2tymloibm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2xxinoncc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2qokkvtxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2vgjaelsg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aummnpfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gt2esqarjvr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gt2kzztfpck.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wtojyikm.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2vlnkrzar.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2rtcujdtg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2lkqfsqbl.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2mkhsutyx.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2pdezuhgg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2fqvihztq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gt2mtakpers.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2pdfqabsh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2lgtlknfg.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gt2basoyzad.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2mkhnzaeu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2asontbcf.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2tfhdplfn.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2yxxllxjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2xmerusin.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gt2gppotnpl.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2dswvtrvm.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2bxcsnvub.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2prjygdws.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhbvmchr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebnzfasn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2ejemmcpq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2rsxnglob.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcbhecbm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhtixlge.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gt2dmphyiyy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcjnfisb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gt2woboagju.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrszsish.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2ngkxcdoc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2comyoswa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2alogbolx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gt2nnmegeuh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gt2ogefzums.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2jlirqnzh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2cesmpvrv.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gt2phtkrckw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2pyhzzfek.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2qaxvfcql.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuftdsdb.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljaebwhf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2gbfsharp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gt2sxtdeijx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gt2jvwaiusb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2buzqldfy.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2yggvvxsi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2ssbbwyum.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggrswvvi.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gt2mrpbhlmm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gt2fygpakth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2psldqwyn.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2mgoiseph.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2igucstao.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2namlmpzd.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gt2ebsagnrt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gt2yqxyrifq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2jvmqydjb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2ytkfmbjp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2zordykaw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2vgabhddk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2xveekkdi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2dggtnvxn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gt2rrcfiovp.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiydqily.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2hemzxnwk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2vdwzzbrq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2nilbugia.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2qmmnepyn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gt2kqpnvbcv.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywcucpep.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2athryees.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2mgesxqfz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2dtxapqrk.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gt2meehizll.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2vjgptemo.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2tjxiymxy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2ygyymdne.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2tugqmttu.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2rztznozh.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcdtcmod.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2ucspsyis.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2oattaqof.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2pwdpfjem.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukxrxkji.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2belitsvp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2jbysrkrw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gt2rkweyeid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gt2toauqxtv.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gt2dtjeafqo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghoclknb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2ksadbscy.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2djdnaldo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2mdizttcu.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2cwpgjilr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ysrmkily.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2nmsinqlr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2iijsyoes.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2wxfzpiml.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxerdziv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gt2lkyzbauw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2tcynazof.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2ncngcqqk.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gt2gcalvuuq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2icvrmikk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2dldkwtoh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihscocea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2qxhssprk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrbzxpub.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gt2uibhxfbi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2ewvxllat.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2fpaghkit.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfemquay.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gt2mprieaav.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2qgkyhwxb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2tzxxpcro.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2slhjthir.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnyeymtv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2trlhtghr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdwgmlxc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2lhkiraif.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gt2qffvrnrn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2fvqrjtrk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gt2oopsaoed.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2zpyrtybk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2fioxroit.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2iycmrtxi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2sptidvlg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2seqmzixa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2wvsgycuy.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gt2tpkltuom.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gt2clnsskyt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2fidqatxq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikmzdafr.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gt2viywtvbe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2sapcmmyh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gt2wbkftzzn.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2eanwdbil.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2borrcvyl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnymysag.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euqsqpsq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2zwdxqjaw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2tgtfjnkd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yejscehl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnmnvqsz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2srdmglfo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2cogcrneq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2ryovgrhr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2fxelqcjg.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2iqmatcla.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xnmqstgs.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2nuegmlke.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gt2qiuxymhi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2iyifonny.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2uttzroef.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2kpmtlluq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2fihjfdkk.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gt2oibrwmuh.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2ptqfiqjb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2ygthpvzr.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2sxvnfdfw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2gtyajjbv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2yqgfxwsg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlsxczwq.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gt2meqkulrj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gt2rkfnnngr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2tmjemgog.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2bvdzglfj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2malsorev.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2mdeuzruw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2anyacecw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gt2oqgxgvus.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fokwjope.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2jrrhbwjx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2epfzuozn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaxqxyph.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2zzojaeoh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2swhheuvx.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqtzanne.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2sxgwhcfo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gt2uxkfoecn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2rcfqcsei.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpikysm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2txoijamb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhkozfcv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2nudkrhvm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2ijsthqwn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gt2xzjguchx.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2kduxokub.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2blbwmrov.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2qxhysita.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmnwuznj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gahlqfbl.html


<!-- 参考信息 -->