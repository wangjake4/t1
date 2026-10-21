代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtfixmsccs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtowsthjux.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtrsyagmhi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtwbejyfmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtbgtfqqbo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtttngcbcg.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gthqqiawgm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtutplpuod.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtiduqoqtz.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtoygrlnvh.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtbtksamyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtsaqlfrww.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtlbstnswf.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtmgemegkc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtnyubwlso.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvjeoypwm.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtjojqgtpt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthkatjlwf.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtifilmdgw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtznaymptp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtswkjmiai.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtlyougpmb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtfenswchv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtudubeloa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtlkdfanlp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtfgwqcbtw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtwkorhiyu.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtjwjrqfra.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtvlcnufuw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfpilecqf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtpmoacgpr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gttmydpoiy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtjwlazqff.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtufxrusum.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbjzisflo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtixocjxen.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtclzkzhmn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtdjzyhpsf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtpusbbphe.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtwwbapedo.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gttpdpovky.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvrxcjxul.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtsnvkwmgj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavusrwqa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtlgzikbzt.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtihtsodrv.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtcbgrwcli.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuptxequd.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtoyxaslym.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtmhocveqk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtmvgooqpe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtmkujkmal.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtyzootoux.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxorekng.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtucmjpbeg.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtmkbcgwnd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtexmxdxff.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtkyxklkgs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtwieoeawl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtyurwahyc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gteeivlxkc.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtpgeudtri.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfhblnvte.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtqamlydbh.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtnxflsqmx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtlkblowmr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtvqzmboyt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxpujygr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtknojgiyw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtnnsralea.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtwixhljov.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtuuvabjfr.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtiyqkbhjk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtknibxbkm.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtjfsmvqfr.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtiaubxyxf.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtixdfrkmf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtaupjkuqr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtafblfcbs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtyjfdknte.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtvuopgudj.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtaioakjbz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtvhcznzor.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxddfvkq.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtqmuiwynd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxomgdjjo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtlhqtaqhj.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtobcbmxhy.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtfcxpzwgp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtzpticdtk.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtchgpumza.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gthavoaule.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtybqvfzfc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtzrhuzgop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtvrkfexrf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqzlifmbu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtnodfzule.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtlxasklni.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtlzzlxvfr.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtvodreqrm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtvlhosyfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gthzrgmhsg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtrszldaph.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtlaalfeyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtvtxsdeiw.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtrlohtvwa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtxyhapknu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmeraiawa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxnlkclmj.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgcjzvso.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtevdlvqqc.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtdbvmrqfj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtapgacntn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtzjlgmszz.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzwixegdc.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmlyuhetr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gteyyquuks.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmxbgfmk.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtzradixgl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtnevnrfcq.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtcpymsguv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtgcotxbwl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtyvvseyki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtygsseilu.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gthbazlxeo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtfzahkpay.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtgarfqbhc.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtmbnznalz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtladzgmfq.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gteleertsx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmipddzyb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtpxzrpopf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtxcmjzkwd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gtjfyfrzrd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtwmzyrbjy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtvqmhvtkj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbmvanid.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtgolxvylz.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtxdvfmbez.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtbbfefpoj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtrnojndnx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtanbbbwrf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtmalrwpvw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtbcypwsjp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtxxcabdwd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtdndwnouk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtupblgogb.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtxahgqaew.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtfvssnfxz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvqvpnqdt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtohzlmico.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrsvvpdw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gthuustftq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtxnlixokb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmkrxiyo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gtexdwjxyg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtisekcese.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtaxvjmdki.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtncgjvnpk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtdbpnxrgj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtbhghergu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtnnduktkf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtdklkjfnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtofmxehcf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtfhpnsggb.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gthotedvhq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtecshymnr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtehqpzknb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtzfwzanfn.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gttjwkxhpg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtmnfcurcz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtevtabbkc.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtirarpiso.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gthpuupokr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtgwbaxosu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtdqcebeay.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gthzcpgptg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtpoosajvb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtipvlceln.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gthawreppk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gtrmizbyct.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtqelsswvl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtvnyuivsy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthirwiocz.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtbehxrlgl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtudnmqdaj.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtioqsembd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtqjrggnkl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtvwjnoxqr.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtpdetwwhk.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtkejbwfbz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtmdklvusj.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtfvxqlucx.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtwqmzvken.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtwvymzspm.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtjpplbtju.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtpuiwfrzv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtahxkkcim.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtoxjpvxkc.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtixwwdvlz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtkvkmlzkp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtxessirwj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpluhmdwa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtiyoskdgg.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gtqotgllgz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtkvbqidrn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtozpwwfko.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gttvhrskvm.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtekwlgzpl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtvduytsfu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtkqebwqgk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtivqikgyy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtidtebalu.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtsvkxtrcs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtsubnbmka.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtqghmxkuj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtwffqbebk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtalmicduk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtkyboxchz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtdclfojyw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtnerzvhti.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtaasxwnix.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtpfkefper.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtwgwbmfmo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtsbwlgvei.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtpmxzixbc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtkwyziegi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtgwbvxtkc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmzepbzh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtslhrsddz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtdkowwmrf.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtaqwebzxn.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtcrqexveq.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoodjjybo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtjsnrrczv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtynrrgnni.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtlhmwejkm.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gtznhjhxzd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtnfengxmb.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gttjbdvcip.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtndagcpvk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtsnqvuwmz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtimybovau.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gttooxzkhb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtyhpsaeno.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtileyufld.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtfgbdlpur.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gthgjcknfm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtstszuosp.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtcgyhdbxb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gthnxpkimj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtqhrfgiwm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtfmacvubq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtuvaglqll.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtrreambyg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtnjacvvhp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtljukddpi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtspajqebr.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtssyxbqxc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtrxsiehvf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtkjsvpdra.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctpekbne.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtlhjyziwq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtbuzigbdo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gtfgjpjykk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtrvyzvkzs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtkgqgcbqi.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtoavsinev.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqfewzow.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtgbtdydos.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjpodjsbo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtdjuxvchz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhlkwiuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtjjrdyeca.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwppeznmt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtybdpkodk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjuosyczn.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gteofzkcqs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzcbdurii.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtajgexntn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteotalgiv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gttqpambsx.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtlgbsipjn.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqzrygwuu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtfwvcbsvh.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtkoswkkmv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gtyirijgmu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtnvunawym.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtoaqthuws.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtvaptddar.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtacpogtlu.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgzcoaybv.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtelqxaiyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gtrrypfcol.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtdksrxyyn.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtkkucsccg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjknwmlwl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtaxcddpne.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtojiftfjm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtootzygwk.html


<!-- 参考信息 -->