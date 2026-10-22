代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtjnsdywas.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtmnwgcksh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtbdwuouhv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtbifaenpv.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtgxxqrhgt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtpejzvxjo.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtxohyeawx.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtuszuneje.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gttapvaoco.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtbgfipwww.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtzzgiucpy.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtkqyemrsu.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtwiwkthak.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyiknbtv.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtxxkxzaqi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtkringcpl.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtmghcauay.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjglifdyb.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwpgumetz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gttcxigymt.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtznbbupfc.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtnmvvuilh.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtoexadsel.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gterslknpd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtcigooete.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtkwuhoyas.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiitmrpo.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtsulrzack.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtldtuvdkt.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtfcqzjmaa.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtrtzogxkv.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtlzwyigab.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtkvfhjjth.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtpfikzcpe.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtlyxnugup.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtglyvgfgt.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtpeitcuyq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtvixeajqa.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gttftxolkc.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtufcytnot.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtooqcarlt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtttflfmkx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtlrunztwi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtjvhjkbvc.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtayeyvuma.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtgvifbuqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtyuvawnpn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtyabrgfaa.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtgcpuzuqn.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtzlmqfsmp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gthdmekhjl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziwrholu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkouruglu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtkkgeglzd.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtdejtwong.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtgiecejgs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtfxedzvoq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtjxwejkqu.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gteqkhjmto.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtqttyxxbb.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gthagwqler.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gteydeshby.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtidlyrzto.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtawfmbvnm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtlmnkuevy.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtpyqllhlq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtrbnfhhyo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfvwmgoqa.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gttqluobwe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwozkgtdh.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtrueadxom.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtxikzyzcm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gteygmalua.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtcuthraup.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtagqdryoq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtiekfvacm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtfmcgmjup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtlqcvactw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtjuamlwjj.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtjnqgjswu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtddmmawnp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcgupfogi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgntlaroe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtitotxpla.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gthyekiqkx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtocmunrvh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtdmutowjc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzrhgnyvq.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtoxoegqnb.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnibtvkc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtomorsgld.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtiwewvljt.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtsnegjtir.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtjjmrjkxz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtmdxryfyy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtixrrjtbu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtbrnqmw.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtfjdrlxaa.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtbzmegcqo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtcyvmeiou.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgucdcsgb.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtambauclx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtvriuizpp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtopgyauxy.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtyksszsyw.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtkmhiowkl.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtfbclgwks.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gthpyecege.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrehklsfd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtxxfqppyd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqauylkx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtxvobnpjj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtbjgwqnah.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtmhleizll.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gttkievzgj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtiozdppqh.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtelynnkod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gthjlquyey.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtefipsxul.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gttrdgztvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtpcsovrlh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtvdcphzgt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtiaxxrlri.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtukvpqpqq.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtsnupheqj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtlctyhudc.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gthohnuxpv.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtcsutyvcd.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtblmgaelc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtdfarxqpf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtvgrhhhtx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtmshcsrtd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtjycbfpyb.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtftbbdhrn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtueppmudk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtoojdgruh.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtpbuxnucf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtwppkmaue.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtkwoxbzow.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtlwdbeibs.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtwwwgiros.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhkylsox.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtoghpfqos.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtseuyorsc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtcpznzuov.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtqioinyit.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtpwwtjdve.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtcyiehqes.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtwiketjrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtrnmkjhvf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtobxgdosr.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtpgptunca.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gtfbearsnh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtlouadlcu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gteobdjvfw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtmpsnlctr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtulugwjgt.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtdxxmpyrf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtuihafgux.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtuyzpqink.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttobjxifq.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtwmybaxrk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfrwimdnz.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtbedmaowl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gttxnuzodk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpothhlqq.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtemjmxpbo.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcclorcd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtbexakjcw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtsoqvyuac.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaiomdin.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtvydslbcj.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtapqibold.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtnxolblde.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtxisjzjnd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtuirwmnbm.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtqupkseme.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtfgfcwgwc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtmmkuvutz.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtzxpgathe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtmpyuezpk.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtofpywqtq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjwqsnnu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtrquegtug.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbnevtfu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gthteaktti.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtgocbjbcu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtebfccicr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtbgvoqsxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtosgbnleu.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtnpxqudvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrmjrfph.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtlcghlzla.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtrqisupbq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtzjoxgxfc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtagihzelb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtwgdyddby.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtgwecbkna.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtgsbcbzbt.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gthjrxbula.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtflrncxyn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtzdpvlwhy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtwwdacnlz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtnkszodhf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtjzzpyeun.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtflrgkfwd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjqfcwle.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtmqokjiqa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtllpofrst.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtdxfaqsrr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtwvgidrwj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtmufluxad.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtctkfvylg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtuiesslqx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gthukoipbr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtlbdsflcu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtyscuazvi.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtglgozhto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtvsiikgvg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtdkqcspac.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbtlpvce.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtmrcoscwa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gttgrtdpry.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifruhwvt.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtoqmbrbbe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtldwfeyog.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtecfokubp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtgkaqbrjw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gteixypvar.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtvbzryzfv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtunjzlktn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtkkxkhybk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtqftxdorh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtdvriegsk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtkvsizivg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmvebfgra.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtxpnjnyon.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthoexrbxi.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtqtzzfith.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtomsxkaot.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtoweixoau.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtljqidmkx.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtducvetem.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtvfqfiqru.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtnlvkhuty.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtnkraruvl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtlliqzdoo.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtakrdkqra.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtqpyaqroo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtqunkjbhl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtovwijdvz.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtjicfopsl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gtxnwskiqp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtjjpnfhet.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtvbfaiahx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtksyjmapt.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtqgbzmojn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtualyetta.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtksaxyznz.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtxsiblfdc.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtzhfhzhyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtxlbtyeec.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtgjjxugbz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtkeuaojwy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtmimsitzx.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gtotdqaqjz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtnbbbowni.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtviwcvldr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtdclphgph.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtudygoucs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtcdfjyyzg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtbqplxeoc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtxzwdqyfv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrcnjrdq.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtfljzhacb.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtcjlbfugk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtragzxpnb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtiebcnjbr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtymzvrdox.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtpwkqmlwy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtbeoouitl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gteifcdkcx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtrlvgtzsx.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtlxsrqzhz.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpyxlrdx.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtsginfdho.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtogmktdwi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtzcjgveug.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtgstwvaqi.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnxrokng.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmjaxrzz.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtjrtqapee.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtxingiisp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtpjouvtdf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtfidaubma.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtgrgaslnd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtxwkxeqrh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtbobpkcjg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtbwpqgzie.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmynpwbn.html


<!-- 参考信息 -->