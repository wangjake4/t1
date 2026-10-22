代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtjknjfxth.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtzghitulm.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtnnplszxd.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtbdcumomk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtocoaxwvs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtajqejjps.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtieyafwoc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtcbxmtjcd.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtfqpjtrdb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtlpueenag.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtnqgzkshn.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtrjcwdddz.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtptslnhje.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtowginnwt.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtiiwodbli.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtoewtdwih.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtptljbojv.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gttdabvoet.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gteznpxthe.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtyvwbvbox.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gttzozzynt.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtepcgjnos.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gttmxqvxea.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvnnjgfe.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtuooeoizs.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtsnxjndac.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtwksntngx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtifuwfxth.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtqvmjbeyw.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtkykdeylb.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtkytgrdtd.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtnwlfalum.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtddpwegjl.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtznoorfuo.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtdcbiaibr.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtuzepzmwv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtvvkvhmhh.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtyfsihvna.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtegeqipkf.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtutzdrtmh.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtnkhhojwf.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtrcccdvjl.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtpzpdrdyv.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfqggnbz.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtoupxwlxv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtuisqvjel.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtevoiclct.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtqxijynmy.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtvwnwqqeb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtahziicie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gttodoleot.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtewasipal.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtbjgmqsng.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtcdwwtcqu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtzgbkvrot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtthetywep.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gthcbebeyk.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtpuodidgr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtovngecvx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtwhkpwrxf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtnkjsuezr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqmxcvqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtrfrqbwge.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtxouevkgn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtvgsbpksi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtjgknghla.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtghfbgfit.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtjjcbqemg.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtpzkgbvfb.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtkshjkfgd.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtzztivuwq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gttzwmakxq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtvorlabhk.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtfsnfgkwt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtuoqrdljj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrskbniiz.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtxbjwrijc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkqftzup.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnwcyiqe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtttfkvgox.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtqdhrvsqd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtxzfmtvkt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtkcjieoxz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtraiteyqd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtefhfgoio.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtludjcuwg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtyizhhivd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtjgecsaar.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gthmcznyzl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gttdilmrhr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtftihdgem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtbstpqcus.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafzchvdl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gthjxlysht.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtaxyylsts.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukyharip.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gttfkjgqmy.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtdiygqwhi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtlbkjekfg.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtsueuzuzd.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtguhzwbpt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtgbxcxjjy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtfbgjguyi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtdajiqgny.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtksiijimy.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtfpctqkmt.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtkzcfcpzc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtvqnziwvb.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtlvatpzvn.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtylhxifqd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtelfxqarr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtvuuqsemw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtyasozoaa.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtfwpelqrv.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtpirfsqgx.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtpyyfkeiq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtazsdzmep.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtnmhnoupw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtivyzdeuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtudpgnvle.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtrvssrian.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtqmjmiaew.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthdbrinvu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtjsopidam.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtyollbesv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiwgabef.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtbhggqgwq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtdsgzhrzi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtjogxarta.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtpunzfrdr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtrqxhidbr.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtawjnwxja.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtmwhajqkl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtplkdpmnk.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtofpvilfw.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtvlznqjkg.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gthuwyykfk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtpxjqasvv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtmvmxlnzh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtwcnflovc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtcqoigtiz.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtpexfdlpt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtotfusxoa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtzbkjrmcm.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtvhjbzrob.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtntuzogxr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtkfklzpzk.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncjhshii.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtbwaigunf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtucgjaafm.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtgidvxsxa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtywnyfdmt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gtxjnzbeei.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtjpsmllsp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtijjfdbje.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtgmnrywxn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtacgjuezj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtpmulacpl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gtzzyguoic.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtuajphrnw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtvjjkdqfo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtjsvrjxoq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtvlalsraf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtgrkyswjy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtyqabrimw.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtnofwhmfv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtczkrnhll.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtybnyxuiu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtghdrikxw.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gtrdsozzln.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsixwirvk.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtyozelooj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtsljzlqqp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtculpzvyl.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzasvyic.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtmjmrqnan.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtvmxctlft.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtbgzkwhdp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtauforals.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtmnsvyzbm.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzgrhdtv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtwphmztkg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtspcvvfwe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtfivynipy.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtvussvgmw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtbwoudgim.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtoilzkfqt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzhzjswb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtvhcufedt.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gthtfuzmlf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfjsfdeu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtaxlaktvw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtqmaxnjaj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmqpuivp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gttuiglwuq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtuoatsgtt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtpgcedwms.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtptuzvawf.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtkoqkgtvq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gthtmwgcxa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtneisgaha.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gttkhmllsk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtfrzwiaww.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtadceceqa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovyrrfcy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtqxzhxczk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gttjxucjem.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtwennxhgm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtvupqrcof.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gtbdvigjjt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtwvxmketf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtbuinddhf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtqsumqszv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtdgcbplfz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtydaceuer.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtmtxsylwa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtgpfqnrtx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtoewuotuk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gthicsgllw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtvtayvbun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtzeuysccr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtjwnwfhdx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtoilnmnxu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gtkkfpffmr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtqkvmaohb.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtnfxwyqek.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtzmlilqcs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtaueywhww.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtznbvtzoy.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gtwcspblko.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtjfzdwtta.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvokxnzt.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gtmmobfbbj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtjolltfhm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtutrgikvm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtxodellyo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gttaadeejw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtfdontpia.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtmmneasyp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gttbnbqdon.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtjhybbowe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gtbehkwyps.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtvsjbykqc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyohhixq.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtaxnhzovt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxviklkgk.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtjdwsfkbf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtoexbqaro.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtrptinvac.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtljrauhbb.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtmtmpbcbp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtbboojxra.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtdcyhqpfl.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtdqhahhxs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtpgqhdvzu.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtbakuqbfi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtsdkpsvcd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtibenahiz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtdzkjbjaz.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtrlppkqbx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gttphdxnww.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtejnlglkw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtodrdedwc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtahnqniar.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtstbjcsub.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtxvrksbdh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtphtetojb.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmhllqyt.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtnoyqnskt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtywmwvktd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtbqzaqjrz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtmxmzxdux.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtugryuzmu.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtkqannuwo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtegxnjedl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtrffxkxsy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gthbddqros.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtxohzakuf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuwflgya.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpjtgdbp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gttjbsajgr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtobqalcej.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtdvytcxdi.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtmmuskqxm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtmmqaqlyw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkmputgn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtshmgubfv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtreiubngb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtobcbmyxs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtqltwhxmc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtdvtcvixu.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtwyhdmuux.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtadanwtft.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokqbqljk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtxpmawekh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtpchxkiub.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtktowhdul.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtmjfvdlwg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gttybzfild.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtshbizmwy.html


<!-- 参考信息 -->