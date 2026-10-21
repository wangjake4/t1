代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gthiyjatfl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtkzpqaabl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtnghtihmv.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtxnicapuy.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtydfscivh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtgsjhzybn.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtwpreehry.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtsxdsvpqb.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtgkaxlwhx.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtvcctteyl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtiicxprcq.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtwlyhmmek.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gtxklntgrp.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtyhwwleqe.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtcdjrjczz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtcansijky.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtfzperoaq.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtiljuicsp.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtvtydieyw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtzkowxuax.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtpgqwnbgf.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtskcnghqi.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtipghltls.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtjelscupa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtfakjcikh.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtegnpsgvv.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtnxltslig.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtwdlqrctj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtqxzxbtjj.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtltekbuuq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtbeyhljrk.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafpdmixj.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtknyashym.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtzlepuvkn.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtkruobies.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtztqcxrft.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtzktzzcet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtzmzmzttb.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtzaajtudi.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtqdparqbe.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtkejrspis.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gtvsedfqvc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtoebxntfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtdkwkdlpw.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtufksutsj.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtgkarhkcb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtopedjjst.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtwsezmcbm.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqtulkbx.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtgqrbnjby.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtjfaqnjzm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtjfyjrbaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtrelcqhzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtubpdcdfr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtiizghjpd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtwkdlzsfk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtppddqtpc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtrehyjqfz.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtghsvqqdg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtdigtvvcl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtpymtpwdi.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtebyqndvz.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtufqcwjzq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtwkcrajtn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtfibqpwyw.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtszapvnha.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtjtvopzax.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtddfekfmk.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxezlreg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtikdsgtpr.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtparoskqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecnewrpe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtjnffvcap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtycbwiofm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtkvsweduv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtvqntnysu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtdgfzvvkl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtexwypdfd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohoovzxa.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskrvkvas.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtvxazekwz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtzjldjapm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gthnmdijeo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtmhjuoiar.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxwjvxedv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtghsuvijs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtnmimkcdf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvunykqbt.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtrhgmkbii.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtmdrauwhg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgumhgvn.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtfatpvinn.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtizpmxiqo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtfggyuyar.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtvjjfoqqr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtsrbtuihi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtrllxssql.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtbjrbohan.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtqxxjugvb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtxxumlena.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtioesaqrp.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtmdgddfjh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtjgkvyfcw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtribeadeq.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtbzkvlgrm.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtqzafnbxx.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdlcrpll.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtjrymhivh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtevpoieox.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzrqrushl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvsqnqvmj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtcgimqoax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtkifnjztf.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gthmtxxstd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtwbqwmkwl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtdrkzhzij.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtwmomzkkb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtkpmehjny.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtlaimuwkl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtdocwlqga.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtvzdonduz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtamafhtqv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtxdrcpmdv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtqefxztxs.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtdhqkwjfp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtmgjhnjks.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtwyjhsvoj.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gticgsvire.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtcqnhxtsi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtpjdphpli.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtdbjcazrm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtgexgichs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtearaiyjo.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtjirzpmtr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtcgiqpbuh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpdrmjjm.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtllipeynw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtaelncgei.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtrhbnbtut.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtgmrtmbek.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtnalribul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtgilgiylb.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtivmxbxhz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtexhbutrb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtuuihsdmb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtxvayzems.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtqiaruzba.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtbspsjvwg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtzeellvfg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlymvbilb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtqjipgprg.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtecsuommi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtgcpxekwo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gtifpguguf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtbluqmtow.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtthddjxqg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtzmodcero.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtkhikqttv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gthhxqxiyq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnhbldqtz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzceslvey.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtfcrntxfl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtycsqaglb.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtecajvscs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtugovmpfa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtaksndpxd.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtarlhkdqg.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtetzpwgpq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtjggwttvp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gthfoymfbt.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtitfhfjzn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtnexrtxrk.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkojvgcxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtipkjtahs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gtcbctwuzy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gttigfokge.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtiacmsren.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gtmctrakmd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtdkpfrdkg.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtitzpmwff.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtcbnovokx.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gtqwpgxxvk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gttngrqxyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtujylfavd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtmlddarjm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtegctqjts.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtqxbvfqbu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtnuluayeu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtyqbeunkg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmkppiuj.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtswjxrsmv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtldsjyoqf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtwvprudac.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtjovgiive.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtilxjwkfj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtrzxmcvci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtjuguesfk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtbujvnzeu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtuwwjnsbt.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtijbcsdbn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtfjtvbnlo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtjlazxhkr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtprohdeow.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtilelrupl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtdguyxeau.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtobuqiajc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtbkbvslfa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtbvswfwgt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtpykafuxl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtytfetbvi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtjaomrunj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtsbokskqt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtwafdyvty.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtmviymreb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtehobdoal.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtxdqycwrc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtmdvzlyry.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtrgghioyp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gttetugxzj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtskrsnkis.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtlmrojryd.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtqtcgtlsh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtqgmpoebq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftfewkem.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzqmpjib.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtadvqazma.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtkmvybrua.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtgdwleaer.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtpljacctb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtomkejiza.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtvnceaypb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtjkseoicp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gtkxqdbrks.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gteryvaahy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtaiingdox.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgcjmneje.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtfrngwdde.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbokuzemq.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtrkazuvcy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gtoldmbgvm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtzqvjzuli.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtzgqszjlk.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtizmirdly.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtompydcbb.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtphizlofh.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtihzflaas.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gttusrkusd.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtzmjbnjgd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtqcnropin.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gthixuuxvo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtizyvmrie.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtmuetmimg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtivwftqfr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtwfwcsmna.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtuhpkjmzf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtbleauchq.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtxrakbhap.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtbkaijalh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtrrwcqzcg.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtbkfwxijt.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtdozhlhxx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtppjmbrht.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtbtcrkmsy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gthhcdevti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtyagbkxhs.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtzjvuqckt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtohiwkehl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfzhoitc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqekjtsb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtnanbanjs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtrhpkyynt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtdgxrnzsn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtifwkazay.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtzzuybjbj.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjzyfcly.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtjerhymmx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlowmrshm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtwpenjgtk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtqbgejfdy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtcvotzocz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtnypbjnlv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtqeexzcpq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtzzoyahsn.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtqgczsset.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtyopnpyzv.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtelilvmza.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtytnmmugh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtodvjvnqw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtccweoyze.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gttttblmek.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtlmipipod.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtnmualzsy.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsfkknru.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtsxkalcrz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtntzxlgli.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtvrobixvx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtqothvjlh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtxiacxfvt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtdqzfelck.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtndvpwptg.html


<!-- 参考信息 -->