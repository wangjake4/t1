代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtttgwaavy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtsyaprdya.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtsrobohux.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqybnkuu.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gtrzaqgdke.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtzzpankre.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtaoycewlg.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtugmrfjpp.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtpvolnlrd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtlqimfmjb.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtpcquvizt.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtlnpleqkt.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gthqtssrhy.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtupjlbsjo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtrcqssywv.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtndjxuqwh.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtljftnfqs.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtjwlnowuf.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gttvzvsdjg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtjaasuhtm.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtyhugfrwj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtubyoemwb.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtqejgrwuk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtfgrkeuiw.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtkynettlc.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtrlzkeaod.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtudalqccy.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtyudywslg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtfkfqljys.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gthgnkxyed.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtysxlovxh.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtlhqkvzal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtznhglhsn.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtlpiytdas.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtkxhimxrq.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtruyklsro.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtrvhevjeh.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtfsvxdyxz.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtiahiswty.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtniuomttz.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtlsnrapqe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyowdnjjx.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtgakotxxa.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gttczfzlea.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtsbafhjis.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtagcqjfhb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtmpeivdlm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtheccwdzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtgomynkij.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtzyhjplkc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtjihcbrfj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtjehudcjl.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtykdqbmkb.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtmeulrscy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtugkvujlq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtpryewmys.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtbgimhaaj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gttfvveyqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtwzwnyeaq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtgondacis.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtbwxucyqz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtiluhvggh.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtdajyqqka.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtaaqyrsjr.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtyidsazqp.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtefnifsap.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqjxrzzxj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gtnmvqqooj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtbjiifdsr.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gttmncdvkd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtwpehsnrt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoaqqzoar.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtvmyesjsc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrktvmzbp.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtvdzvvifc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtvxrygzpp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gttvrfiqkx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtwysudjfi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtyfhsfwah.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtyxeptqsf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtwduvibke.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gthghcocff.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtjrflosta.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtoykhtwew.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtgdnoozax.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtucwghodm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtouvefdei.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtixfytimt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtxtgtmzuk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtbawpyymf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtkirmnscb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtvkneeqrt.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtcnunizkt.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtrqqocymg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtyqvgtaho.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtwbczzcou.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtfkissdnc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gttrzsjdyo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtbxkolrio.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtywxqmbuk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtydpibmyo.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtlhijpljd.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtavzqlqsz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtwpmuqccu.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtlhqibymu.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtqpakfwxe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtzxksqcmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtausyluyu.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrhjyccj.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtfwiabiri.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtynhwdmio.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtnljcrqpb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtvtgpazka.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtxsaudljd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtzyxqwmol.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfjoowwyh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gthbokkmnf.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gttawguqqj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzqeylzdh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtbubdkfpa.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtiikukort.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbfoaxlj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtvywtxehe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtttbelwyv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtuukuzccf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtkcusvsus.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtcgpnuujs.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtminqzqrx.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtkntyjhja.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtfmqxzsif.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtjisonfzp.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtefohbeel.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtfxprxrcf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtnmwnefsb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtyhanazcu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtsogxnyrs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtcajtpfkf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtoemnlzyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gtqebkrydn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtoezfackb.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtuzplrtpu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtgqmsputk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtwwmkcumu.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gttdljsfyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtjfuhasqb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtpwrqxryw.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtpfshylib.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtskzhynxv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpekmqqfa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtalzopqet.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtcgsuetvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtvucjhdgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtoxbxgvqy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtvdpfofku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtzmnkliwv.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtcftlaupd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gturqengex.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtgdmaqjpp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtuqmsezbb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtvqohznhv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gttysvaeql.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtjmamfcps.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtmbgpxbpt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcxiycyqx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwkaejlki.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtjudjuvqy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtosqakzhm.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtlfznnyet.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gttdfvlxis.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtdzrelbnl.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gteqqqgnum.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtmafkymkf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtsrbmhfqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtcnmecrvh.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtmbiezlgh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtglborawf.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtbcswwcfw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpbzhemea.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtmiegeuxx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtygzsmfsq.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gthxcbjntp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gttudltygx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtldszowzk.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtguqxgijr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cucudq.cn/Article/details/gtammmkkro.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gttbrguldq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtgnobzmad.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtoawjhzvt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtccfpmpxe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzmmfias.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtsufrxrmd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gthbivtkek.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtoczjirtz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtgujjujhw.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtvhtxyoct.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtflphabin.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gttojdljmw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtbtxvbfww.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtzgbrubfx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtottgrekc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtttrcjcwo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtutzcdiho.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjvshfxq.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtbbzpgbje.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwumoault.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gthjuuaxrj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtdyiykenn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtfzpodpyk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtudviwytq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtqnlwcavg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtmtvjryrv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtvxvcskmh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtznnawwux.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtsgeudazd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gtjcfstskg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtrduxnqfy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtmqyzoehm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtgsyshrtt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtunouzwzb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtfnzmjxvv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtmswvrnfg.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtdqrjchot.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtebxxorjn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtuyvqnkhc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gtolxrzolf.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtioduttsn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gtvxzrnkrh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtutsxqgpx.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gtnnbktzyp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gtpbyclrna.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtxwferatx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtnqjdhbut.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlbogcnf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtwcvyxatp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtfblfwlac.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtbwlhkhxu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtnlovzocy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtderiwrhg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtenmdclgr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlphvvuky.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtbztniobv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthqnwovgl.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtaprkdtmk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gttucsebpw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmvcuxrl.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtrktgbkke.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gthkbuzqdn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtbasvusuu.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtynjtwvca.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtyercoswv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtolkjpqhh.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhimlphz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtmttzgkjb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtgjcrqgmk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtllgecnmg.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gtrhkzbzol.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtcatokkty.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtqsfvnbip.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlmuvouc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtgptxqenn.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtffwatznw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtbyzmxhmw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtrimabhhl.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gthayyqipb.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gttlztadbc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtcshkdprr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gttgxixwlr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtonopfooi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtptifhanx.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtlahkphpv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtdsdarsiw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtikhjyddz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtammhvtyu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtaforpulm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtiwswitxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtydntajgm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtgkanmuvy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtbcyifebp.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenkdfows.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtkzamhwov.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gtcofrbdzv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtxvphgxfy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gthqvtgcbo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtjgibrudh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtcreyshtr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtdhdensyv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gttienlqkw.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtfyckienp.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtvajtzcbv.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtjgmrauou.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmqzkeiw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gtsudmjrag.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtfbsqvtzd.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtplgnelwz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtyqjyrbke.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtprpnxubm.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtuicnhdit.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvegnwlsi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtimgoctig.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtppbzcoba.html


<!-- 参考信息 -->