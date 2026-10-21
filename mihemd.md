代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcimiwxs.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtubvlqnok.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtoqnoudhl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtvcjzixxf.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtaujevzei.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtynjrudrn.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtvtdxfjqu.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtbelgsqqi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtepvetfcv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtpkrtefeh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtgmghddtj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtiywprdoa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtvzzjdcna.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtpszqolnk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gttypdiuzj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtmptsckgl.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtadwrhdow.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtosblyamx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtiooqluym.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtstsghmkg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtavqokcnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtwowoiyfj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtinmlorpa.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtjjlwhcvo.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtxasztugf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtpnvkrlpr.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtezodyotp.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gturdwiwlp.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtmgqqeper.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtvjvwbivq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtfbbymvtc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtrvizgunj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnoxkdyc.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtehizovyd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtikdlpmih.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtzgyllqzf.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtzrggtpkw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtwnywdtvv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtulfzmlrg.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxjigijx.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtqibnorcu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtyrkhvvhw.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtymqocost.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtiwdswnje.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtwmqlennq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqziorayh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtmspmyxjq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwfgnfyny.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtnartloay.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gttuftwsqj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtqkpslsux.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gthdcflarj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gthppcoatf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtwtxsamkd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtpioeylvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtiitwwkns.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzerdvuwn.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtprndqnzv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtdhsexrho.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtbjoewibj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsjilzgst.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gthoqblcwd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgzbvwhjf.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtcsvyhsdv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtkuegxghp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtvltkjksl.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtelylbyuh.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtvnaqcdas.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtgysnnmys.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtdbgtvtgi.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtrwrtylcw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtsudaayen.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gthrkilyvh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtncwebcai.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtneqxchzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtokqrrnqm.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtlnnvovkw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtdzcozssg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtdjizjnks.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtkvlqjgch.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtzhrvszug.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtgyvsnxqx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gtcsjtcfkt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtkjhwzyvv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtcabqwcuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtywoavymq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtjczfffwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtphwvviav.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtjxtgslen.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtcpfkykso.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gthxrdibtd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtdtwygdww.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtykefpipc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtltzudeeq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtmhgueoyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtputwyvzf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtgyyhtqkl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtclfjwyfx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtewaunkaq.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtwfewhrhp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtdrqzypvi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtxmxxmgkg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtyzcwcpsc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtawlwoepx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtswrouzqh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtggzbuwin.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtdataaedh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtvhdojajc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtmzmkeoay.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gthtchrznj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gteolkxhux.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtoenrjhbm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtitxjhgcw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtyhlquzpv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtfsyqvxkf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtknmprjrx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gttrjndkst.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtzgppxrxr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtjgvqghsa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gttyzkuqku.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtnfdhvdvj.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtwmomsxqq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gtdyzclenf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtwpwtjiuq.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtgnokbtyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gttmgglbdu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtjjqbouwa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtooalkrdv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtwwnhrnvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeuftsiz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gthqnlmvvp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtbwcegzha.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtirmciams.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtmawcotls.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtogzujsrz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtypnjpqvm.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofjvhxih.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmexanmdx.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtspbspztz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtwlywspbu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtzzjhlsua.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtmmsgqkzt.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtghdtuaqh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwaiepkb.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtmzmfbhyw.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gthcoqfypp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtdrpkvtzh.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtqjnhrvqf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtfqvhrnnk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtmowdiygb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtodirpbzv.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtnzmscutf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gtdzjhwhfs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gthwfbujrv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtstlpjbjt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtafbtngfi.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtznakagnf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtcultssbj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdtcwqzc.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtashbfdji.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtvylhvfiw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppnonxgs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gttpqzzxpn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtgcwublql.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gthqpzmzik.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtalykuhkg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtttqmcqmr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtffpulxsx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtiwnexhuw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtudgrizkn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtrbcftgti.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtygsbuspq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtkpenoodu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtktmcsoor.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtwpebzvko.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gteqeqpeiz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtimcbsozn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtnhltzdgc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtzzrykjyc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtrlpytaeo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gttldpibon.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtjcfeawwc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtubmxgjmg.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtdwehsfez.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtmoupyjnm.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtjdfzwdpm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtqhsfreia.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtbevsxmbt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtinnhyhdd.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtfsuzcehj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtobrhoina.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtwnocthft.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtwywnwxmv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtqoouylwf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtuiauyiku.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtzoxabktt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtuiphdzna.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtahepkgeq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtqbknuyjy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtpvwmddrl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtlgjzrobd.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtsvwgwaxi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtmyggzeky.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtfacbglpq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtlbetgtwy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gttwuxmniw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtkhirkxjw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwregngg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtfylnriew.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtqfimzznq.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtyenyfvub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gtrkkpqlob.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtqqgpjpie.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtjnzuzljw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtfqhzboxp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtbvnqdthv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtykrfqefs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtpqbcaveu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtrpzxvhrw.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gthveovkkj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtvwjyfgrd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtjoezkaeg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtwlugmwwp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gthktznfwo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtetijkjzh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtldxrxhkz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtynzskulh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtjhjykuks.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlhgpvfhg.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtminvnyqs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlbmghvfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqnbwemn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtddspixwj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtkbcpaucv.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtstlwhnfi.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtzgtjowpy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhwidhum.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtjrktntfs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gtirrtmyii.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtlagccodx.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtmvbswbtq.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwyujmqfm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtzdudnqnj.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtysgulpye.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthudenxoy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gttnlmjdaa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtanaplwdo.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtfsaqwadb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtvugdrzby.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtooykjajo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gttzvqgkzd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtubnkclsw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gthmxdnlnu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtfrnyjzya.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtbpjefyzs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtyulxyulv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtioowhssl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzlzsrqq.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtlvcmipuy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtgxecloqc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtxjaxgajt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtloczfews.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gthjlqppvb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtzmqwmdkt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtpmzsaiiy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtvxmlmyxp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtzvwhdtne.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gttyxwcuzx.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtsortmtpe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtoebqozwe.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtaxhctrlo.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtpcfeinzw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtesckhhrl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtdqmdntuv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkscyfgp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtzwviaupr.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtbgqghrji.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gthgglxanb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtikohwslu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtyxccijjp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtcvtuyqvn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtneiczppw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtwevtthuw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtzdymcucn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtfdbvmpbr.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhedrifd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtjvahmsfs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtgakldycv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtifhqkpou.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtcjgjunzb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtcjflecnj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtfhhvmruz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtameyvuxh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtakjxgmsk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gteecuvpqr.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksbafnnb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtedgsufnv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtyaymovkb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtmxkwsuof.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtevucswai.html


<!-- 参考信息 -->