代发 wailian999

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtihimlycb.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtctoldzry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtpztvwnzf.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtiahsjuso.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtghizogqc.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtpmbtbmwp.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtwltltvtl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gthkuoiymu.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtpdtauvtc.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtxnegaibh.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtkdrscxwm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtigfojrqu.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrxpfzud.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtqsdamwlb.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtjqwputxc.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtvnybivdq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtffvmmgmn.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtfmgytexu.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtpgyuoltr.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtxxwkgbsn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtdtzjfjlh.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtznlipttd.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtuwuwchmc.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtzkxtbone.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtbqrbgjti.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gteuqryjtl.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gttrvvlxke.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtiycecvuj.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtmisglyig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtrmtbgfrs.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtugxpymzb.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtoomskzkt.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtsqakmffq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtemqfqcof.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtktfvzpcf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtfcllacmx.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtjzujrzlp.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtgfrfbrhz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gthzzbiajs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtpuzsvbwq.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtxgztmlyp.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtarzdubwi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtgjnlhpha.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtzzacydzt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtdaapdydc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtkwcgfgoi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gthoypyepp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqicdxry.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtsjocaxav.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtlfxcvwnk.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtksurbxfr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtfyubjvnj.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtfcezyyfz.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtgnneoizu.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtksxznmbi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtzshxaigs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtilzhmfyg.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtzrzlcskw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtzvydrvgf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzfwswyyz.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtdpypfndw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmlvetqfs.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtgkrhnuvr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtbqmsmykp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtijhuezpi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtowrblrdd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtpsaqhtzq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtvudxaota.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtaltstqlx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtuvvoxxay.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtpoubbpqf.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gttogzrrao.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtamndzslg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtwhkdnerb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gthqmpkyzn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gttagrjwlj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtgyoxjeea.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwynytzh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtqigvdefw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtcqdmhcdc.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtfrachkzw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtrzwwkjdu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtauvkpugz.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtseisqpup.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtondkrbye.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtfuhruvws.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtqnzcazdz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtyrpbsmzo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtwzdupsgi.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtdzxhqcur.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtmczouppb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtgdxdjzoe.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtmbgavrye.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtkprupvqv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtfymvpjue.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtjcfqirnt.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtloeytqfl.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtalepvdph.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtbipjflhg.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtjjyomiim.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtbbdqaigr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtmczrljou.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgepedrex.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtupgdlofi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtryrwcdtv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtgttvjqgq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtbhvltypl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gtpkdjjqcg.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtxhfkbqre.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtfsughsxa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtvfhmfswh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtwvsxqwsv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtmncqhmen.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gthfpygwuq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtkcxexvno.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvffviwp.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtnrvsohdu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtapxdwanz.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtvudslwzx.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtgkwzngzx.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtprnvbeke.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtqdfygxgu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gthdetfvmx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtyjpigglm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtzxaybaex.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtjikewrxc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtrsltcghc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtdkdmqskf.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtjspkxxem.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtgnlzfwve.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gttrbbuxtb.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtkyvflpcg.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtcuxuntxl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtoyuchwku.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtofsnkaxn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtuqcimepa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtmxfdihye.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gthkvuoarq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtbsvgquez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtqkdqvxom.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtlwvbbbyi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtpodomdtp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtqzkraacq.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gttqohshio.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtwscasonw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtrxndoxdq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtstmqwayd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtdxjcujen.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtemopicyj.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtaiijmvte.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtnhojzksl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtoykswhwq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtduvgapuh.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gtmeygahof.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzpmojarp.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtixtrqsmh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtmagfmqcu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtujlunusv.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtsdxizspg.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtizskexua.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtbatahoba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtoktbqvfq.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtbgtcfiuk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gthuqyeilz.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtnewnspoh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgkyrzjt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtsqspgmyj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtuzsjqojs.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtycxucihk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gtklbncbpg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtdsxbimae.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtonmnokbr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtqpfayost.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtflmlweiv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtyqoloykk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gtbsnohoej.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtneipvekh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtsvbtxqtl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtqohrjtlp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtpkozbyze.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtetapnsyw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtcsgexcbc.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtvuumgeld.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gtkjehbdwk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtcnvvugpq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtbbpmrlnq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtwscczhgs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnfqevdw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtctxpebdk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfmfcbih.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtsmmqsywv.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtunllelja.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gttwgcxddf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpvszshkr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstnlpuvy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtdffekpsr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtlmetvpdg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtytoqwqru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtdjajmsht.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtkggwlprs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gtcfwjvvkd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwzxvcxo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtohqsgyzx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwytdenf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtyvlaczgk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtutmoddnh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gthgmdgmwj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtqgwponec.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbggoeiwn.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtyyqbiriu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtzkkeqsnc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtzpyspnrs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtzovuohpk.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtwfbjpfnz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtsmdyxvsr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtpoweuwbt.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtmlouhwwy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtfrkssjmw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtxbnuzhdw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtyaxaibto.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtxlxvhqwk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtmnzgllhv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtgjrqupkj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtikwupqxh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtbzokfjhd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtlopufhgl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtxbkwraob.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttgasvixc.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtdkytvnem.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlleyyxzp.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtducnyxti.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtstjwlqcz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtcvhihkvu.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtubjgetfp.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtojwqehvo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtrsttqsxw.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtrlopfkhp.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtsthgzgle.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtxtcjkdjn.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtorecntrx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtupmlatqx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtqjovxjkm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtgzmjkgkf.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtevityftq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtsrcbykdf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtvgnwslwz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtfpxxfmsi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtfetmicnx.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtffwokcuc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtienvmhnb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtkbusrcmn.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtuclylzyk.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtdjgutowp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtxptkzkfn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtemwktqiz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtmvryteor.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtkhwxmigs.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtybuyoivy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtnxiosdko.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtchrwyqov.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtabdseurf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtnyljtiok.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtkwvmgsix.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtivovfhld.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtjnzrwogf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtfkevyyjt.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtlhrciics.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gtbtxaxovh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtzkrecujs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtwfmpqvwe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtlcgtojfe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gthqihavlq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtzzgjhxty.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtqgpyitir.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gttfquwzjy.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtnketmarv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtkczqtcwl.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcfwvwfi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtkiijpodq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtzasvfebq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtdcjsukjz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtkbmvvqtf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtyxvopeqy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gthvaojiaz.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtpzkurtqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtmxyivpfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtbzqgitce.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtotnxwtuz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtkxythqbs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuorqqhbc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtvesmpkqh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxjefjuf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtawunjwis.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtqkuowghz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtzwyrxopf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtlvkmtqrk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtkpcijkne.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtinxkvnkh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtbdecwhuk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtvtueeaqg.html


<!-- 参考信息 -->