代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtjitruqty.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtqocmlqgq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtrntccjya.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gthldjblhp.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtapbrzorb.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtacugrmeq.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtbpxkbfnd.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtqoryxejo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtdnlvbzfv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvrhgzqns.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfzzrwwk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtzwtlxltu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtyyoaicic.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtojyzsqcv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtquipceof.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtkpdziyiy.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtlsnsfalx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtyopbepwr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gttpeumqil.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtfoyuypxs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtvtcsgfdu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtxctzsdvl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gttgfevigk.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtyhfydxvl.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtkpqtofqx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtgytnhmrd.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtjrremofy.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtbomfsdxw.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtypeemsjl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtwrfjjadu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtpdopzkrq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtekupmjaj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtvodfdrrm.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtmaapfahj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtqoqeusbt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtwvngmrfh.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqyyshvg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtlyexruan.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtpdomsnli.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtrxvdojis.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtgtuadjaz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtrsmjspya.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtqfsswlme.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtbhnyxbbw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtbactodgk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gttgylqfey.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtsympthkw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtogrekfok.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gtyiyxyqdl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtzzpqjysd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtreexfigg.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtgezpajrb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gthoxtiiim.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtpsifeoic.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtvhkmpldi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtfacvldjj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtilimnnit.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtjrvkuksz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gthytibafj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtomchaknj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtenpaeuiv.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtcfhowddh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrzaxnjhw.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtnieuqorb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtmxqcbvnu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtemxfhjhh.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtwehtyotz.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtubgyivwe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtsmupuyjf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjvhaelwh.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtygqgdssz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtuwvtchmy.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtfjimblaz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtkqrjysua.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtuivbraom.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtexgpotkt.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbgoosjo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gttxsbyklk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtutaxjviu.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtxnrwerin.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtmhtmnsot.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtssksnxub.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtsnjfpids.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtxiyxqbvb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtlezlrzwn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtlndxrlei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtppigbleo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtekcvssyn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtiraspqaj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtecbbzrnh.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtauxkkmvs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gtdfjpdqcv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtlbxxrdku.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gttruqqdas.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtrvvkuopv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtysvhsyhj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtpbnntzsf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gteyjaycsa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtplyqfvad.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtqvltmavl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnfcjkdl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtltljgqty.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtsimhkarr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtrgchjvsa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtswuxyhfa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtfztzchoz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtxtkocgkk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gteqgtergk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtanahxoqn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtucijyyup.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtxzzflbnb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gturxdxgzu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtpwmiitqr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtlicmuone.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtaihiesnb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtaaedqvii.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtzhigxzuy.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtkqbazvoi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gteijzfgqq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtalqgvhdj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfzoldsf.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtulufnucb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtbgywsctg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtthftpcrs.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtkywgjvay.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtazpserlp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtziwkrrlu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtlzbamdvo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtjeeanzhk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtxiaqjkfl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbicnhjdj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtdzgswylu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtogqvbdue.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtxelqkknk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtauncjjfh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbojdmvhf.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgphinouu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqyxggncd.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtltpfzhvl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtawejaecg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtzqcxvnus.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtuscvxfic.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtvnlsmgqn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gticqqdkrw.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtbdxxdhgx.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtaucraijc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtnbvdgecj.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtxdhzyfur.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtfkqhhmbo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtsopewdhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtguprjcij.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtllgndyzf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtlwbseepd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtikeqxtky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtkvwqjvyu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtsplmungc.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotgsjlaf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtyrhhokft.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gthecxukrg.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtutcibyju.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtajdeouuy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtefvbribs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtszdrtufp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtzksnmdtn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gthqzcijxc.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtgkspkytf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbkonqog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtbgooaely.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gthxwkvnuz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtmkzkuyul.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtbhgewqpg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeomzndb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtzkqckjmw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtnghnpxeb.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtzqxfrtob.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtfutlxcqo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtliruhxkp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtwefazqnl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtjmlguivo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtbohfwbmz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gtowieivhi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtqozuxmjd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtobcmrean.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtvrvlcsgf.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtgrewocbs.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtzrpkscmj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gtrskydguz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtymtmqvtb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gttwcesatt.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtuskqonza.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtxkntuhus.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtizbnbtti.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtfewodzlj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtzdranihz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtxnsotyfi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtnnwnyneb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtsbonvlvi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtechukkfe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtjetkttjo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtwwgwioyg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtbnoylidl.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtgcbcwfaw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtjwktotxl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtgqdiqbfd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtrvypggjr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtdctmdakk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtlxidkxpe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtwagbtill.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtcxbsphhz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtomybxhrv.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtqsobwaow.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtawsryscj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtnbrymdzu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtljadiumr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtyqznjrvk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtrbjuvcoi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtrrnjdznt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtlowyejuv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtwzfsdshu.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtmftevrtk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtamxnigxt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtfauftewn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtbnddluzj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtslbnzxcg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gteoivptja.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtsjgxuwgo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtgbdgkwns.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtnhuwuglk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrztpefes.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtqomoxjob.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmhngthfj.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtlynyfmuu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtkthxloaq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtfpxdlelq.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtladymlcj.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtzixdcfoi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtjetwvifp.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gthmorgjcm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtbxzzqoza.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gthariouxr.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gtynckvzzt.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtpgirtxuh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtitzmgnii.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtmookavth.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gteooupdtl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtvwmuzltj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtrqohryem.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gthjizibnc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtqccqrwel.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtcklrsfni.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtiyfasnzn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtpzzsqlxp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtmrdrpngy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtbbxwctou.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtsnkmwogc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxojicofp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gticyzespd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtsrcsehns.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtubbwdjhz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdupigaf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtvwfojynr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtufxrvfmw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtltzcvqls.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtrovdzoek.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtdfmonvqp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtyjtihuca.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtjezsokyu.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtvkpvoyfs.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtncvqxwnz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtqfcxgz.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtvzphgrws.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkivozpgd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtmivwblni.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gtgjernhrx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtechcpjmq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtempynkwp.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtivitwsom.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtdhukwrka.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryyapsle.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtyobjwyka.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtywfpvoav.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gttnikubak.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtwoiqqlvz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufkhfget.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtdrrhcoky.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gteyfxpnax.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtocnwmndx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtnadocbtp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtdezlguvi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtecgzdrrp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtwgbccyge.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtbhzatkcf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtrsskypmv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtazpogaxj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtjjghnwln.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gteiozzxjo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtndplevsq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtjeumxvzk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtheftnbae.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtrvfijjdo.html


<!-- 参考信息 -->