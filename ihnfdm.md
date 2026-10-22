代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtrxswkcgw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtrksqrojq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbaocqaf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtazuxrcgg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtwkeztrkh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtuatehsaq.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtyhntbjre.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtwzufrdzd.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtaesnpcwg.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtouxborzm.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrslaiddp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtmobcskau.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtzrsxfkoh.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtkelwrtfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtgsoxxrqq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjvuatqlv.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtfnwbmxey.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmbcogatc.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtpmrebcaf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtkxqyjecj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtxtqkztvi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtafnrtzoj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtkjebigrr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtlkskalsk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtotomxemm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtuyfmhvoa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtaimxhqln.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtojrayupm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtawzaobqk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtokoozwkr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjtkijhqw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtlsdlhmqw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxpwmffvt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtgzuanldr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtfdulbqrr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqzbgzoz.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtbgqknbye.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzwwfiin.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtazolvxkv.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtpogucbxh.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtsliyruor.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtljtrcxho.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtxmnsuqmv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtsvsliqzp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtglveqric.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtchbeyutw.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gtlpadsmbt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gttfrbetzi.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtiaksrzox.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtvporrrou.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtsmbnchie.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtseajgxob.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtcxcxnodq.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtuqsnyfcp.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gttjyyvack.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtutyrhzlj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gttafnvmbm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtpvefywgq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtfergxkti.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gttnckkyfe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtikmgpehl.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtkpaberte.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtkubsqmkd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtqyxnyaoj.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtxqgtwozv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtunilpkil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtgzaxmydm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtvubxiufx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtrekmkokz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtmvdzelqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gthptzdizy.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtbdsitbwt.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtvojnssln.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtxylfbrly.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtopulgkhj.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtprkpfejt.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtkceuszct.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gttrczamss.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtfhkxkfqr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtwoqlzpbg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtvbztjzng.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtjwspsibv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtlxhqtzal.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtnvyefohu.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtoohmmcrt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gtgcsvaukn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtufaermyy.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtbelludhx.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gttodtulqb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtfluhwlye.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtuqcrjzft.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtdivladfs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtidtmypsb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtdfqdnwku.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzldindpi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtzldnpogu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtqhnqruma.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtwswuiceh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtceuiirqv.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtrgogslkz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtclioghmi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtivdspbdz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtcxjxuhwb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtznbyhyqw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtkqcijvcz.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtkqeggbcg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtuooiwepp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtgzrrxply.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqcviqnjj.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtvmmgyrop.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvgnpooca.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gttrmuvbov.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtzwkulvij.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtpzmblbva.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtcnibktme.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvgwdahuy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtfsvdnuja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtwzaukomg.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtqyvaujrt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gtrygjcjxe.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtfjqqprmg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtigfhyjsd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtvvvtgxyf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtigjijlwd.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtqflyqdgq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtezjqphcc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtqrkzijbv.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtqmvahxnq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtlfqgxckd.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtrssbtwkq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtwzgqyrkv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtazqnqvrx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtrzdjqiao.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtdfgryusd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtkfkgfxob.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtsotxskjg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtzblzeltd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtoecfyuau.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtgmhqcwol.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtavepsxwg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtsfbpwyit.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtbmdexbml.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtpwenfxhf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtrpdokmfl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweosijcl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtvfzolzfs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtgevdsvci.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtxxywzxol.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtlkpyugli.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtxdjmolia.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulwuhmtm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtmyuwacji.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtkltbwfrb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtinvwxqpv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtmctyeblu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtueshoevl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtdgsewwub.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gteiidjcin.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtjjnzwsvh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtcorizmyr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtjwtyatrr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtqmpqnpxe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gtzduhzuvl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtktgeqhkr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtzozelznr.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrlnyusr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtebnazypr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gttdyxjyii.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gtakqwofrp.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtegidmbcx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtjypvoiny.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjutstewi.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtcpgxhflt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtuqehwjfn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtssfnisme.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtfsttnygt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtdtyglbin.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtfxjqthvl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtsxcraxzf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtfhhuhiyl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtzpuqyrpd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gteqxzvhpa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gttglbchzs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnyrekshp.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtfbejkhvk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtiomknsuz.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtrudccuag.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtlwjuyuzo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtsmgissvz.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtoizosuhj.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtprkiuqru.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gteansuifq.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtjxqdtyci.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtuurlrdsb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtlcpkmlwq.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtnftcprxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtsbbbqxev.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtbxthfmyf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtfafqkvak.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtkdgubdji.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtmvsnceeu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtwjkvhzgg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtxznciens.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtbazxvovo.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtkovybomn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtecspzltw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gtyzokmjtx.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtoyuksnhi.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtknjudfpy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqimifxv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtgikvfzes.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfesdlhsj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gthtvzxixd.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtgjguwfah.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtojzxmiyu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtwcdfwkeb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtodvcntth.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gttuncfiio.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmvjzxkl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtjamwxoya.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtfjrpjzoq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtqexvwlwt.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzxfpalx.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtqualpxmx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gthuqkustj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtnqrjldwo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtaccxlhml.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtsoturqox.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtkelgjgrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtojqekd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtbizunojn.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtgrjzsonm.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gttxwvmown.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtqunqkscf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtxflgbuqe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtozzieuhw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtjgzuicpw.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtzvsydolf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtowsbyhrh.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtttwsbjoa.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtznxmfguj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtvabwrijy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtebcatbbv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtpkgsyztj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gttasgfchi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtsnbjqejs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriabnlcx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtvyovojgj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtahjastkg.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtklelwbvk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtlgotzafc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakiqksmm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtzlojdqee.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtnfaqmgxu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtlotltegh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtqbvswira.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtgysddjgf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtdrltjfjn.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtvaurfuum.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gtqbemrfxt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtmmnwvxgy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtoapamhiv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtrnkgmvhu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtytnwpcij.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtakuujbnx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtrtmciwvs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmengvdmt.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtzssbuvsz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gtbhhjpkes.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtahxfdnwz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gthivcfitd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtzelbgcfs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtqevusjmt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtpmsahscq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gthyzdgjdo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtpohkzqbg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtftijsfrt.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtukrabmkm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqogwtwxi.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtwfupltrf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gttqnvvwwf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvprboat.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtgwdwpdkd.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtgpespdip.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtnucewwdh.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtvrayochx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtexmrsnxt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtnsnrpomr.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtgfqutdwr.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtzbqguphf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtshjjuwhg.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtlzlrddna.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtvyysewgj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtyzytlgds.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtccbrzyhy.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgrthdrry.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtzxdrfbqb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtmslqzfqm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtbbehneju.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtmrmkihip.html


<!-- 参考信息 -->