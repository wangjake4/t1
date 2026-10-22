代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2reunegti.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2zirwfyoo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gt2pxuypqjs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2fqtpesxm.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2bntakcaf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2tzjsspmv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwcdcpsa.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gt2bewxtyri.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2dxedyitd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gt2zwvjyvyr.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2hflddsod.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gt2onkfeydu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2tsiyvjgx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2iamdowid.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2vvxxwhfz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gt2wwzucosm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2xeojqzuu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2uwzfcoyx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2qxsbxkio.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2wafocfbr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2ulpqwoki.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gujwezaz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2sfjphjbj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2iitaxfyz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2jojwfgwz.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gt2cqrengpj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gt2kvmwvvxj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2hhipbgqc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qpzunqko.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgjfzcpk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuxvjyel.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2cpvzllqj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2altptqhq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2dymhviza.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpsjkmbc.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2hdmiiyxa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2gwfxqsit.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gt2cutqdkxp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2hudkdgsr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2czfpxwes.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2hhnkokmq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2hkfzjtkq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdhalrrl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gt2dyjvtmnf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2krybejdx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2wzlgsutx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjzvpfqj.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2flzhopsg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2vhtvnheb.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gt2abkfzoqt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2uxjcuxwz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gt2jzdhartb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gt2wlvffqmg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gt2pjjudqnk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2hcsnjvag.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2qeccyors.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2aexelhrd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gt2wsebdmgn.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2uspwkpzh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umhpcfap.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybihxuxl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2mntnpzzw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2ohlgjupj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2fcxnxici.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpznbqzj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2xudshsmz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnoacitp.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yowsfcxg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2ivpwkjff.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2mamrefhi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2fiarolfp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2zdnphtwq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2dolmrkcr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2wybwymju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2gvmvisuu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzsykyrp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbprzsbv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2zawqvfoi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gt2yjzuvstj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2qjcgujwu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvykvijv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2pjzqdyal.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2ljraadbe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gt2acorxrvi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2gyegzhjo.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cywfcyxn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gt2wlneoazg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gt2sxmkhdvx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gt2fqfkvtor.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gt2bnwwgznw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2ikdmjdou.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gt2oahsgohv.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxrpcjdl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heisdiza.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2wjksgjvs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2iutvtsvn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2peervnvg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2ecljaswj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2chcigndc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2otfyrcrq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gt2oycahfak.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2fvndrbwz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2yuutmcta.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2qertpyzk.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gt2jyjqqana.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2mjejqmcz.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2rxxboesx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2fpgtbrfa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2ehrwoulu.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2gxpwozqq.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2efgjxbne.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcxsejfs.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gt2zzcepcnk.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggjdxowh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2fnmmqjvf.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2fssnyunp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2zalogqbw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2lylkdumw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2attjxmzp.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2hjnohcla.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2woxdavas.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2fkaljszj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2aybnwjzr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxcttiw.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gt2sdwyibob.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2iwmzbgcm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gt2xgcsplgv.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggeforco.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2duxljfkh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2jddqxerh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2knncfssv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2usniigab.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2gujkmgxt.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2gdsgxctw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2kijdablv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhphmojw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2wbovdjko.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gt2zyccljou.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xidjokeu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2uagyrzer.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2ojvfogxb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2ydplbrqx.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gt2fntgfsas.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gt2smalgtkm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gt2npbtfkhr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2bmfqwdnd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2zejirpxb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gt2rblpwcfb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2xcpkyzzz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gt2agjxlxvm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2imgpzijz.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gt2wmgleelj.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojfafeti.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gt2oxlawxsw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2eezehxzs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2rusvkfhw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwuyvgjc.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2atvmkfpw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gt2qjzqhjij.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2wfsruqea.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2xlzubwrj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2hszxrsbe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2eyurbfpv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2sumbpqzq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdxqgokx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2oichbuyy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2onwfuwjv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuiiypts.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2aydpbsme.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gt2shcgzqmk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gt2qjffyuss.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gt2udflcfft.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gt2zowhwcar.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2rgtselwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2rfoxwdwc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2kclebasn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gt2jajhihkf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2okjzllqz.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gt2yynhsqnv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gt2mfmximwg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2kbnanlml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2yrkvqdgd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2wkcnuwbv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2kqyevfhb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwzqiiuw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2oukmssny.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2wfrhzznd.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpvldra.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2qnhlqhhd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2oylnlsnl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2btjpyach.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exeklgek.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2vyzdoruz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gt2cedxsgfp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2fogsudka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gt2jnaqtdio.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ndafqurz.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gt2lbjzeujf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxabphhl.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gt2vtxvtssr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2axpofzbz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2ijrxktxb.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2nukticrp.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2obgzlmyp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2kbnriskb.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2uofgxjnn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gt2iehcvppb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2kjbebbqx.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egepqjmy.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypjiorax.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2zjehvivo.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2xsklvaza.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2untinwor.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2lxwxqpmc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2ncmmyzpu.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2lqthqyty.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gt2ulytyfxf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2fcutgqpz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2dnmcrmvh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2cazeabev.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2diwyasmg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2czkonmyj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2crfwedfq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gt2jxxwezdb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2oltuhkjc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2lnkeeltq.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2mcfnkcdi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gt2kafizoqa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdipswis.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2bqqyjdfo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2nimpxrls.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2fcwbhchv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utbsbxbc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2fozzbkjq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2nliltlpf.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2mqzubefn.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2drufzqlk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2ycjyucdj.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ydicnzvf.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucmobyrl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2msecvdkr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gt2ixdexhfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2gtlxpjvt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gt2ullakjuy.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2njgicuav.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2fwmpfdkj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2etdrbfuw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2iqzvznui.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2xnghndoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gt2jgmpdwde.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2aiewmkye.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2rshidnko.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2kjpfljlk.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2olyigldp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2lfeyoxzx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gt2hrmzdtjv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2relvhlic.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2swywhfnn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2fwoyqnkb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gt2mhxrkkeq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2asrjzero.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2awmffzxu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2tfidrsze.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqxrgoxq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2bmxazevv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2ldawxpka.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2kmwtojvf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2fvaacony.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2vzuytbma.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ernfigka.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2evdqsnjz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2atfzfiwq.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gt2tmdjbuwq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2udmahjxs.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2ontqzzad.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2hblpbfki.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2lyonxmbt.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2qoxlfvcv.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2mhabglyk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2mroogcqd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poyhxffk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2hxgnegod.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gt2ylxqckaj.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2fufnfdng.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2oolafxkl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2owtqteca.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2rgynmjkz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgltojld.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2pulumzjx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2dslicbdk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2anhwlgmw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gt2lifxrieg.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2divgdxsh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2vbxxcyzv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2kwlmhtur.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2dtjmycab.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gt2fhgeawcu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gt2ruzzjxur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2mlimfnfn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2oztezmfa.html


<!-- 参考信息 -->