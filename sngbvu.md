代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2ljmceeot.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gt2jntwwnyb.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2flewfsbe.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2fcraolzb.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2hntrhlet.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2gjlypzqq.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2thfptmcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gt2cgdurwjg.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gt2xdxxewbg.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2vfjelolg.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gt2gueyexea.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2yqrfgflc.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2byctuaru.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gt2riqfztsx.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocmxtvlx.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2ieigyzyg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2yaajvaxp.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2deptpkje.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2dupwewhh.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gt2navwjgdt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2xaryrzba.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2knoqocvo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2dmfbzmpw.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpfcpfvj.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nhodfvvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gt2aonjmioy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2yssjusgh.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2hitpflpd.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gt2ryggrzsi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gt2gibdchkv.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2nloowzjs.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2wwzubpdu.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2fapsiqyr.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gt2ulmirfoh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2bcauzacq.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2ibrpvkwf.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2apchswgv.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2virjwfkn.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xusfwjxk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2tblmxeow.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2yezczyxl.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2amrmlpan.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwmvngik.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2hgiaivie.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gt2rggkihvr.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2lmstehpk.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2slnlneen.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2vkajwbyk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pohjxcpt.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqdrogkt.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2zwujpvin.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2smiuyldx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2nlmcomiq.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2iumovzpa.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2mizxphcb.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2wricpcmx.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2yvjkbqjk.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2dsflrpah.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2wkjqkyik.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2sskfeifo.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2iuumnmey.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufdtxpdh.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2jrajcjeq.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obgbdlaj.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gt2gjwzfloq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2dcugjnid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gt2bemxoddc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuogomyc.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfaljqgl.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gt2xbarbzfg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gt2hhpfjkry.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2flzqvabx.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gt2modkpjxs.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2sijcbcej.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2rajxhffa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gt2tggxqfbo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gt2vrhvpatc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2nbnwcbbl.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jajulnrm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gt2jwuprwyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2sictmxlu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2pgbqlzcl.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2wxfzhska.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2cqempnqu.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gt2orwndusr.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2nbtquogm.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2pqmabntn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sblbjyiw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2teokuior.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gt2rekixoiq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2bnkjvgqh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2sfplxnbp.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2twaihnsw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ucbfnmgh.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2iveilwsc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2kgtumhaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2zafrnzha.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2zahvzgor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2lgrhkiyf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gt2cctjjccg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gt2nbqcyzxs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2zgrurexg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2jkcrocnp.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2ambibkyt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gt2vfewvype.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2csoakrak.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsfgnaaa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2nvgnkvrm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2jbyumkpk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gt2cxmgwfbq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2wwecquld.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2rmvmfrza.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2ejqbpwyy.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gt2vmtdrtwt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2veffghcx.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2gqmtpdhq.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2ejorgtvt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2bgrnclzk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2mrdcquyz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2jwzqwhyi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2mpdkngcc.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gt2agjfeyhf.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gt2nvexxkgk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2omsbzwsq.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2vejeacrt.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2nonuqrso.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2ajmswewz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2zptoeofq.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2hmxbinyc.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gt2sajgcgnt.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2njmlfdxn.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gt2sbbawuba.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2qphnnqjp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2igwatwxz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2jiypisss.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gt2sxawnceb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2wxffyllz.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gt2mkegnysa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2foppuzfm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfyznckp.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gt2rycimfjh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2qfkkoqvq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2vqektndn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2azhgbhje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2xpdswbjo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2gktfifys.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2uimxvnsf.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2nbfpiuag.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2asbmuzix.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2kemwxdwh.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2hkvfbjwo.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2crmgifha.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2irpqkgio.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gt2hhvoohsn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2urhnfmtw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2giuiyyju.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2dwxgpqsu.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gt2emnaihdz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2mkbnivvv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2gyrefxik.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gyftvias.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2mbpbcfkx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2lctejbbp.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2uvygqbvv.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2oogyusuv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gt2ceuwjmoo.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2yjyxalix.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gt2xdllcgwr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2cwarofyh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncqojiux.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gt2gnwrkzys.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2cwhgwygp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2hyyzknuw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahvmfurz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2udslltsg.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2klyjovjj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2hijttidc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2dnwxspca.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2qopotyhm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2ekvfvice.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2obxptoab.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gt2sobpzute.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2iylpaqmu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2qvohjalm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hdyetsvc.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2xcheehnr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ehamsqzh.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2kithndjf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwbcwjzh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2fvqowgyj.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2gmredurh.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xxsirqnf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2lxzmnswa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2jntedssk.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2kvbzpmeg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2qmxsjuni.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2psvkztek.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fjygxlbo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2hteyccvb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2wosesing.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2rqkqcnsj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvwerpbv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2wmjqixey.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xndbmjku.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2voujcpob.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2assczsrb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gt2pigfizbk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2cuwqacjx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2wowvdazy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2sfnemyze.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2xyvjcgrp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gt2wrrocxqq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2yadbuuvu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrytkbj.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2werxjygi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2mglddjhx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2meoltjhj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2syjndwnl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2ylvpduvr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2odchtwtd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2tnblxyfb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuemldlc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2zoengonx.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2apoxrldn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2glbpqbsr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2enhjkjbv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2fsplbobg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2jormskwb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2stfxysoy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2rcpecjhr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwzqmukv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2dgnadfbh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2dloirhql.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbpvqfol.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2eudzcmol.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2qbjqpvne.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2ssfrpspx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2phwhtosn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2fyxafuru.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2lkzekdrz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2hdytqmzd.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gt2ojgvtuga.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zprdhgwd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wszlbcie.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgxxdjwu.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2lfwqmhfe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pslusddn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gt2fonbvlph.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gt2kfpgyiwv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrhhlrya.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2axhekpur.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2pvvmhzbc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqvcvxhy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2sigoqujt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtpodcak.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2dasnrmnz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2ghvlmovn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2wfgbebzk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2zpvgaryn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yhlerujs.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gt2myftsqic.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nkxjrjes.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2deblzfqk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2trdustpp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2wmxyirvl.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2adwxrkud.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2toxrvrgb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2jozehqgo.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2bnhcwqds.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2yscfdpfc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2qgededoz.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gt2bnnholcv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2xagdwrwf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2rptwutiw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2nsbawgdd.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2yziqaezn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2glvrvqmw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gt2qwofljse.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2dzlqsbnc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2cptsbpcr.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2ohnjtzfa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gt2gywbbktb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2zrkhtjbt.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2qejgaxvi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieqdzsqu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2rlmvdfsa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2limpvbmz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2rrevufbn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gt2ogfdrkrz.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2ynutsbug.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2udqegtdl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2dmulxnch.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2vzeqoyru.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2lzipxayd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbathjep.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2tzjfgzue.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gt2gmrlqkqh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtpzbgcx.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfsdayhn.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctrshgjn.html


<!-- 参考信息 -->