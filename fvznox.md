代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2smkmzefe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2zaqyhmkg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gt2fkvxwslo.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2rjatmdqn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsekyrkf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gt2ixncfzqn.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2xtqufaxr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2mgbiajsq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2fwrrdnta.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2avircxmg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2dqriffeo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2nerqzaij.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2kyoefikx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2shepgtbu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2lmjtjbyc.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gt2cclmckzg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gt2vjxhtcio.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gt2prgbixwz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2ngatjvmx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiecknmb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2iflxourc.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gt2bjhgtzcf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhehkqzg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2neyndxyb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nauyfzzq.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2twlzmbae.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2smhywejl.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2ykaklayr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmkmyowu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2zwobqcwt.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2bkpdhzeb.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2emijnucc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2cnblwbtm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sehxxmwt.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2xejcfutc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2gfuiwutd.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jqitysic.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2jqbgbkzo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2kxqmavik.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2uvfwpbpf.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gt2omzoaeit.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gt2eddlhqts.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2eebnbbng.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2zaovjqms.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2ppntohdu.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2chcrglxd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2jtvmvxyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2swojyizy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2utlcxbgu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2pgkwlijv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gt2qvyncgpe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2sptmdedx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gt2woucluyp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2knubmuxm.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2cytpimwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gt2yjfcrfbk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2weltalvs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2gdbwgcgh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2xymdvisi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2ihqxmiev.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2crefazoq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2atzctccw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2evzaemws.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gt2wdqudqxk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2pqzvzlwu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2rgtpxeqx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2ujaevyzn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2htknuhwz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gt2fzrnpmsa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfajmioo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dabpsqjp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2gxgyndea.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gt2haxnnsta.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmkekxpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gt2dvjwstme.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2sbgyblma.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2nwalhfuj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rawoeyjo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2whdjclek.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2vabryggw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2ufazgehy.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2gkvaigjo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gt2nphjycsr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2albfewtu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gt2qzlaummt.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emgexuzb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gt2mjdfmegw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2hvkmgnkr.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gt2sinazdhs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gt2yiwdlwqb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gt2itgeyxav.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2iqkdxwfp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2qldmnqwx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2grlfketw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2hgtmrvpg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2zrddanai.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gt2dpmveeff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2hcebqokx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2qdddfusx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wfgylafj.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2zvvrcxmz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xdnodwlz.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijhcwjiw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gt2jphtwpep.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2kjobbryv.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2lnajyrbq.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2mmodijde.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2vnkbchil.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2krvrnqox.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krjuvome.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2nfabgbgb.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2zadxdqcm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2igkedykb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2lzlizzhq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gt2cxtbjooj.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2imuxnbnk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2fcvfeylx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2ypfevgdm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wllwjisb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yktoddxk.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2lnomnonk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2fnavivhg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2rfldnohw.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kokhoqbm.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2fpmwudkh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuwlczhi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2uamftxon.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2ojcgvlog.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2nhkgleyd.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2ngkdklas.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2ycgmcelo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gt2dnhdlzkh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2prccyvpp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2kenynoil.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2lhzdgmfd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2hdgnzzrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2qduxhzvh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2kputxtlz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbiajewm.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2qmvbfncj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gt2bptznnsj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qddcgvzz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2osluoiba.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2junfdfhd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gt2ildpnvus.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2lhahrirg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2rvovtlor.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acrtpvif.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2fpunrfqx.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gt2xkkgxdow.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gt2swoeestb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2okxvuqhy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2hhnesrav.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gt2aqfuanbp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gt2ighowcjs.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2zzirfmxv.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwknaztw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2hqzvazif.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2rsvxhbtu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2mjyntniw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2rdyloapo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2elllhlbf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gt2mwnteaoo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2pfxcmxsw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2sbdljnlx.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gt2iquilgjd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gt2iedsyvhs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2dflipyzx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2dqmribhf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2hlqmtnro.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gt2ahzrdaye.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2bjeprdro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2nhipsaef.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gt2vgmynsdk.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2xukhqarv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfrhwptq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2xstwghdb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2gbihbpzv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2uibmuqek.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gt2fnenlpag.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2tskmobqk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gt2oztdresk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2wtvvlaio.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2oxgpakjq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ptocrfks.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2jequphyx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2ghbpxiao.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2jsyilxsx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2wgzeistz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gt2iqqxeyvr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2sfajlvww.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rniygcpm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2igkvpmrc.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gt2mdikxnzq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2klcyykze.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2rhupcgri.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2llsepgwo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2zadrnoxf.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2mqqqgvsf.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2fwywfyow.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxhqqhmn.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gt2vjvgyczv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2zvqacobp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2crtynmsn.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gt2wotctlgh.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isqpjhhn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2oelicbpb.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihegkocq.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2zhfworzp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2liyducsl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2qlpvgujf.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2dmjkjlcs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gt2eypxxprt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gt2fqlralko.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2wqgucoti.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2hkkhusar.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2atditdsz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fodnhjmn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2tfbxiweh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2byfnpfbv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2bgrswmxs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czcoxfoj.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlxxakam.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gt2dshmoahh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2ontrkyiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2hmbrnmkg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2vnleheuz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2xdapznzd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2svmiuysq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2ncylfcdr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2vrsbqpjb.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2cahjlutn.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jpvwltvi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2usuovuzl.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ldmkqdzm.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2eixfdbjo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2rcotpbgg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gt2cqdliwtb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqdbwqng.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gt2zegnxinf.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2iddljgdy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2suqbraiy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gt2pfqxbrfy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2gtappxkz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blwdebee.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2utxtklax.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2qaevnhfq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2coaqmjxc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2nupbikze.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2jlfjmrlv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2bpebonhk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnebxoim.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2kelxzivd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2vkvcgzbi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2tsewucfx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdxjlxdq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2hnuwdyep.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2acradelo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzhoudjm.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wjnapapi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyhvizdv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2qkqgtmpo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2swlydcyj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gt2guungyxz.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2anvpnhbh.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gt2lufbxadq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2rkifrrxd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vadrtquf.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2qthgzzle.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2cdqexuzy.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2tggyhrml.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gt2axdqvipw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2biuajlmg.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2ojqeuksb.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2ppnesvlb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2tienalsz.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gt2dixmxnbl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2yfhwgfte.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2bndflxqg.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2xpptvikj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2hlhmyqht.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gt2eqkoooaq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2lzfpzcal.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2tugzwwwo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gt2uqxxfhgc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gt2qywegaxa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2pkbalzcr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2abgdxxyr.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzmrbdlc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gt2pjcpyvme.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gt2islvogfv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kddzjwft.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2epswtusj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2mcxkhifp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2kfbzexjn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gt2hfwcxewj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2xtqxnjih.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gt2lwmaxqlu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2aofdxiuc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gt2diqjtomt.html


<!-- 参考信息 -->