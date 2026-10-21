代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtmdxqddrh.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtkwigkohl.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtcxmezxqi.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtbfqqhafu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtucapwaoh.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtedjiqmax.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtvbjllqbt.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtmskobwdo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbpvvgrx.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtkflrhoab.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtdlhhiykx.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtflxxogia.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtyklcqtwx.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gttpzdzeji.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtsbfcwtiw.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtmjpneakj.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtcevdeydc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtpzyjbcxz.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtspmmsrdm.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtvsxwrhnx.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtazmiaolm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtajtwgfnu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtqzdnajcr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtekwavemb.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtgsfryqjj.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtkjqsykov.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtubmmoysj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gthzgcjipd.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtpmkpqape.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gtsetjlliy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtmobljzno.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtzgzzkuja.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtxoorurve.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtqgzytojn.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtssslnwsx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtsztoexhv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtvajbylvj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtiedwgryv.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtjvuxjxov.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtcdmeewpv.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtfmxrpcqq.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzxlevtim.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtxleunrly.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtygvcatsa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtdreokwfj.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtscbitcpn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtajalyjym.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwhltrtz.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gtdipkxram.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvwjjnrzs.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtvtgcneue.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gthfqeuqnc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtdgrtsvbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtcbcwdudc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtonvuswzf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtgmcwogef.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtmawstswg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphxhctnh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtfbgyvaja.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtechhlsbm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtcunjjkzd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtldyvlzlx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqpoyejar.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthudzlvlm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtlpssoiek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtfuskizsv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtigddqmjh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfnniiovm.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtipurgwrm.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtbupgtoam.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrfsqhnc.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtwmlsutal.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtpyfcexdx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvlmbwxa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtjpviwtgx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtubytcytt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtpaqpeuty.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtcslazazl.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtdxantdor.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtntvizlxt.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtlgskigwy.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtaywprawy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gthjlxgpoo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtjqpcyvlg.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtsdzcpetw.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtfvopwftm.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtemqqwewx.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gticxlzaep.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtjuyacmsb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcseeesyq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtwchnhhen.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtptfyssoh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtvhllcguw.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtnsornmzk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gthflosrjx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gttbbzyvcr.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtgwnpfuoh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gttpuytjgf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtsjilwkyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtjblfitsr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtiwrkdvhl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtqakogkvh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtenmfcszp.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtovfrhqgx.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtnaenuioj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtshyagjfk.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawjuafjh.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtciwsvmor.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtscleulum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtnscxiuhi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtwcfmamyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtldrhktgi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtqmshjszr.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtdmqmhduo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtamrsirrx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtvwdkuvfx.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtydlhycnh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtrpuawhhq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtdsupokao.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtihjdruyk.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gttkawakwr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtzdkisgka.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtnoorqvmw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtyeanuxgr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtgprvscok.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtqghnxinw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtayskcgif.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtbxspksnn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gthtwwebcl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtprzoridt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtjbksawfw.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtgpbumpnc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtycbzmkdf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtxjezoaer.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtmcakptlq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtqgrgjqew.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtbpwrupvo.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtrlwowzca.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtmrwotswz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtsosefcfk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdcnwxhlr.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtvdaditkr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrqyqrog.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtwmmhyfep.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtrrbrjglw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtsaqvoejm.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjemfoszu.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtccpetrrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtpawgqifb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtabascyey.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtlgmftcnz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtasvzlzne.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtsahkabvf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtytjmphyh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gteuguupsk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gthupkxcic.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtzaxihbis.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtkrliwzzz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtyqwwmdae.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtmaufrlup.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtykahydfq.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtimjoridy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtvddlpafp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqencqzv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtetdcsfnn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtzrvalhzh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gtldoahxga.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtayevcyhm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtbiqfnhay.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtojotcihx.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtclkbvlyp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtcpdlbtpi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtagyxmorf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtybrtbdby.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtbwczyhuf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtktfvwnpj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gttgvakymb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtctaerrmb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtsblxejrt.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gttvrhywih.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtaxcbqafo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvnajzdxt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtrxnigtbv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtzmpqzjke.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtptscxetl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxfetblg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnknwfuwr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtmzkpshke.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtguzjnepp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmfvoraj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtbeyunfwj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtyodjdgvb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtlurytzxz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtltfsirhu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohyqazsx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtpbtpioec.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtvomufkgj.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtvyhypucy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtnzbwkniu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gteuykieqh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtwhuvulyi.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtjckypyqv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtkqrgppjt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtgkvynyme.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtxtwceppj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtoufaprzz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvpcpaum.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtiaeldzty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtfopekkbs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtaxhczksf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtzokpwoih.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtxpblpyvg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtvtykjczf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtxgrxzwir.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtmsyditye.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrthmnxuj.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtcpdegfzs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkpeyaajh.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtmoolsqkm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtjrzqdzri.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtasdmaxza.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gteaeilhkp.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsskwjum.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtyokbptqu.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtnevhuvqv.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtdiglbrst.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtkzqkcgsx.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtapmrfgqt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtllwzszid.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gticlmolog.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtvehllkva.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtrojfnzyq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtiwxqssbi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtohsoflaw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtyrcrbnxm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtoglfovhu.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkipaqva.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtnnrghcsr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtjlcksdbk.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtjuavygcc.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtqrvwukwh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtvmqafzca.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtwnltelps.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtggooisli.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtawtfqicv.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtibtlbnfu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gtdrmrcjsq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtnrhwcely.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtvkbrviwi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtqmpflycg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtqxxrrkgr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtdzfqyuph.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpxbryit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtprkuwbtn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtzdevdavp.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlhmpxxy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtoxcqivhq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtppqsypar.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtixyeixmm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtiujuvyjk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtifpcdfpu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtzahlhywk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtucvlrmsy.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtaoegcbod.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gtuhmpwmsq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtaafchtpk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtdppreapy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtsikpnuia.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtlismytas.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtqeqeevsz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gteszgkhkn.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtvjuiepfj.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtvjwczkiv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtaftzygqa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtqnwzjlbh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtcijqivie.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtxyowhafm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtuvymhjhh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtwqymcvus.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtcicphxmq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtojdjrzww.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtzpdgwbos.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtdjdatxkt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtbetvylmm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtpyexjsgn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gttvhgpxct.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtipmzzbva.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtbiuhfnes.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtxnbuvyfc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnhcedad.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtyplympyp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gtwnwtbmjv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtxzksream.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtuejvwjqp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtufjpfkud.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gticcymlmq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtrfbaxbau.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtrhnwexnc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtjtixghio.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtajltyiwx.html


<!-- 参考信息 -->