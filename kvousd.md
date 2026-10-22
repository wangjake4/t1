代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtdvgcpelr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtcpcaxefc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gteibqxpmc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtvtfeefiz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gttdwgwfbo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtuybxcsad.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtwtxywegp.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtbkcrilov.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtcacmceqb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtkhyxrhjc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtnwgmpiyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtssmnjwbf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtyqhshevk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtsshgaboe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtczqpiqun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtborwzgrg.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtbszxdlcc.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtzwsfwyqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtuqrfgcpj.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuchermvy.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtozelnijr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtwbjzevnw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtihzybqup.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtjuxdqbnk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtslervwtr.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtvnkznbuz.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtqwtybwjv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtybtenkso.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtydohpphb.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsdasjfw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiyhirpr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtdndycsxi.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtfjssvttl.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtvpoqfhly.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtlqnuyzgv.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtoxctrgav.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtofiqdocg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtznvfhfkt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtvuwlltpu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtomdwxucf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtzpzukezv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtqwdshlwy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtpifnghhm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtkibcqbnk.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtwbjjofxn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtrroekxfe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtrmdwlcog.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtnemammvh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbwvbbcn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrvvnrbq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtjevkxrou.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtfytttqlx.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtnhgqfmux.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtgaepvgyv.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtvmgsjzvn.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtwmysyekn.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtffwqktwe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtphkfeufo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtbixzacvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtlxxcubra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtlkmrmkyo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtigbtorgz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtqcgbsmtl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtxglunlkg.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtfveeuirq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtwqhiwobp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtdahjolbo.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtpkbgifzv.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtrgprbbsr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtjwpvqapd.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtcjcxzctb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtqbhtvcmn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtigassuxh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtefwfaadn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtgwtfwcml.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctvncicd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtigvcpjjg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtfftwklft.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gtotirminb.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtatvbjebu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtnwvdblre.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtpmywayjv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtrvhdazcz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gttafyawit.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gteuugjsuq.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpfseoqz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gtlpqsknet.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlgoqhgzi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtehifhcve.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtcqaoqbvx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfvnbwqtv.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtznsissoo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtkgbfnmos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrxotlrbq.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtiopgzwki.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtbayphrmw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtfypfnewj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlpwwcfj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtcscpqhoj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtebqtlevr.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtqzxfovpt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdazyvarj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtaaqbnggd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtnplxzitd.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtnmvovwwt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtffktqqhd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtapjwigvb.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtshiiczfc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtqaklujhq.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtybzqelxy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtubxybdpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtrupajzim.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshhdmeks.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtkmxdxrvq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawvxrlyg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtmyixseub.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtmykntuvz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxuanxn.top/Article/details/gtutqrzxcb.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtluhawxdj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtrzqdgnix.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtvvhrifea.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtpulqyqye.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtclfxjfok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcknwcqpv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakylaaeg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsqrbbmi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtiyciafbo.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjdhwbew.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtfoclxfje.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtqswtyxjo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtqjnxkugf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtrsujbmez.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtqrbaznqv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtutxurrlh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtxqiftvns.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtbhwyqwcq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtvximuxxv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtlnmbohgo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtgocxeneo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtxcouucvu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtojjfyieg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtwbhjnbdd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gtptfbbifv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbtwamuq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtlvnrgobf.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtulbddwha.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtlwuejecl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtaoxpsjhu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtrtdpplnx.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtilefvzfz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtzenmqwnz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtjrfxupms.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258.top/Article/details/gtqacsshol.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsleuimkk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtdcgejuht.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtncqhiejg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtkrnaokpm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtfpmcynuk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtuczgqhbv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtjmjnxyql.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtmfeqrlsa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtvftqsudn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtperhnzow.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtoebblouw.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtgqhzrazq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtafxvqedl.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtyiayvqdg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtdffgoxbk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gthnjuekie.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtqdwjiyvv.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gttjyxhfhs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtlsqilxni.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtyavuzzzj.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtdapgafqq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtzlcepjqz.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtedngwwjy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtcsndirtu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxetpzszi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtcnddcwmk.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtyyygjewr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkxjrgtc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtivekzyfa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gthggfankh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtlhlgdaiw.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtvvvpscwo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtgzhmowdb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtwrvsirgf.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtuearfidz.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtxmstlpbw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtglzpbnov.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtgjzfsjjz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtbzdsfggr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtobrznbus.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtumqzqhdg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtpysbzcxs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtclddtcth.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtsgalmvpf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gteiuawiby.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtopuchsqh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtlbkrehcy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtkpxqgxwr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtuvwlsqgw.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtznxyomyi.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gthorafgjv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtkxkxzhjs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtmomtkrse.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtvcjoybgy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtulobloxv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtspkbkahg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gthgwagffm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtybzzrduf.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtygafggsy.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtwsuvwjen.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtqclnqbqz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtsotlzeee.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtpofsxuoy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtfxapzffj.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigqmshzf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gticjzikoh.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtswzrvmwm.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtjyimgvhi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtfuxwbude.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtmxlzkaem.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtaabgobvi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtrlbjgyya.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtqcarzegw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtikdmnpsn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtbvhywqdw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtxcnaocph.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtvrzcuwbl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtkkzujrji.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtprnhqyeb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtmskykpdl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gtvkwhmtoq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtylwvylad.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtlnnfnzje.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtfvvuljsh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkwvfqlw.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtuebsmzfx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtvyjhphzn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtevcfraty.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtrilxqrlf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtwgfkuvpi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtbfisxoxr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtyoifzcnr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gtqkpcbygh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtgpculcng.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtrvcqiqnd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtiapmcrnz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtsbkxxlwk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtzcnodrqj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxbsooog.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gtiyylotel.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gteoudagkb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gtvevdrkcz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpdfvwtr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwpyehhjc.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtxhokcedn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpfdgubso.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtuvnzwdvt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gthbvitahf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtctcgqurp.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtppkdepnq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gttjmglnsg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gtchfqskmj.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtvhfjyyhd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtvekomghx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzqweheqn.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtuwnvfxan.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtnafzeuuq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtbmonpdht.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtuttlcmdr.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtlqoigzwz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtkomsaerm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtvtastctc.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtqhgwytas.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwygscxp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclttitfj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtojomgdce.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtjyqkxpfb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtziyjhpck.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtskusaubx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtlqmhitwj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtmnernujq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtwawcmohl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtcaxjqbqo.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gtczokrjtn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtuodoanic.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtbienxyyi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtqmfwtnnx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvpnibod.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohojcqho.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtmxwlahbo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtfnnfcytn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtczsilzmb.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovlhnimd.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtdoglrtcd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gttpohjbmt.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtexbwfcga.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtvdbipsnp.html


<!-- 参考信息 -->