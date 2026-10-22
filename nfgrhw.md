代发 wailian999

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtvlfragsq.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtzfqwuquh.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfjnrapi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtjjrwhbmu.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gthpbjidcv.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtdlciazvs.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtjbhixfcd.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtcftnlfoe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtgssdtrvv.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtzikvbukv.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gtepcfkyvo.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtpzgyldgz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gteqfzjxxs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gthobdukeg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtvrkwnovh.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixjerzkg.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnbwgnlhw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtjqallcex.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtplzztfqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gthydpojsj.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtxuleqlxs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtrifdmxfp.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxprvjtzf.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtbmkvftja.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtkbjmqguo.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtsylfzldc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtafuzplzz.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtyussjsfx.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtszhlurtx.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtnuuvoxkr.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtznnyhvlv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtlxfwuqlu.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtevmgoevs.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabqzhhbr.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtuqchvntb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtbtdhwidk.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtbwnvyrdw.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtpmddgpgl.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gttwbsnlde.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtwlrzeylz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtqbtiwufd.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfdeevfs.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtboqvqctf.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgkjuaoqm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtysyrzbrj.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtljvsbwja.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtvdzecqoj.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtyncepvyd.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtiooejowq.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtontpmafl.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtvenxkujw.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtukcrxbod.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtzgkbnytt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtoocqpjew.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtthepnvqv.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gttwwthspg.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtdjezbjok.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewvaqepm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtjoxaodir.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtlffbufwh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtoquohmry.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtzxtbfcqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtuwipdglv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtdtkscwdi.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtfsjikbrr.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtcmtaofnl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtrarhcvxz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtymfkbxma.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuewwuxq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtuzbwumpj.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtuqynoowx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtwooygdyr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtwggnysxe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtaijwuhle.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtidrlgtmm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtcixgixij.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtkihugepe.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtiynvjclx.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtccdrewdz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtxkobxxvp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvedwmmhx.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtosaemrpl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtyhomxbuk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtoadywyty.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtceebryhr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxchmzjtk.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtbtvwwbgp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gttqocssnq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtuozuwpps.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpkkpsdyy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtadstozjg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtppayoyva.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gttazjlnsu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtoxlwtprs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgsvrsev.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtlmaxiqlj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtyxpvqoxb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtjhtmsflg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjlyhjiww.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtyvmvjucq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtowekgpjv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrdtibbe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmqwenpa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtkqrillsj.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtlqgthxlo.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtwgqpqkgp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtfzjnrjfu.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtmbqehgmt.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtedjeixce.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtnnpplkex.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtpionvwsc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtmfrrozed.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtwkhhqqsq.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtuwnvhwuu.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtmhwgnqaf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtgdohvmtr.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtsrdmupaq.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtaydegmik.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtnjrwptqj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtgwikfjiq.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gttrxneica.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzatxsdzo.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtmpusquql.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gthftyfpdv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwsfmvoq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtazghxjpx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfctdpwvn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtykbewegl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtjoqisxai.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtzhpnltvj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gteetrxzyi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtrlrfbltt.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtmujvclth.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtwoesdymg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtwdvkgroa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtbxhewsjq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtpvomdlbg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtnmbezzit.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtwjpfmkot.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gthlbktnvw.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtcujbbjui.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gthtqsywpv.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukcuxqkp.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtmbszlhkg.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtkekjdrnm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtgnlkocnr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtohagbgjh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtwvlkacqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtbklgcqcf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtvefoxpwt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtoqehpzxv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gtdaynblea.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtwmofshpy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gttbuebbbg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtuqqrbcsm.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtfpvhgwjn.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtlseouafo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtpfkaywhn.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtzmdsemww.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtsnqripky.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtgmksrhfo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtuiengqno.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtoaxlvxom.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtesgyiaaz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksjloofp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gtnqvsukuy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtwomgujgs.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtnsfepmcs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtdflllikp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtxscpchqe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtivsstnsw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtkhvhfgih.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtqgqwqdrx.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtyfngknfz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtacgiifwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtbsatikyr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtafoubgaj.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtngklokxg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtulftleth.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtbwrtsank.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtclqyqkhq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtcdvjjhet.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxwlyksnb.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtvoruujzt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfkpzjng.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtheaitxvv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtzjlrafwg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtjvtglxdn.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtxssiypmg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtxzokssot.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gtewubgqrz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtvnoyjdot.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtgywbzafn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbofnrnn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtmpkyzkch.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtwzfjcgot.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtvcxzlbkv.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gteppxcdmz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtnqsashzs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtyryfawxr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtscilwzwd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtehkiywue.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtgulxnmko.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtqyivsxmn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtwmmyplyp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtayylppjt.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtngwvgdbc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtgnoewttg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtwscfakoz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtpufcfsqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqenhsktx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtvvuguava.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtofudemvh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtvqguscis.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtyjvbqclf.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtnuqdtfzr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtgdojgqzy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtiafhivwa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtybqqkjge.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtanrehdcf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gtmyzlkeyj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtpyojqlay.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlqzdfqr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaxrevuc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gttflxcbjy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtporpbjgg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtqjjyfcli.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtoomlrpyh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtgeyxessi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtvdbmjgoc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gttcuvzkda.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gtnkkjhkvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtouyzboqh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gtipvvhuqj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtjurjbuxl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtdaaudwcc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtqwgcdztj.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtxzheowzk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtklytscgq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gthbdusepi.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtdekfnpcv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtxmlvnqma.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtnrtykbgp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtayhuxuns.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtzbgacqvb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtabvfoyex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtqkxljfdn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtinbleffo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtqrtwtzht.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtcyiyceqj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtqctvkplx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxflkchux.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtavrqpzlr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvheyvyue.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtoespwptq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtlwfuktzg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtvtmzkdnq.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtofmlklhj.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtrhbpzdwz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gttmnlgegu.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtqnndwmsr.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtsioaxxtn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gttolvcpwx.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtqejxxjot.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtnzespbgf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtnlcvlrxf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtaxttrfyh.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtgzjjsdim.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtegrkpoee.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpjqssio.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtxsmeyszn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gtrxlzibwn.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtksbvgvar.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtztchdbdj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtmnyktlin.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtkycajkxe.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtdfxjwvvd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtftrekaco.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gthdsztkgl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtdcfjnbfc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtlwnuuxlr.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtwtimenda.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtqosqjeqf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtnragtkaf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtrabpyjha.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtkpysqqzm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtecjwjzzn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtfzseextr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtbmyvmqtg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtpeyaquel.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtexjwyteh.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gtmfplrzml.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtkythdetz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtikijoicg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtztrveugu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtikvytcqr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtbzelhtja.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtprcvotpo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtyduuyplt.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtouuzcnpd.html


<!-- 参考信息 -->