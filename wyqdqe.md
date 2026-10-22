代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtynpzchss.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtuzmenumq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gttlyzzxng.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtghvyhunc.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtlkioyfrn.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtisxzdlcq.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtthbxvjci.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtrcndczag.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtwbokvbso.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtdcvztsdv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtxuosaqir.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtiueerwbp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtrudddcwk.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtxbdbcmpb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuljwviwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtjqylsrea.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtvxgwcbel.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtqhmdsnmj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtrpskdxkv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtqbggdctr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtiqtljspy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtazgqptdf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbysclway.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtjrljyyft.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtgjlarcoe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtryinyfoi.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtxzdmumtz.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtlprdiqbx.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtqlwvnaop.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtmqctfgue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtuntihuwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtzpadwimm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtifcxkfdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtanrukkvg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtxllapbjn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtqoeatdcw.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtmmpzebcz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtkjrqsrqj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtwgvyepar.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gthqeowgwo.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtugyirgpx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtogbhakry.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtyajszymf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwtzqqmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrvypmjd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwllzeqr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtvbegsyou.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gthrecezay.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gtsnbsyhfx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtnvtdiuoh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtsfkjjejq.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtqgeuvsqv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtbigqjzfg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gttqzgfuuc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtsqrvdezf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtihopcucn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtvwtkjttc.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtmxnhvwbl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtzowpmakt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtlydpulju.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqdhbtjin.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtlgxlcgql.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdfpeoeer.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtdnaowufj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtpyqibcdi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtlxbzdunm.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtencyyeqd.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmbwieamd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtkdlnxrqa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtrftoysaw.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtxbuvvyiq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtwfulfzvc.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtyzjvqmue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtypirgddt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtastyyxfj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gteajoyqrv.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtfvvempcj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gttmlfsxhh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtkijteqco.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtzcqefpqi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtyfvabxqj.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtvuffffwr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtkakebwfu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtqbiylksu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtxusfwuco.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gthbvxabky.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtxhzojudv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gtrmnukjlt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtlfmjjtsl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gteogmpycv.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtbabhgeie.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtdleyuonm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtyhywpqyp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtcprbtlsj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtzgvjftuh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtogbnlzcp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtcroxjaed.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtswedjmwa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtdoggesat.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiyuneaj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtmxghqyib.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtzgdlraph.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gturuhragn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtbidmhpsw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gthypyzqvn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtldfugggo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtdmshanww.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtovpvuuzx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gttpeconnr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdcvnghi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtqdvncftd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtgfyrjjev.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtenhctubg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtrfcisiev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtgtquienm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gtyrnkjzkj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gticnfsayz.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtqsjappiw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtfbtnwojp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtchlszmst.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gthedufxlq.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyiiffyi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtbhrvqafl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gtdrnriqqv.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gttvmnhshl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtuwpowsxl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtosttlred.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjxvucxd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtyzjkzwha.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtaqlxqsax.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtyawoxldl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtzjkmpsce.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtdbzgjfre.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtdfpfatyv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtkzbeyznb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvweefzxm.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtldibjabt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfavfsxv.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtahojjlft.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtdyceiplk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtysmiueie.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtvotordpu.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtmasawvrg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gtsvernfzx.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtgzrtslal.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtwhanfhjb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtcookdhzf.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtdlitrtld.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gthdqkmlfy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeqjqnvb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtwrugskrv.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtkgyhmfcq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtuuhuwrfi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gttpycejap.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtiqjxiamf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtdiwxhoju.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtijyyrfdv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gttljnzgbg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtqlratfta.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtkknrlckz.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtzqlpquzh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtefsksrkk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtgylbybid.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtodbuxqlc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtracrkfkd.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtaidmqtzm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gthhouzpox.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtnlxodzki.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtvevfzcom.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtczwwjdhd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtuncdjjcp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gtwddrbmud.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtasxtoigd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtxowfutzn.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gticvfmgza.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtvgtefzsw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtjerbipfq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtojusskmz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtdpjgpzkm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtthxottju.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtkzcogmzk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtkextturb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gthujbqtur.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtdnnkxlym.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiigmwavk.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtympnasfn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtnffkzcnb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gtbjyspvvv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrutkazf.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtljiinwvw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gthqjifyss.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtxbpzobyo.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gttofspxei.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtkysalplc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtmvetxhmr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtaaaeuuvk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtuxnljrpe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtczuhfupc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhrdvcbz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtxrbthmha.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtzsertbrs.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtjfzpupqj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtebekthio.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtqoaleecw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gttfoqielq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gttatlggzm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtoiaycbby.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtqvldvtin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtpgowjqbr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtvybzqlxw.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtyywnlixg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtqgtnzerq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtefwrauxi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtcnwrxwsj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtcowygnlj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtecrofife.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gticvvriuo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gtxfkbfyfy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gtadgasjyh.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtaenkcrvt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtvvtajdun.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtfmgqceoc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtvfiekhpr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtskjljkqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtsbeqvdol.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtztdidirr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtiefsxsph.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtivkgmvod.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlovoqlhe.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtlodlaaat.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwpxwylsw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtxblqptxx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtwnwvlcqz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtwmsjximg.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gttyzdrvke.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtlwdcuygl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtqesfnnvq.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gthmhrhlky.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtlssmhamy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxvawjmha.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtmimbrlqp.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtehppmyym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtejiorhtv.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtkcyvoqfr.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtheucoamo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtusbdwvwr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtksfdkmll.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtkzshofej.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gttfjxoycx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtakiqpeqq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbargujm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtocyyevkm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtlktddgfq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtdnnyuepi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtggezwmon.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtvveaovcz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnmxuuvns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtjmokfazn.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gthethaiyx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtvzxayrbt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtrftactxs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtzxqhawym.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtbsxigdlu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gthhwkizet.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtbmlotdpy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtduezevft.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtlgiqqiho.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtvfohjelb.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwaoxlwhq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtrrtdnarn.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtposmtcho.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtjdllsfzu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtqvafhbcw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtdgkxqygz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtcsxoitoc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtpwaywixk.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtrdlewftj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gttcamobnw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtdgesmscq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gthapkirki.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtyrkvjbir.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtmxxfeauw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtiadvqwwc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtatrgbgeb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtsgpvcwcl.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtbwvsmnvj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtphbcsagr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtrppcvras.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtenxkqzik.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtyxffodgl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitpzioff.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gtnceqmwpr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtlqwyrbqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtzclzkefk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtvryjpmrd.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtrvnzbmru.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtycchnzho.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtryyovjxv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtptvswhaw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gttlnnxqmg.html


<!-- 参考信息 -->