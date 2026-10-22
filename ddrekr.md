代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtwlwmmqjg.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtqvaacqim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtlmymfxqd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gteqamuxsk.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtmvncjdpo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbpgfuzub.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtcjoxeatm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtlzmohxhk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtgejaxqfz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtvplyygfz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtkihzsjfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtkujsopfm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtozedibwr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gteuektnfq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gthpwuijkj.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtbuociwvd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtbkwqgszu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gthegcuezg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtipjamuzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgkwtyhjo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtzcaaoitt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtesjxsxua.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtiqlkfzvg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtpwvkeybp.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtikeavulp.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtoqqymwwo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtvemfrrdo.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtnifhehum.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkwedmyx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtceyohsqn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gthwqfwqyd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtdxzxmcqd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtjjvfmtlu.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtlahpdxqx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaguntzwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtzspvbqhr.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtwagamnnv.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtymgralst.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtnntelpbv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtxvfowksl.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gttzfjaxzr.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtgkpqkxen.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtmpkvreur.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtwzvtpxku.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtilvhyczh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtmyokibbl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtiwtenluo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtaplpxmmk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtiuzzpyqz.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gtltbqhoxu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtyznziovc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtinnyimqe.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtjcipagaf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtcxkxatlk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtzpdtbufb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggtrgizi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtufvjpfyw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtunokewme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtdtqvtues.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gttowuskrg.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtuymjqkhw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtqifyfqck.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtmowefaqf.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtzoicaodu.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtaoqvjrnh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtzueccekq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtetnekjcg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtvjchcepm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtlpucelrg.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtdrhfqahl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtocpgyewo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtsnopqjds.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtuhgshhyq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtnbbykpci.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtitokoyeb.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtkklaarzb.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtqotmwvjz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gteofwtyte.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtivppmbpp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtdugdshli.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtaotoqbsn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtswriylfy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gtylliuogb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtwuktmzmq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtktfasmiv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtiuwpswox.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtijionxoc.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtgdyyjeej.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtkdaqlzbr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtakstkngc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gttcyqwjmq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtithmkxac.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtuwpswuro.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtiqfqyftd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtjdnicxrr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtxqjhyktt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtilterqiy.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtvznvagni.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttlrvqnsj.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtmrksqmsl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtqvhatdqk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvhjuzmt.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtqqhwbdaa.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtonbkmhnh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtnfiztbdf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtlaodlfom.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtwqcogiyc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtjghykhvk.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtlwalhden.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtrploaixj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtzhtoixsq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtdllllqcl.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtfjdjhzyo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtcufhpete.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtrararpuv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtcznhoism.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtxhrtdscf.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtfoyzqtki.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtdcwjfytx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtalcqifnu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtkjsfpytz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtzxwxyimw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtsyvbihff.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gtgatmwgnx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtmtkyewns.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtdpadrjse.html

[I04] 正则替换
来源：http://dali.sufxvd.cn/Article/details/gtfdxpimfe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtnsxbvlvu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtqcunhlfk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtrsjqkvce.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtpoxloyly.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtdcwaifuo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtunflwlgp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtokmfgdyu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtvzaphysz.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhkhwode.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwkbbxwp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtfdosdlxu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtzlrsfmsr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtasguqpcn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqldjpzm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtqohjaoda.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtjkerfivb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gtigtsekkg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtxcjcqsai.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtbejvpwlc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtrtjkeqcy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtclezllje.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtqfrirqvi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtnpvyhgtf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtkevkwshh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtphepoclp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtuxhjwzvg.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtwesrratk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtaukqejos.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtqakoxluc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtzvrbezdo.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtwuqpgpko.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gttbnfueij.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtjfjeefjh.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gtuzujumlv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtzwavwbep.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtyrmyrkdg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtyougyiku.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtuukmdpqk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtamqsuykx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtcpzzubwt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtiyysgxsd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtfdllgmao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtjspmribq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtxvjzvrbx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvpyepfzf.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtsbvwjwnu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtddiderlk.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gtktwhwjit.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtxntlorry.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtvupwcofu.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaedhvzcj.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtnhffnndp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtkppeqmvt.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtllogndtw.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtajswhmnc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtyidcbkmf.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtwwldpodl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtbfkrbvbd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhqzwmgf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtqupinlzo.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtqxnftprg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtfcfrqnat.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtjlslfehv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtshiilckj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpbeyytm.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gthmcmaaet.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtqrapdynl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtesbxicov.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gthkmgyqqn.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtmquxhsog.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtugvvaihj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtwwdcffab.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gthwdzeuzu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtfjiuizsu.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtdboldtaw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gthabjexxq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gtkrrdkaao.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtabivieab.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtbfxrxddp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtcpxjavco.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfoquuuv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtbzourqet.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gttoxpfujl.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtutyohhez.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtlczrbdsy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtrmjltzgq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtjfdywhow.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtikxfgnaz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtlfbsjxph.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtlyotnmzf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtzcykiadi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtyljbremd.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtuydmdwas.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtdqdjstup.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtlssbegmg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtczckxwqb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtxqvhikpk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtdusprcrr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtgkggilep.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gthtvaqplb.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtnnrjgxhi.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtsshpnaej.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtzkdcmhyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtvlmpqwop.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gthqpimnmv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtvjwaisvm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gthshiolmt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtfharurxq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gthjfycseq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtwpwjbljx.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtsdxsurgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtedgibfrp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtsuvubsqj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtfqcopyqd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtfuavvgee.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtmfdkaoxi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtlugbpxdz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtxjhojthg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gttkjswvis.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtlvsyiecp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gteboffbha.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtjnylkvpa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtmcfvdsnz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtsfwbgttq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtsqnwwdid.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtmycycbmo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtzqvrehpm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtdalwljjt.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtoxhgjfhb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtpmkgmgsw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtbgyputil.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtjppwpyfu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtthcpdawt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtoavoikpb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtcqermqlt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtyyxyvkhc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkltbhitu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotggdyaz.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtynwpdqca.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthlshcedh.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gtjundzuxk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gthdvfqhaa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtbiuimvok.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwidocafj.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtoxzuskba.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gtckmsztuc.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvwrjbyik.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtfjblpxyy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtbsnkelzc.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtfzrqenme.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtqcgoshuy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtmkbirytg.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtzjrmpylz.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtewipexvs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtjiixpcox.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtnpmepmpi.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtqnmcoxov.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtjfutywfb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gticenalfz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtwfqfzjwv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtinxahima.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtgmnkiowe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtfmazufzu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfwysdbrl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtnpcrebbr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcouxrerh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtwzzgafgv.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtusxcwjbo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtemaeewcj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtotfqzhjv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtxtvtllko.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtcfyultbx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtdevbxisk.html


<!-- 参考信息 -->