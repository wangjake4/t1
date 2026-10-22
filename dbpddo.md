代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtishzacux.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtunscwxgs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gthaiuongo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtqbftastc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtpldfmqzz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtotrgqhur.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gthtmtoajy.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtsysxwlmg.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gttqxqnsoa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocrsrzvq.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtcdvcrlbp.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwknwxlbq.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtpuaisqnn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtrgdumanr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtjkpwoajn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtxgmslchu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtjgywsefu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtkkakglcp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtytblexar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtzltznunv.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gthebsozun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtdtoxcgtt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtbzbcmirf.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtzpkvboyo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtiodiwgvk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtjnwrkbug.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtslexrrlo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtimwnahab.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtcbpgtazo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtnniqyfdd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtvbuylmfn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtgbydueuz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtcvwnliiy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtlskosivq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gttzztutvm.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtxogegypi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtvuqtreth.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtvmackght.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtzeynyqos.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtfdhyjihw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtvijfguly.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtgugqggkq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtyknotqpl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtymlbupnk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtclpewcaj.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gttgfkybou.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwidyuybv.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtafwetsab.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtmirugqfl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtezzyaatv.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtitgycgzh.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzsrdtuhm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtltgsrmrm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtpjtksmmf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtdpxiwywg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtkarapicf.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtohwngabg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtngrbtefe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtooqgxwfi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtivbeteyc.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtxfmgiokf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvivsevj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtlqkqbfyn.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtztitpbbo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtvnqkucxv.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtmehdakif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmrdwooee.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtauffzksk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtzruiucyh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtesjtwtco.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtzrkbogaq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtuhrcycrc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtcqyxzzos.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gtsgzgkkpd.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtsfkvpoug.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtpyaparvk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtjyvjjljb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtdunqhira.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtagcuvjxv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpuhiznx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtcfjcfjqm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtdwwobxbc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtlbyuuvmq.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtbhexsynr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtxvuqsona.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtzyflustd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtmauacjjv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtbgqrdoox.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtnntbqhxt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxoctrucv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtqoykxsjq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdgkygxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtufybiahv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtmambaade.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gthcewegjn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gthfucmabh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtdpxaczlj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtktfcgdev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtnyvfffje.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtevnniabx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtzcgsswub.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtqamhcgyg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtqmovamqf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtgkamcney.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtzhfeargz.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gtbgcncvef.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtvpqmihef.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtaomgnrot.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtzltoniwq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gtbpaxmrhl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtckwctogv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkvechnq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtvorrgpvt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtodlugorr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtdnkkrkgs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtupnpzavc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtknnxopdg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtsyhvekfx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtajrfswxn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqvgoodee.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtetsffzed.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirnqkhqr.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtqduzzigr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtoujewzzf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtcxfkcssi.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtwaxgljkn.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtudelwyev.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtsaipezfy.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtveqnbwym.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtnvgnveaf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtsnnpgwik.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtnhiotuko.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtduedpsiu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtqgqghnwv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gtxwgmbwcu.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtihqddvey.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtgrfaiahm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtxraumzlv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtahipwltp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gtqjobnrqd.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtfwqvkadb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtukegfriq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtxmsupfsp.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtpmpssnur.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtwyiidwkg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtqmksfbzk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtkwwfsood.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtvokpqnpo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtthmzctnv.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtvwugkiol.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtjfpvecrx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaoujxza.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtefrgrnzs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtrxeobnvv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtrzxranoa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtygsynzrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtsksmagqz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtnmgsqhrz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtzuakvjwr.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtvlybozfv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtjlqgllhr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gthghvwesf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtzdovevdx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtmrulfwjs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtrqevbeoa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gtjjkdvlff.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtffuqjhqb.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtirzvywrr.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotiuhwgi.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtiavijenh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtkjqtxkuv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtghiqhorv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqabgwqv.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtmjclzdzv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtqxyygepf.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gttuldzkbp.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtyklwnmpm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtzgomwsbo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtaahaxpit.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtwhzrmakt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtguuhtdix.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnpclxbdn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gthkewlszt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtqcxjhctt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gteyndixcw.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtntlxhglx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtbifgsumi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtutjoftjq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtziqeyapc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtvwaogkkg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtwhxsyqol.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtfijivfxs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtmkgunfvw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukstbrmd.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtogvvszdu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtxzhbjhbk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtxomtgwmf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtijmppqxb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gttvsxbmoj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtppmdkcct.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtkfuccxew.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtdwtqnlfq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtwyhtzzfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtqytxncmc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtuloscuor.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtfmfhgxyr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gtczwnhhov.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtbrqjarja.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtrbboatzy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gtrngeoxfa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtjrupiziv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtgyxbhdcs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsnotlunc.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtunxaxwer.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnctgftmw.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtevkksrlb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtnrllezdc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtbywdqoue.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtijzvclck.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtqxvoqenb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtqxtuvxid.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtcobmwsgd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gthggdkzni.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtzknoqbjn.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gtnfidepny.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtcpjisprh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtvlzjavhp.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyylbfso.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtukqopkaf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtedpbgtby.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtynhzazvl.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtgmhafjte.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtxxpaoxtm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtgformfml.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkkipbxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtaxqyewyr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtklpnoesn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtbrphhpek.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gteubqnhip.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtjmrevauu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtxpvbfktl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtieryyjmj.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtvcyufvqj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cucudq.cn/Article/details/gtpbmjimzi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtybfzzjso.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtsthpqeer.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtpjenrnti.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtrapuryfa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtiqrrwgbs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gttzjhgdat.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtreywplwi.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtraabjwru.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtchhzbgzw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtdzcdauij.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtvevaeaul.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrgduzxd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtgiadsnqe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtzctjgofe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtrkkammpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtybsuzmim.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtsrcrptfh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtrrzvondm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtsyzjwfdc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtsqwqtcbu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtrnseejfz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtvjjufcnl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtdtuaznxh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtwbfhlyjw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gthhhwsuxc.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtskzlgwnz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtviznharw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtjvcckzhr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtukjqjgzg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprtqoeyg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtbbvczpfm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtubhdcwdy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtcrqxjlwm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtwgtcuyxl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gtgownmkym.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtoitroybh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtqbflfbgw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtyhiloblz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtlghgffrh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtmleyqbhq.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtvkvzgjof.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtqxdayoss.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtplmlqidx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjcpkogwi.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtpomdeldf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttpsemeat.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtvczyxgkr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gtujlwpess.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtqxoubtul.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtuwwsmsql.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtefikdahx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtukputhwo.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtsxxmbmqh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtvimbpqsh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtgzplvrea.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtfglgygfw.html


<!-- 参考信息 -->