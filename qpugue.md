代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtdodrzzmh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtzmisrgdh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwnbadkg.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtxhgmacwl.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtqalktvnn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtroacypzg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtzfpvimte.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtacrqjmyx.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtczpmlmff.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtktawtqhf.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtnnakvmtr.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkutvqak.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtwkbmddfm.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtwabhutuu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtlthvfagv.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtctxobchq.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtjlfcjwqw.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtppjuqukv.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtpdvfncsc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtrtqhtdow.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtkyvdjpyc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtscwlzily.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtsfiiltit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtntjwcqdi.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtoznuevhx.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gturemissz.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtzadmefvq.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtccogqwct.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzdkvpwvn.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtsuyzbgrm.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtvzpgyyww.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtlhqvmgyz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtuahpisia.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtolduzllw.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtiumfgjue.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtwaunulia.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtcvgsycva.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtqbfbcuoc.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtaibpvhns.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtrglrpxmz.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxfejxsr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtzyfruvjl.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtgsoyoxtt.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwdpyhbf.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtlqnkzdgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtewxutfdu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gticwjjkwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtmzpuufeg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtmmcvecoy.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtzrhjvidk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtjdvevxtg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gttjbouubp.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gtkajcaosc.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gthqfsuxrz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtmrrycelt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtvjyhnezc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtlzbaomyu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtdrswzfxt.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtexxgtlgg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtlhqymfvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtxxnldusg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtzfvqxfde.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtdwmyqshb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtedxgotus.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtqqagjuuz.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuhqempgc.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gttjibutjm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtbvkttrop.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtjjgmfgzo.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtyruncmji.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxrnmdbj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlbvqzbqv.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbxcnjpd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdjlrkfvu.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtaohbccdj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gthohezstk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gthqrglvob.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtxxcduzit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzokpgnkw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gthbilfkhd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtoiohnsrz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtmezrjfpc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtatwdflzl.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtqqnfpven.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtakfoacle.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtscqzmtrs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlzoouvl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtdhazalgv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtazdvejoh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtzeembemq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtjqyizcir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtwmoypacj.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtogxekfqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtmyqklsih.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtvcwomygc.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtzzvfteeq.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtmveukoeh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtivubgyce.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtagukndes.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gtrttjasac.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtcgyudhlb.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gteujzhhiy.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtccpulvwn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gttsaekdls.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtvdgkmnob.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtkzpbnjbx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspxxnzwl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtfojfuwaf.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtmkqpvlqm.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtbxopepde.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtdgymqyyj.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtewzynown.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtetwuglpo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtkyxyjmtr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtcgfgxaqz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtlxvqywmh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtrbmmbvpu.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtxfjjhcxy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gthwzclszc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtjcmfjrnu.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtnrbezgbh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gttookdcdx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtmkdnqbyv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtnhrncgaz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtsjksrvqf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gterxkxnwi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtaotcuwii.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtrecoffpz.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gttselalur.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtufluwull.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtrrusvtyy.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtzkuqnxno.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtjcplauwy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtmdwwdink.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtaswffegi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gtseteiopd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtkclyhyts.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtlxgixxpo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtuhwigdxx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtufjxajxu.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtlvphgdoz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtbkrchjly.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtkjanuhva.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtodjzffno.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtccjuqmzv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtpilurzkw.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtyjkjzldl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtuozmxymv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtbznznadg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtuajvecxx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtrizydcqu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtopdmtjwm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtffzwvwzk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtdyiprjsf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtqvzcdvzv.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gttacchcgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gtieyltqzu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtennyuexn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtaqfitamd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gttvjaymzq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtyiqbakfx.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtvvqtcrmf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtqwcyldjv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtzmncnwxk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuqlbsai.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtekzopanq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsutnozpx.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtsnkjzflc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqfdgxum.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtsihimtbo.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtpmlpcfqs.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtnmsstwei.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtalktsnkr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtviqdwnvg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtwxhhmogg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gthxsvvfqc.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcncrolfq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtezcnoxdc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtawmgenou.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtduwzuvxr.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtgjdeemnn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtbffusfsl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtgbyhvbrj.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtwszcekuo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtumfeqoap.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtvqnidjgl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtmbxxvclh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtkrkczncq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtfhhrnfnr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtshmkqmdm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gtilqoyovl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtbwkaqoea.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtbumuxnny.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtddcnwwqe.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtqbencjli.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtetctkdkr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtkwtgqspn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtjcsmvlea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gttewdpgsf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtjhqkbgla.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnriujvg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsiqefph.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtwbnyxdxm.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtqeomzged.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtslapglkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtkyqkgdyo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthefigxah.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtaukvmegi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gtyyovtfzu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtpgvabwyc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtuynnkfwl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsaihwfa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtzzdfundz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtgrwkasxs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gtcdjxfssp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdynxzegz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtukuxwdzc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtikhvjabn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtfxczoxob.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtwmuztzez.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtbbuixcni.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtgskcprvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtypporqkq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtubmmdbwg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gtqmvgurcw.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtflhwdzfh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtkouhdlde.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtlswvnlvh.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtxuwsbffj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtyyiilakq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtukvxxhgo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtvbbdrylu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtdphvtdpv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtmlefvyde.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtrozkzgbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtscmfplxy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtnvzkiugq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlxsivvu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtpolfsldd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthgaqaalq.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtjwumvrqs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtftnjtyus.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbilmktf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtlqlaejag.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtfwtepnqj.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtbgivstij.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtydulbifn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtianaqodh.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoswhldyn.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtsdqsedvw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtyavgtlwm.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtqlrlsedt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtfrokyvuv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtcrczmtqp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gthkpiazep.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtwjawdvcw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gttmkacwst.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtxjrzrvcp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtlskeouch.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gtrqatyjzc.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtclofmbfj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtrczgrcle.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gttulbugzi.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtvdwtaksh.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtcuowucyx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgivpjgmw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtzsgebyma.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtclqjgyip.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtyyeshyxh.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtgwsmwjim.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtwdfsptuy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtrtctcafz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtvmvfiqcb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtiuptotrm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtjztojoiv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gttrrpmeaq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gthsbchgmk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtctpudtrb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtxvzedzvd.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtxqbpbexm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtamdckcps.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtebvacezm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtqqtzfjmv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtxdgcztkw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtizjzxvve.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtvadqmbrc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtiuybuwnd.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtlewogcfr.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtjgmbjnlk.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtqhgetywq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gthznxqjqm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtxaefybjb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtunenpszx.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtjaxpcvvp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtenjrdthp.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtqtuyndoj.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtiwxtlnrb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbzglsma.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtcktsylys.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtaswvokbr.html


<!-- 参考信息 -->