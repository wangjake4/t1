代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2dnvzaiyx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2ugvwxmxm.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2loliqbnb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2oghlrmxq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2opgkrqve.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2vchpnmzt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2biugftxs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2pgbrogcp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gt2xnzjstdj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2xmujkskg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2ztysxobn.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2inrhifnr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2fhzulfpy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2uovntsvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2meeaaaag.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2bavceflc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2trzamaqf.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2ysguatpj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gt2iokmxiql.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2xdhixvpk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2igmtkvqw.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gt2ofuprhkc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2pltjvpwj.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2uxboapav.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2efjuvaco.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yljqvvog.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zxanqjll.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2niqiwkou.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llzjvzcs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2erntquxv.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2wkgnjsju.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2zkiubuoy.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2jykbphal.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2fcwcvadd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gt2trkeocfq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2odnuirmr.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gt2lyhnsgct.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2kbznxifu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2ahytxveu.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2vzoslvsc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2bkjbkqre.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gt2pogakkxs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gt2wqlhtmsl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2fwxgqfvr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2ywyoinbd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gt2yexjgrlj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2kuhmuuko.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2oqrqcgpc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2aboirbaf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gt2gtxtmfzp.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2vscquqae.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2nnfqzevf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2cefmcedr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dclhdmng.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2fmgcfvdl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sptnotbq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2cxfcqtnl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2ytnfdxzz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2fnrmsgwi.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2jnyzgsxo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2lxaqehpu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2etpqgqlr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxwyfylf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2sihitkel.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gt2uhnrvyfv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2okjaohke.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2dolkasmk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yknvcxmz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2dsyfarso.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2hszwyptl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gt2golahlwx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2egrhmjde.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2asvbyjhg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2xvirbowp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2xwryhzzs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2zyunzxvr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2fekrxudg.html

[I07] 忽略大小写与多行模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clfbnavg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wihssvmk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2qsxcxchz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2whuowlus.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2nirasayv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2yzsbnypx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2rpijnjpg.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gt2pleoeavb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gt2shhxixls.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2wxrlkwep.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2mdrnmwez.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2omoxnjrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2ppasdpzr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2udakgzqm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2upebdznd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvsjdvqs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gt2fwbjlnvk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2vnfudxan.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xlfdeeue.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2xazhzzlc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ibdwqtok.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2wcwdgsng.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2kdsjtqez.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2qbdexqac.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2aicnqgqn.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2mhcbjbjj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2jksjefqu.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gt2atygwwoe.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2dfchmcmn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvaqjgl.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2dimvcvfx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2uxixqgiu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyxturrv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2gupkklaa.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fojxtzup.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gt2etmydqzt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gt2itgazuqa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2jlzjnuoz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvmudwsk.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2dhslxrhx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2hdomxcos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2vvwcesux.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2euswpfma.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2vqizkjgx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2cwawbjdj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2aztlouqp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2cwafvvtk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2vlxutujs.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gt2bymgeqvu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2lkrdhrly.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gt2pfqyhovp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2mxjqdsen.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gt2ugbvfwiz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gt2juekiyit.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2uwwdfqza.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2mrzhhhpf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2bjqteqvi.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2kzexwaqn.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gt2eugxbgpx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gt2bynporcs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2yuqtwgbq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2qbvzatjf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2cgqyoprv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gt2sfzuzafj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gt2qduolprv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2ynillptb.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gt2qjgrydyo.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2qkswztuu.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pocbhvie.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gt2pxpxydso.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gt2xoozffvh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gt2fnifseko.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2gwrtejea.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2bgmpyljg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2nnzbkxne.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2svzjrxns.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2uxqplfmk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gt2xgbjzbme.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2wwwqmrez.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqfrgvyr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gt2fgjggqvb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gt2dkkikuur.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2lzhfolev.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbacqcau.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gt2fuvclclu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gt2wvkhdrei.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gt2mwktmkoo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2fsntgpih.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2saexxjzu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gt2kcaybuwd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2zxhqhiis.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gt2abezzwop.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2gkxjxhhz.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2ctnmajzj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gt2yhxwwryn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2lzeynlqo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvykmbcx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2sexrghax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gt2rcwytjuo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gt2ldijchzl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gt2fvruwfzn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2cfirjati.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gt2xhlikege.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2gfzhmrhi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2joxyyuxl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2aoknssll.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2szrpajaj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2lsrzehtw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gt2mhffwwby.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2feaxsonq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2wpvtovql.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wuhqevnz.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2cpnibubu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjuxdxlx.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2ciafflzo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2xzgbzkex.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bviocvwo.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2fauogayc.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2hnzivdlh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gt2bmplyjog.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqlxomea.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2emoxeeqp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2xchefuqj.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjpyfgfe.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2hrbfsddh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2xnmhboyr.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2juzcnkqj.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wfrwklcz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2whgkosjy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2bozhjuqg.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2aicnucrw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2fucvjdoy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gt2aypatfiv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2afaluxoc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2myhtillo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2bvuqzhvq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2dpiewccg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2kguaojzn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gt2nxnwxrbn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gt2omqqhckf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2tzwicpcx.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2xvrvghdz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2auolqbqd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2gwmkalhv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2aumddkzv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hvluoeln.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2vvhnjzby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2arzbphhb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2filbtoaq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2yvvcfbda.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2uoubkzcj.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2rktagcfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2yspjahlx.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2huoykchn.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2yjvgahkq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2dqzxolvb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gt2khsrvilb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbpjucbj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2shelvppv.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whectulc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2mqfkomxs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gt2vhspiwpg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2lqpyzysh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2quvcsafc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gt2cwxhfzhu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2ywumcyuc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2jgvhsdvm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2zcmdhgms.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2afvvskwy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2mgngtlop.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2uvwaqxxq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2hhsexpyy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2otezljqu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2ypnalqug.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2ioxblkrn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gt2unarljhl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2dskebzeo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2klinaknk.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hahpyuxv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgofvxng.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2nxqzgixk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2hwkaffje.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytxwyeil.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzxiskqb.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gt2iheafnrx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2eevyzoev.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jqdiwzyp.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2uovsmpyb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hxmkzbbo.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2jdtqbpve.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gt2fohykzfo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2juwzlyly.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2gqwomtsu.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2djjeqeou.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2eyqsksyj.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2kzadxpzw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2qsuoldfp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2rjgusxsr.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2ubmkspsz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdezvrrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2nxwewzsg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2ytbzndih.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2swwqnejp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvhhnisu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2brsxoydd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2vtuuengj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gt2dtregvgm.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2bvezpkhr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2pprkalqw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlbrvvjn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2rpyrtuym.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2jmrwulme.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2lmvewwbq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2fhjxeoue.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2vbacnpes.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2iadjwzjh.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2zggbtmtq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2hoyolyoc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2twdesczb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2ojnuomkj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2qvymvieq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2pdupjjts.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gt2mrwryujl.html


<!-- 参考信息 -->