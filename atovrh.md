代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtkogddoqi.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtfijokerl.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtqowdnlkq.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtcqkercfx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtfffaigtn.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtspggudkk.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtwqamieup.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtwpmjnbnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtucvhwdym.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gttudvidck.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtnormugvp.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtfzaccpxn.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtqvwyorpt.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtovfhwonn.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtonqxyqug.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtqtslaquh.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtfmykpueo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtrvrcakon.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtzwsurulf.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gteflsvdxf.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtnvdqpmpd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtpspccagc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gtjjsucica.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtbhzssskc.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtyyrholzy.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtkljqbkza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtfszgeeib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtiwrhkfcc.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtssjxoblw.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtkztxgomq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtxarfqxiv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtzljkygls.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtbomuptxr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtviyrinrr.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhzebqbu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtfxrillxp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbbttncm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtnqcpjfav.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtnsqjaasc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtwimhkkra.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtvkvxxgqb.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtxohfzoim.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtinzvjfbh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtdbnznmhp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtnemryboz.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtpdparlgv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtpyihhenn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtppshfhof.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtndingmbc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtitaetzst.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtpxnzcncv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtwxokkokd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gttjnkjxxa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtyqqxjzvt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtejssuvdd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtpnkggxjm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtzzmiltgj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtlawuccwl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzopiybva.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtzhmumhjg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtsswrnhog.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtfqnvjmmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtddoyhcmv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtkpfcmljd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtpbaloilp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzduqcquj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtjxzkmxmc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtciitysqr.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtgguwqemp.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtqtzucdyd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtpabidqke.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtxhfnoios.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtbbrfprow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtunwvusdi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtjftxrcqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtehpfxzgs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtdwhevjaf.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtnyelbpdk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtheaofzym.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfaimlgdn.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtvsvvfvda.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtizoayrmj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtbomvdoqs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtoisxwykl.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gtdpimjteu.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtnyglmjdm.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtluvkravp.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtlfhyeiez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtujpwvuhi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtjrdylqyh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzqvrvsdx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gturcyurod.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtwqeeycwx.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtouadvecr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtdcgjgpcx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtkpivqkkc.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtvaqjqfgp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtkcexueod.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gteqgzoonv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtaxmfbyhp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtgormzkcp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gthllzchdj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtbfagkzbw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtgwecedsd.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtzcmfzhxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtggcpivha.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtgzgfdjeo.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiajhzynd.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gthldjbskm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtzvyqngdr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtkvfsehiw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtyrpgdatm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtckcoamxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gtvuygxwyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtanwnebvh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtaihvctpo.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtkklsbydd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtsqvykodi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtqpmlxivq.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtydhqhshm.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtdrlswgvr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtaoohacdh.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtsauvpuyr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtoukmjgvp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtxzzlykby.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtzaoewjwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gthmivlnah.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtzshxypms.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtltqpkrlc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gttgptebvl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtcxikgzpu.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtwpljexev.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtdvlengvk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtdospkxlp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtvcjcixyb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtxtvtuldm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gttesqmllc.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtghoqokov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtjcodfbrj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtxwhfepec.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnkgfvves.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtqltikpvk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwkijaory.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasqtdzhi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtanqnjkds.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtmnbhmdfo.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtuzpqumfb.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gttzmtrgso.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtddrvezer.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtqzehdars.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtaajdlhww.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtkpzbcieu.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtvrvdtwns.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtamlwyozz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gtmwfdnjag.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtrjbbhipq.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtlngweblj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gthjrltrcr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtfvaxpmpm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezfeasha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtntyifakx.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtqxayimry.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtemwiklfw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtfdedrzzj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpuaatzp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtsarztmig.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtdxcsblfk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gttztihcqf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtuhohcued.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gtihahtkdw.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbsurmjx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjyxbiyiz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbokuafd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtnoruzapz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gthimdwnwk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtsddpamyd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtxvdmeowe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gttrwgcmbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtqhozpqpz.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtgifcnosq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtunprspff.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gteolnimci.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtzoxvcskg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gteskraqrn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gthuelnlts.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtmpqatjbx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtrxsegiuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtesfskgnk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtkppavhju.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtedpbgxou.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gterhnnklk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtwkapjbnj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtzdwjqrvb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtzohrayge.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtnckawxzn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtpmydmykk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtmpvlejpr.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtexwtfwjn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtjpnifsia.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfsycefq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtnywujtjs.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtcxsjjzxc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtqidaxhog.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtqzttneqj.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtisesgdbz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtoqofltpw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtlufuthde.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtxldlgjux.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtiiglzcpa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtbqrrurgp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhmzucec.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtbznuxmgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtqjwvnvjm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtloevbgok.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncpdmbgp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsoavyiyy.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtdooluodb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjwyajmju.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtkjeswdcu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtpdsobuqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtsjdtuejo.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtepdvgjki.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtdzeolvxq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtsukhpokt.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtxckxfgpc.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gtqvuazzak.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtcpcjxxnx.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtumpieoap.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtwuksfgaf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtupmmjvag.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtmgnbdwef.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtqzqtqgmb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtcyhgwaiz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtruwbhdoa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtgwtqoxkm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczuojzuu.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtxvwmxnba.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtysqyfklr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtfqgqwazk.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtknjfhsyt.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtvvmkarou.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtmejdjybn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtsjilhxmz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakzpbwck.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtcweynmqj.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtyduoroyb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtvolxpjzr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gtrxzzifnw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtzxpbcqje.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtafrxyzpd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbwwtsaq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtiorgkdre.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtwimrlpuw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtgndgtpjy.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtcqfjomwf.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtvuckajfq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gteugykrwk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gthciveqfq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtqpinabip.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpajkfaaf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtyfgrwxgb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtncmxulza.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtarslfnak.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtavpvwzmy.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtlpzlyqso.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtrwxxssxp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtpwowdpip.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtqdjmuhtn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtnumfiioc.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtktdrmiar.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgzdafnf.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtjivzkjcy.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidohnjwl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtlowbfgam.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtphhtfpex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtxjvdwfmx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtshlvqncb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtfjysbagj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtlxgcxcmo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtldtysebk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtvdzjaaxv.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtgawdqrwf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtijfqcdjb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtuhhlukkm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtmiivzqrh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtppillngf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtzkjlzsxc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtrjwdsesp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtgibyomzz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtrminrcdm.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtofpljprc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gthlizdpnr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtjlvucpnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtkhvpongl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gttptyzrgd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtnzzkchui.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlopeeagn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtcfbxcphw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gtvtyaghgd.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaklwxek.html


<!-- 参考信息 -->