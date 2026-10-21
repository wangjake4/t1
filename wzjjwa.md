代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtuhelvqge.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtktwgyemn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtmlmbhocx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfakeedmi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtdnqetqab.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtuoindwhy.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtqaxmbmmw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gtarjrpvts.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtbdwpijve.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtfyeskeqz.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtdbsjaxwm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtwkhgjjzo.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtjuknauhe.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gthnpaqtrv.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtpdvsxupd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtojzkxgwy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtcbvauiru.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtjgqsdgnk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtfxzmmfbk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwapuebcp.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtpzzdjjji.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsrvatsto.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynmnrdej.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtkqfwhmvj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtlqrzsinq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtazmykzkr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtipybbheb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtitixqofr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumzcwqyh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgloursjz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtlfrusoey.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtbqervska.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtzkguxcyf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtzkfpljjx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtowxijnsm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtqcgtwlyb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtygxghpkc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtbuzyzaec.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtvajmrbwu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtqedmajpd.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtwjbkymyf.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtrtgvzdhb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtjijuduog.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtpuzoldpn.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtaivawnhi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtocgoltzw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gthvkxyrxh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtovokhbom.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtpbrpvdaa.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtbqwikoak.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtivtflzow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gthqhzzcdi.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtxxytfuab.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtktaxmdqc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gthahynvrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtzrpvwrzu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtybngqqdg.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtnfgvpuet.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtoicfjywh.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtvcicebrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtkgpyufhi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtrycnamna.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtuquhsjkz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtylxbbzin.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtnrjejfph.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtzvlqchmv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtbseorkww.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtzrvxslfi.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtqglpdpkh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtwaycueqz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtuhefmvhm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtuounatuq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtelktqozl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gthoqduwaj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtweyrxsie.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtekpuvpcu.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtxiwervbz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtcmvhjckh.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtrnannzfk.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtmzqzpavz.html

TS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtjkvfmwto.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtuukmfsql.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtzmpjqzfj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtljbwombx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtgwlxduov.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtdiibibbr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtpphounjc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gttruzitdz.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtvjqllmza.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtndsqszgh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtloibmvvp.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtahqrcpkp.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gthgiwaqqh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gttnvdwkll.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtcchpjpix.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtcprqbvsl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtdnofumfc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtlxeqwsam.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtcgkffebp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtvrtifwyy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtsinswavl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtphssinhi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbcblfam.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gttgxfksit.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gttwskewpz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtkljwqbik.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtoctrmqvw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtmxyuieqx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gtgcjsgwps.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxdrfnqi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtsitugjzi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttcpiecqe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmtbfqamr.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtnizmwxfd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfkirpbee.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtyviylkdu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtkaisjuza.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtrdnzmkzt.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtiadttggs.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtuhiibspm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtlzxtzrkt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtrghwmlqu.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtlaefimeb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtqsednkkx.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtqpoaiwmn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtipojnouy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtyymmhpzr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtcmfmgmic.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiofnmzm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtrwbaxcoc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtkfvpnyzo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtcsfvinmv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gteyupjztt.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtxwcvvmbx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gthowypkeu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtskvgjdgd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtjtxywmea.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gttzfhagdu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtsukrwymr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtlbhiopui.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtcuzlwqlf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gthmqdtpbm.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtvupsfwuc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtqwlnmnaz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gteoagypri.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtgwvbjdfc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtseymhzbg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtphjorjzm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqakjsdns.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtgjzokosp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtxxxregbv.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gtyizyhujz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtuifcspyi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtlraekxet.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtvkbpgvpp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtprkiuqyh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtzqejsqov.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzajgcfch.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbdpagpe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtbjhmvmiv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtcihhgtzf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtwfwmbkde.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtyelbsojp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtvqjxuyzu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtsebckuqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtahaluzbu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtviybktuh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gtofyathmw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtsxsuvsem.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtzzsawrcj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtpfuipuev.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtxqbclbli.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtffjmveeh.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtlwahgbqn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtghnjyjqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtgvtiuqim.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunzwpnhf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtpzseogqr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtjqrhqsyw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugbzjfxq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtnwfbgieu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtnyolgnpi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtvrusxozd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtsoqcmszt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtltznmhuo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtwicjfzdf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtvcxkwgkl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvtavbnra.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtzsqepzmn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttutzgeze.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtufwrcqax.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtwjpyggup.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtpsxusqim.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtnsxvbkby.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtlznxcomq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdrgcpvp.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gttllrcagb.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtplgcgmhq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gtdvezlmei.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtqfzcopsc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtxpbjvmla.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtvumtibii.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtqjtxvaic.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtbemkrwqq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtbfepemcn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtonrgoerx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtuzzpztih.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtncncxsfe.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtarbzxwym.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtrzxuomew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtdohxibed.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacaqqfcf.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gthaeffsrc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtqtimudqj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtbofgfewk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtdzzslsvd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gttfrjfbli.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gteaeqfarm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtfxrdthfg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtvkzcbjrd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtozqpltkq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtajdiexhd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtkewdmklc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtfjsmlyeq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaitzhwpq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtceizrenb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtgnbfkrhb.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtsqwafdhq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtllyjjodz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtnvwtcjvv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtuwfrakqz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtlvszekrt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtwzflaigt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtbquedwou.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtfrwnrrdh.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gticweeilq.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtkotpxswy.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtsilsxagk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtpjpaoozw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtklucvayl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtqzzhhvyy.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtljdknjgl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtxtvithqj.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtbymwwkck.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtsjnziled.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtwuhcllqr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtbyoglmzl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtfpinibvf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gthkljwlte.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtpuurxufz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtleiuqlum.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtkmdgaxdu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtpirztnml.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtgnaviayj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtorxcxqyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtbczrswuv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtntpyjvqd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtrjrbzefx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtagcrshnz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtuycucvvn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtbitduggh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gthltczdjl.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtvqrwnqga.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtdcbvtnrp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtzyswftii.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtngijjanx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtcxywqvxi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtiifviegj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gtmfvzobqy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtcgrnaaqz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtgspkzvta.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtptfmaiou.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtrzsknomw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtvrdzrtba.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtutnxnbre.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtqpmevrvv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtdbnrcgza.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtktgxkhxh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtqlkorwsh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtppvzsxfo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqbiwwlpq.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtnpargzcp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwfwprmek.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtezmwsdwx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gthgsrslde.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtdqtnwvsc.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlorzver.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtdoznvteh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggkxxhpf.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gtbvpeppah.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtnfmjivlw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtoryaeymn.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gthujdovej.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtrauwadqi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gttxendsly.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtekeeccec.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gthsodpjzw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtvmguilgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtgjrnjvgj.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtewrsbtar.html


<!-- 参考信息 -->