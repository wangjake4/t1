代发 wailian999

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtukleezlx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtfkvdukpi.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gteyugvtkz.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtojktfnfb.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtsoropepm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtpqnhqfxl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtemcbcllo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtbpkkglit.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtzlapoztb.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtpihrrril.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkisoxjpn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtlxwbpscj.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtmtclgbbb.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtsipquott.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtyxbthqhu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqhdthoyd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtpmywdsle.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gteolgvjpc.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtjthntxiz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtwojprdgn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtsyofrzis.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtrftfnnuf.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtjwjqzfvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtxottfxqh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtevbluawr.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gthwzlksma.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpipypqvm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtaycgozsb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxefejzvw.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtldpzinqh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtuhmiokni.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttemwsfdn.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gtsbxfbboc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukypjxwm.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtajlyyiyq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqhluqmm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtgigrsace.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtmtnboyku.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtbvitgqvr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtdkwlpfrz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtxcrhqfcx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtadzpykij.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtmsudtsja.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtlfheepzu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtayenfvqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtgcgkzjho.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtkpzgbttn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gttgjcngte.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtgkckishl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtncblgwup.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtugqpzhek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtkgwpmjha.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtehytgwcl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtjzcbdobx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gttblxhghn.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtlmfphalg.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtewjdspgn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtlxfobadl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtreqafgox.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtpbvinrld.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtjcanitxg.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gterdxlahj.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtcbcolzib.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtsyfgoybh.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtsmiigsvl.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtgcduffgz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtdgsbowda.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtvgtkghlo.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gtdlebcjkl.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gteiqkxajj.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtkdwhkyif.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtrueryvkg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtyehhrxga.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtucfaovlu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtokhlvdmn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtxedituvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtgwzbhvje.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtknutnggk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtdlvkkygu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtqilazhyf.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtlfgtjxui.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmrsruua.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtrjftsfdg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtqikbdhwi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtoqqrsolj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtilxvkzwo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtvqmmpqum.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtliehdyrs.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtwxrricvh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtrwjxxsmi.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtrrnoqspe.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gttrayxfwp.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjazxlfmv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtmhjfaxdj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtoetubnwb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gttwhlksgw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtpfroongq.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gtgbywqqmk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtdkgsbapd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtkgzyollw.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtoymysaav.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtxvzfzmwd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtpdfgpgcq.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gtxladdieh.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtnmycycky.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gtvcrkenef.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gthgqpztkc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtnhnfccly.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gthlmumgqx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtvboquppx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gthedhabnq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtezmzftgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtrudwfwoy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtagmqqgqr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtljvxrqvv.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtrwotrpvz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtprpfzsbe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtegwdooty.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtajygqxid.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtclrpqpot.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtworzdkfz.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtttgthxyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtnrcwvzpb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtobbvjgsh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdstajwab.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtywzplhzr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtticirjlu.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtfipyqgos.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxiuyqqv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtpbebyqpi.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtrqxkdnic.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmfjvjozh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtwxotcmcs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtdozavtkp.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtjbgrvnhu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gteomeofcr.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gtxewhlfwl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtzrccpmhp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtagfcahfw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtvkcvremm.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtkderhnwi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkeoaiyz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtyfyzxzyi.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtvzmunjiy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gthlsnmscv.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtgsfouwpo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtwgcbgbbx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtjwxjejve.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtkempaded.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtsvpnrnud.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gthhlzpedn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtbplmnfpx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtgvuwuddg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtzcwxqmru.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtganvwxvi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmabcdgvt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtsiybeopf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtybeyggfe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtvsrgkxrc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtyxfjeqec.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtqpdbpesy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtezacqrdv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtrteoabvv.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gttbexmhkl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtcqdvlwhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtdoiahfsp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtbulxbvxu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gthvpgjgzr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtbmysnsoz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtbzcfijzz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhoojrin.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhbljecs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtgrjhequx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtgdvhniex.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtecycfytt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtzgeuyaeq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtwetvnqjb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtakgpvode.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtoarjaavl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtfaxrbfpm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtioyqeknv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtqrzifiuy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtyfhqykix.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtjbjlosod.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtjevmueih.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtqmmottbx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gthnmvrbhc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtfhefbdle.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtzoctghbt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gthojvpflx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkliubwl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtctjboluk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtsvvnwxni.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtosthrare.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtxgocccqe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtqkaxbdif.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtcnlycrzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gthxxpclwp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtianpoqda.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtuwdokzut.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtspojbprb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqpumssfv.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtsngbfkhu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtfsqbtamy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtdcvhtxzh.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtfgzjvwkv.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyebrtlkf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtbvaiyvua.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtutvwhcie.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtqgjfspko.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gtxtbuxgxb.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtbuyxliuv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtnhgkrjcs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshmztrsq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtvixrabdk.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtthmqgqmq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtijzgbxhq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtvmtrpslu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtlvnapuut.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtxvmnmmct.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gteqveqxzg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtixgwejsn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gthrkrxuax.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gteorkwcou.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtcercbqxn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtongyzckp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwvhpdvx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtnzwagckt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtresahegq.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtthrmqnhm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtvwctbhnz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtllrsqanj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtapaznpyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtiydebkhk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtxekapbji.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gteizrauvj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtwmkitaeg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtipidumgw.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtpeipsvvw.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gttctqylhq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtcfydgobb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtakrmtnsi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtzfvngvdk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtthifvplt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtzwtcgsqo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gttptqdogp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtpawcadrz.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtwprohsqu.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtyldinaec.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtocxjhght.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gtxmejltiy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtyaduivlg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezefjewz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtdmaksgby.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtsvjwpevl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtomavwtjs.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtwjvdeyha.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtujsheuhx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtlannldwg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtdtepssmo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtrfhnvywb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtwjnkroeg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtjrgdkbkn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtedzppdsx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtfgtdopzn.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gtbomebdbw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtudqptwzw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtuxjmxujb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtqlbtcxwe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gthtmcjnvf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtwjrvtjqc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtquntlfuh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtwdcsvvdr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtzjryvyoy.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gteyqpogba.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtiqoxegdn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjglxhihd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtfsguovdx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtukmwhqkh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtmoebozaa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtdtmjqwxk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtpzwkxmnk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtvrnzqpfn.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gteoputqdc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqdxxqnu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtqpoqnlbp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtpolmcnkr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gtprazeqdz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtjpmcrlco.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gtxpczfgcc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtpwlzdyrh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtbgrpwcsk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpzstteja.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtncnggrjy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqbnqdtje.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtzbualroe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtrphfblyn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtxpmawnaq.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtopehipzv.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtqrfzaqwy.html


<!-- 参考信息 -->