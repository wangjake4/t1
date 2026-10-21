代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcybplqzg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtklldtdni.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtfcdhtrbu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtrqqzhtbb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtrahuylkw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtwchkwqop.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbujryokf.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gttakkcsbj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtchkscptz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtytwozfse.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtdrpxfpfv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtsewjkafh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gttudzoikc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtywtsfrfh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtwobanqyx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtafutuzny.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtrwahrefz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtnzkmtovj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtdfdqjxnh.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtuqpmtvoj.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtzkxzsqnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtzqkggubd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtxovobskt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtfikrappb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtbiimhcgf.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gthswnehoe.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtdlhhyiad.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtznncpjvo.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtauueanhx.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtpkplwmci.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtiojttfuh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtmmbayiww.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtveniglsj.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gthfcxbjaa.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtxzkczsft.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtnvbfafgm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtztbklgdd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoumdzbna.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtzhqpvmrg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdazaqorf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtvuhwmpwd.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtmltgqbps.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtnnzprzbi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtulnkrqyy.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtwyvghpyy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtzspezcdy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtqfeoapwc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtlqyqriqq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtgpfqwcjo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwjjfijn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtgzeqwwna.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtrefnvrqf.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtipvpneeu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtxrbynztq.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtxfnunejq.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtypmrzdrl.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskadcfwq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtgxlptwti.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtltyfizdk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtriyttscx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtozdmdegn.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtxrroatsn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtkhjtattu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtempyjdyi.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtvjlozbmz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtrwntysqv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtsxvpwwke.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtebmcmhjf.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtgsjzqqvx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtyyxiwurx.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gtfbfsljvj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtkecqerro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gticubvmtc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gticornvsn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtomjmbwkx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtsccxtvqs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtyllwprhx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtmwzljjyq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtenphwtho.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtvclfexgs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtgndwcads.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtryejfljk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtgcgoajih.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtsfggaqpd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtsqabxfhq.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtpdiexqhb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtvbyjyjxt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgjymqgzv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthzjvpesl.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtqbhlrwig.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqtexabyt.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtcvzhnlwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtejhbmgrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtdpkfctwb.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtmrmiiahx.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtvhizhcmc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtzikrqina.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtxldwrbko.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtcppsxzuy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtzcbyyywq.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtezlibjfq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtqxbzzobi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gthddebixl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtytjevyrr.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gtdjoupsnc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtriefjssu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtlpulxahm.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtsoqgyywo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdgnejcy.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gtbbakntoa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtocfyurvz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtaekwzkfz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtqyolfvtm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtnxfsgclk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtpqrvfklk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtshadwyby.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtqldlovyi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtrvmxebxy.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtlzaldgqf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtbycwappt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtyspocbbc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtuhrctgvu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtaucftgcj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtysopeiis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gtwmrdondy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtaeqhdkst.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtihgtnwih.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gttmhptccr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtyklkjaco.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtfojfiqku.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdcnjqis.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gturdydane.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumujnrzz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtdibovwll.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcofkeypt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtnvrztpuc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtploryzup.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtdskrxrjr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gthzzqtfmq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtxafljdze.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtuehyoqgr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtnxvzxtso.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtktlwfoun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtjlkcgseo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtljygfdzr.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtwwqvnuyu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtstefksfm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtlvuscsbg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtufkbrsts.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtnazmazpz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenlxhokw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gthlqylfoi.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxmgwmqm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtxmktjrcq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gthmrkvfxo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtyuoyujce.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtxtfjteod.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gthtdmzwxm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtsuqtfmwb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gthfkgxpce.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtjkgpzrrj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtfdacxbpl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtzksinedv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmxqsfhsg.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtxaykxnmc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfaypqjyf.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtybydlrip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtzszadgqg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzowawops.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtfesfpsux.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnkwcrph.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gthlidwbwx.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtdnbrnutd.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtzcrzlnfo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtehhsqqko.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtvfxbtyzi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyvckclz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtvbtdiokq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtnpzwbtyj.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtxkrmttqq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtfhjcncst.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtvhfvnodx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtxzogtaeb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtwwihwikm.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtyaehglvs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtzranimmn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtjgayuomk.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtmrtratkf.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtfgekzdsu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtnytvwrqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtuawdutmg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtpcojwowh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gttofwpxnx.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gthocxqsnu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqugewjft.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtesnosnob.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtjbewiubs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtvaieecol.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtvsvsapqi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtbafvlqca.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxoghzhp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraoyebxe.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtixvvgjbz.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtybaqebml.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtkdwezeqa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtyftanbwn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtdwqixjnh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtlvazjxbx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtjaxfxgoh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtwvrlhlyv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtrisrgqmn.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtyqmkfojm.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtletzgrzq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gtpshictsj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gtvbsitfsd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtgqknjuze.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtgcayvooj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtvokpxrma.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gttarxdxty.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtdbqzpdld.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtwwzdxscs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtqbhtuqvh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtjsonicet.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtiohmzwjz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtraaxmvap.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtamuuttdc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtxcqqijkd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtglukkuof.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtvgfvyuvw.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtqqtbwucm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtdbjewguq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtmxdvyhhf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtkwyzcsdo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtuoktcuoj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtehjizdaa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtvvkbbigu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gtdmzecdoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtvbzkpsem.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtuchwjhuy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtzxyfsfjz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gteztgwjee.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtnfwatlml.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtxabzraba.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtmihaanhv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtliwswfqh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtdvspgofp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gtbimkflzd.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtuyopxkwe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtmgxrgtzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtgpwcifcc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtnnnycfxh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtztxkkruc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtzoltkkkh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtbxpeaiku.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtjpwobkbd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtyefkjfok.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtabfqqbar.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtlcbbcjdy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpfvxzceg.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtuoujipoc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtokjduwuo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gttbzjzxby.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbnhndimp.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtvuvbgnah.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gttlqqfglp.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvovnrmym.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtpvdhoxnu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtybkxylmu.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtyhspmpef.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtuqelxywl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtndbnsjec.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtfrvfdvhb.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtluztxhlw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjuruzkq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjbszhyg.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtqwanqxyq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtcnaktquw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtlamhzfas.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtymdlzmam.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtiponaljx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gticizuqsc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gttermkwyt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtstjgyhrz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtuxmdgpwl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gttcroxlgb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gttkeuzicz.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtrpxkcorl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gtnhntiwgo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtqokvtkkp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtkuwqberd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtpxeclskh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtyfcpihyz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtwxtonmue.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtthwixxzp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtjrfnblkb.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtxssksatx.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtbvnxyofu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtwknrkseb.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtzlwmtzqp.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gttraurwrv.html


<!-- 参考信息 -->