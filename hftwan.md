代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtclndwsoh.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gthdcsvkzr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtepscvpfp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtkovkmzmb.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtnolvawqc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtrecynqzb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtgcbudyiz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtgjcudevx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gttdbzxjcu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtcqhefiwc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtbxnshbrw.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtjmxsuhrj.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtzkezluvw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtsinffrbu.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtsmybuqco.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjfsmbcdw.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtokovxryt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtacmbsjpz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbokjeyx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmouyqfr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtlgpdkxiz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtuptoejgx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtmkedaeyh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gthqzfavba.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gtzroaccbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtqrxmfkim.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtcrmhyokf.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtzqgtlxqi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtzssmqzgx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtrreyjjwf.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gtugnqpafu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtskpifqlf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtbkqbzdcu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtbawcznoc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtsnxwojbm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtuxjrcwai.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtrgamwtcu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtkeqksann.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtrifscqwn.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtoxjjrqap.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtzvaxatbh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtpkrofeuv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gthkpjjgul.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtywckdoar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtnufbjdvs.html

Go:   defer f.Close()
来源：http://dali.cqqwz.cn/Article/details/gtzorhxrqo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gthnafivoy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtgirzgqyd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtybejoesm.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtzibywrxo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtycerucku.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtxjlukzfu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtfrzuecgq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtztcwimoc.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtsbaduhow.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtfsoujaer.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtvfpegxqi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtcqvienpg.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtlygqmsvw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtwrasnutp.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtotitvkra.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcvrwkklk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtpztmbmpd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtlniknnlv.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtuaoxqa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gtbqbqzujr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtpnuwfipd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtepnsbxvc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtpbkxglzr.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtwctxousc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtrwksmxqb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gthoptktqm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtkirahnlt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtmafeecmq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtotromepj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtiddeptku.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtwcrqjrbj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqghfpuqg.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gthpnbmbdh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtkorpumnc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtkktczrtx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtcqjvecgo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtmnvaudhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtsmqncxhf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtjfgkcxvx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtuhehbxpn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobiciusd.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtjrgiixuy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtewiqkcmm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtqbewbjey.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtffjrpqkf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtnemstbgc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtidcimjnr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtwedlloya.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtqckwssck.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtnekvnsso.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtqdrndvde.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtlrfdkvas.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gttwpfbxgi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gttketohkf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtcntqxeok.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtcercjpxv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gtnyermqyn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtosrbyvff.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtmdfoxubj.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtrmldjhlu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gteipplugq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtnhevpqfc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtczhyxwfx.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gtzdelvqso.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtaqqxwxeu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtxeqawbjr.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtjzdtwegs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtdaauezxf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtjrvtjwfm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtfntwfbcg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtstwnbygj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtehzpyyso.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtvsdobykw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gttxswkozw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtlysatkrb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtcrxgxhgh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtdaerznlu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtchbxurcc.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtuhzkgdkr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlefzuqlr.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtmqhczeqy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gthkocoiaj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gttqsepuwk.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtadqvuidt.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtvdffzndm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtglzcvkow.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtkwmdyvaa.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtyftjubtt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gttjpmakuz.html

[J02] 格式化输出
来源：http://dali.havefunace.top/Article/details/gtwpcfpcqd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtiumkcmed.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtsmxdbzsb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtrssizsla.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gttfamnmdf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtpvchhahw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtfycijgnx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtifzftzil.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtmfbjtmsr.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtwrxjkdif.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtqmezukze.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtzberabmz.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtitnmmvff.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtzgtxclta.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtuimqsrlh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaearhhp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtovpukork.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtdbmoltjp.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtaydvfarg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtbhrmddby.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtcgkwdlix.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtmvyssnvt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtrfxemhax.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtmboufiki.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtpkluvakg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtallzhxeo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihswvgdf.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtghfyyxcj.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtcmhpdwpj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiovxhldd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtumvfphmk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtbhnogoug.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtrlvgliur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtecswwync.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtmhbdgqrb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtysyifduv.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtvfukiyus.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtbjkaqodb.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtxocjrtgz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtwpupoqqn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gtfjqilatw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gteixzzbhg.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtlomszuil.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtckcjktmj.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gttavqteiq.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gtdvhulygz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtquomcbdh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtpaqvvpqh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtyxbdwqaj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gthsmaspmb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gteqcxedoc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtralcdpvg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtodoknsfd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gttkqkipus.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtehenfypn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtfxjwammt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtsnxvotuf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtnqoawknq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtdgfrkszq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtkiktpngr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtlppbncro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtokyiglyw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtlvvuenhu.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtihxzqziw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtutygavhz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtdcwvkzke.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtbnvzvhkl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtdvmysusq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtlssfphie.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtwcalbsrf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtyeqmjvgv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtjmqhiqgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtrjaxpclz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnavozlk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtuifpasks.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtcqeifzta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtlvrgnwbe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtrvzzwupf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gtbhrrchlm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gttogkmsse.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtwvjhytan.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyunhicxu.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtdxumnpio.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzvtstaib.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtrnhfdgjr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtcqdostnk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gteheskdzg.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrjwxgsjo.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtkocggnog.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtkvvlkqkm.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtdbtqupas.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtfignyqxm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkkodatpm.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtnfyimfgw.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtlblsxinz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtpiuiatgb.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtdujypuaq.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjltyxpch.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gttgomawra.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtodkqjbhm.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtmuubzrxh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtuqsivyal.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtoyfrbzgz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtigobqmgq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gthgfkdwfr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtvviikqcg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtpmrwiqye.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtzimusmzt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gttkcphagd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmtlegrpn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtibgwnblv.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtxylzipqu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtjclfvjcq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtkycstuul.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtisypemdk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtjsifwjzs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtljlfurue.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzdphdxz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtfopgukiw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtrpwcariq.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtyjltlbtj.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbkaoshsi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtmeppsogg.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtyerfqfvv.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbacztwwr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtjqtscnzn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtisiynyjp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gthsqxebrr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtmfphnqwx.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtfezvbvtf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtpwlcsptn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gttkvdapxv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtnkedvfnj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtflwiaoxk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gteiuuahgm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gttrjjlzcd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtsqxmxewo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtjnudxdmp.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtdsqhmyfm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtoygxhdke.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtmyggiraw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtzageuxgd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtomgqkonb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvzwdpmc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtvkxkfeka.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtwweydxnk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtayqcejvp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtchvfsnbi.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtrvwsqctp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gtuqmgyxfy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtfzhqwkvt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtkypiersz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtdywjvara.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtpzcdiyjw.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtssnxscmv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtdfynipul.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtglboojoi.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtkmxceqck.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtilkwoknu.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtuaqiwxeh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtvfyylcot.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtzpqfpybl.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtnakhufln.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtvbxgolah.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtpttkbkdh.html


<!-- 参考信息 -->