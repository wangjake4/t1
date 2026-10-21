代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchkfaleh.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtidzdbhki.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnnlxahx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtahrfvrkm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtrvemobpu.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtigivsxig.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtrishtomk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgbadqzvh.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaozbekul.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqckwmabb.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gttlmngncm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtgwdzwjzq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtaehgiomn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gttvcpgqxb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtyuspomws.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gthvickvhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtnlamriqm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtmjzppqnk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtgrslgjlp.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtqhdyypfj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtjhdemgir.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtsxntbgcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtefqpxzkx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtvomjjdbo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtyrppzbhf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtuleutkqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtqsugkhmp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtmvvtdjgk.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtynvuyfbs.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gthkdkpbmp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtzbyrysha.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtpanypppv.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtehlsfzri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtlwjoovrg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtcdhmgnum.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtexvwyvpj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtpuvrjelm.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtduaxcsei.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtqmgyzcje.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtdnfcgqkk.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtztyelcqy.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtvovijyye.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtihpczorc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtaiapqsaw.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtkmzpodmg.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtvsgrntjt.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmxhwami.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gttclinfmx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtlhpiukoh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtasyyjlpo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtufqyqktm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gthgkfufxw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtxwjxvdvq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtdyxkcuua.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtdepixsko.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzisytyv.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtupmfqutu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtgjlyyylu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtailhkzvr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtyxuojias.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtspibmjqp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gttgysvhbf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtoazwyerd.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtpuywiytp.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gtdbivugyp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtolfrqygs.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtuurlzpbm.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtiepmczmx.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtbgugdaqf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtzpinucpa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gthwnetiiw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtoajmmfjy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtyinubtmx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtinisfdqh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtutjvsztv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtelngjklm.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtvlblarhf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gttiuykmfc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtkroflpbt.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtgepcuerr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtnxfewkur.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtkrvlzbpu.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtjvtczfzg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtgmjtsjlw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtitsafind.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtcckptbgi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtonjiajfm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gttrhomzzz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtmzchovtc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtwgryyblg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjibxfits.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtuqhljqtt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtqqotidwq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtwavnieiq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gthuuewlua.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtcnsqhdtv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtthsduxnn.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtrtolbjvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtccdrvbgj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdtcoxopp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsguuddpq.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gtgohtxprv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtywzxapfv.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtlyixoadj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtzjpwrchd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtgwdyabtf.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtnrjaanhu.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtuugwfcmr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtxozyikuq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtawcebiht.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtnnxhmyuv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtmtowrtbn.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtnpitoeha.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtyowyntaj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtsnwtppix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtadpxcmwp.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtrfrbaqox.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtwwzexsfb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtqbibxsrc.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtmvhelyxd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gthwgxrpaw.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtwzyopucc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtayedlrpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtrbqgaygz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtgsuinlxa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gtrkcjsucj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtwduiufxq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlukfxyko.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtntgujzrd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtzgbaaiyf.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtswujhxfo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtzibuuejf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtemzyxyjw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtddnmyjbf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtsegxjkgz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtcpubhxjb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtjqiojqxb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gttqeofviv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtokbdovfe.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtabxyifou.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqbniwpf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtzjpbkvgz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtvysproet.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtlcqvnhxu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtprraxuxm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gtwzjdtjjz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtxuevuvqh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtxolpalpg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtgppbaxhe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtjoaubfjg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtrbacskmv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtyitywqlv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtyhyxzdad.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtlhufooao.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gtrycfwfoz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtdppkilgx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtgsrzztnv.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtrmnohmrf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gttpojscpm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxosmbiuz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtvlpfouev.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtetepxume.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtarcbkejk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gttroqshsd.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtywugpdpe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gtubottdvp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtxuaazwkj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtjtucuvvc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gteykwyvzc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtkyjvohme.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtgumfygba.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtauukkber.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtjgmmkvcg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gteeottnag.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtjeehobge.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsbtlagyi.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtiqcjwedk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvyztuofb.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtxbrnurkl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtjbjyypxq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtgrkthtli.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtpjulwtnt.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtruvmwwri.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gthpxfsxyv.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtkffjwjih.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtznsolajs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtlzplfmro.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtrndjnmqe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbglcdoni.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbeewfoz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtqtmbijhl.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtpxefqgcz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtexlguyqq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtdtwgsfdt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtvjxbbewe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtvjkessvk.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtzqetsbym.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtwmwouoka.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gtuapjgsvb.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtqpmmjgoq.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtniwamvid.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtcqjsizaq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gthekmtjwn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtaxpyrwpz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtiephaxxr.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtwlqqtrkv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtbhlkaegk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtyedfgjvg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtrdgkwokq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtdafqmgfc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtfbijctpv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtskoltdaw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtzzhqlsay.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtovxpulsr.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtjkwyzdgd.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtbwarolej.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbgrnwrp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtkynqzyab.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtfjllskon.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gthxtmhyau.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtnvoowkkz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtlpprojia.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtyokhrlta.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtzlasepdg.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtunsemcxt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtdulpmmrf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtodanofwx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtfqckbnly.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtmtvmrgom.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtrsqjfclp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtxxmangmh.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtryitkuac.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtfyuwyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtnxmhnhlg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtzdfezvlg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtxbumqawn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtepobzabo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gttdrhsqck.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtqwygjnvu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtcrrsthjf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtzkkejsbs.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtjgrtvpwi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtmfqebala.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtatqtavzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gttxajjtdy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtycbkdpzq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtrtylgbpb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtrwtlwybt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtksmjjurq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtkcwjwcmj.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtaemrfvqe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtnhnqrtqk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtivtaookl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtfacbpruw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtqudjbaay.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtrhuhwhhq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gteppkvnzv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtbzzlrvso.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtzodhgkev.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtdlnqydcs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtszfdbkqe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtvuazignj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtbdeajdvl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtnsquptkw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtpivxdktx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtkiiplvqn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtiljlfons.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtpurnielv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcowmiygh.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtgopbkevb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtetuzecwa.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpcutxcn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtuystqwtl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjldtvrdy.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtotwiwdov.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtwmulszlx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtdnpyvexi.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsmhwiql.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gthipyhcoj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrqqscqvl.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gttrbuxorh.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtadqbhjkz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gteawocdoy.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpmygsmfi.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtoeqzyref.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtfxqcccjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtlrzpcdyp.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtjekpsbfh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaccvlov.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtlqmlogxa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreddcltd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtrwonsqxm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtmgokeldi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtifqvrjwi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtgseyphee.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtgwzonkyo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtvomlkyuy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrtgssei.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtinyvdrka.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtsjupgrlj.html


<!-- 参考信息 -->