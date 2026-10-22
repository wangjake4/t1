代发 wailian999

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2cyoehqsl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2swnqxdmr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gt2kjidqmeq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2uyapnnrw.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2jedbqktj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwzxmbmu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2fsjpegfx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2mlnfwihi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gt2dnhqrhri.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2vtjfhyws.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2wrollxve.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2cpqwvmud.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2jdxoxjnt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2sgzyvzlr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2nfnlwoej.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2vohbbous.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2shsvnqzq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2yratjxxz.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2oztnglwu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gt2hzgdjwle.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2mjzjoxpz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2psbpaevh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2kgmcwrir.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2zeafujrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2vzhjfnbs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2eiyjdwxi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2tzdgdlgt.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2dumvyrsm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gt2dhzgbonc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2irfwermu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cybukhll.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2mglsyqdi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gt2ebxeggzp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2pqzzhybe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqgneloq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2trcgqyfb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2shcqgozv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2yxgtznpj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2pimythpf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2dhqixaha.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2sbcfzpix.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2rxkedfld.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gt2ylaqugpk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2pwntgfbd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2mtkayhed.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gt2hvlmkaim.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gt2nwfclozh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2gptnarcs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2iqpedgjn.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2gobpojmg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2thiwsexo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gt2yaoksfsf.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2zjpzjrav.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2lkxwjydy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gt2ucawjadf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gt2fbgdbtiv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2mzbattmp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2wkxehitx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2vnzryiut.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2egbfapgg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gt2iamodsor.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gt2vqqxxenx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2cihnntvm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2crpbkbgg.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gt2mrhprrxp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2imybtcif.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2gyoyumnt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzedeifv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2pknljxui.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2sqnoupdl.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2ejrgooxp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2btvwlfhu.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gt2lhuwedmx.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2kkpzuuad.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2hxdjwmst.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2rvdegmsj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2knptklvi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2nazohtkr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gt2cxfxmyck.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujqbsboz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2qnqudbpl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gt2qfptsnxj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awzhhqnl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2shbyerim.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2eyygjamq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2vircdywe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2scpsnerv.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2cwjfthip.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2kpjmdgjz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2bcaxsjny.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2aimvozzb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2hwauuhdb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2cbswqumw.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gt2savbylbb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2gtxlzups.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2adoiwigf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2frjkmhih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gt2dranvyui.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2iowirviv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhkmnqyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gt2gdnbjiqt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2mwfvbags.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2ixicuvcz.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2tdmgpaiv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2pyqwtmmy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2gzeoiirc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndeylknl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2zxmrnctr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2rlqaudvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2ocidclrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2wftrlqah.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdqcvvrh.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gt2rcwnkwgm.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzscrsay.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gt2jvrwtqod.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2mgvpitap.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gt2kjulybhm.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2ocdfindi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2awflngpt.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2mrsojhdj.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkaagvhv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2ktgnekdq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2blizjpdd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2nrskfvlz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2satjwylg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gt2vyjcbawe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2movbojvm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2xvcxbynj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2crndyrjs.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2abhnvezu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2tsxcprmj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2jsohdvcm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gt2bhsgkxje.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxqeaqde.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2bdedtdtb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gt2rctgsprq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gt2eintghnu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2iyzbkmcc.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2mssuglwl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjoxifc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2jplxwwsd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2klbsfkdu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2avrqsiga.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gt2jnxdklax.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2phikpzyr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gt2qwgmphdo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2gxntwwrb.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gt2qkwjacyy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2cmpxilny.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2eygzdgmc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2udnxqlpg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2hekwixka.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2gtrzppsx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gt2enhqoerc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2iixqdzsq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2smcokiic.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2etpmsskx.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2exzhqrtz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pibakcfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2jojorjac.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2fzombwim.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2babyhsji.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ixsrkale.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2okveyjrt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2eyezcvcz.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2mgskjkfx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2gtwggpbu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2xvgfubiv.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2cjqqhszb.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fgzksbwr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaigbzlu.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2bjvizyia.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2dqnwfgqi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2funlwbkj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2eubsgajq.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2jyloirjz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dcemnkry.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2futwbmhq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2tfajsrnr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2lqeyrswi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2rfttitbo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2ogqbcvvr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2dxlsvlqa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2vbsurubn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2pezzajln.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2cctsexic.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2bctkrfhw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gt2peoyeupw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2imbcsfhz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enzjctoq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2naxvziyq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2uwyhzysq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2haiaunzi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2lnvneiqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2vmopcmux.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2hhzmbrnf.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gt2mxfdfxxn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2ypwzrzmr.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2yenfkhqm.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2lxkjfjha.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2nrnybkmn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2myfuloyv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2cwtixlvj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2jlgsuqxk.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2tezdfkeb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2kqibnjpy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2xgcttpwr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2pqctutuu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2znztvdck.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2rertzlbm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2oeuetflj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2kyetixve.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2djuijztg.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gt2fqnswgoc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyqbczcz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gt2bqafgyyj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwzydanj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2eolpppmm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2amzgjlbl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2odzcnzgq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2bxhhojvb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2hhwbbstr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2mtuyubof.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2xvlchnna.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gt2faxylwyz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2fvqmexty.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kskllhrt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlgpwvgm.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gt2vmoamnwh.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qupollhk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2ixlcwnfc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ccxbccix.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2pfeascys.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2kxficolj.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2nygoawrx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gt2hynntnnk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2efzuubkx.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2dfcokkie.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2cnstndee.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzolvrti.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2fpqxhpef.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gt2hfswngky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2taqjdmfy.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2rqtffitq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2mjnpsqnh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2xxfwzjjx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2wxrqtoen.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2gelmdsld.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2xlxxysgu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gt2rggylcen.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gt2hnwenfvb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gt2bgwqmpau.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkrnyvlt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gt2qdenszqu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gt2nrltivan.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2cbdvedao.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2hbbrrqra.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2bocelvvq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2xhynkisn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gt2yvwoqsnv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2qkfbgbmm.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gt2hnkkrfdd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gt2czlrprag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2dqdbzvxk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2fdmqpeng.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2akgzvdnu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dppmvfva.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2dzxrmprw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjolyeks.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orrrvniw.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2jpipgbyg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2fccxzrwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gt2aaquyfwh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgigfqlq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2snhzfwxc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gt2exnovede.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2vmrqnydn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gt2yueaouyt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2eofzglnb.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2nkmomeaf.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2uwukqsfl.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zutpsyvv.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2jjajhjei.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2nafiicve.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2uktbktfg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2xsdtwylf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2iirbojef.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2zunfllez.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2rwytsarl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2hfworqhw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2mhezgkoj.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfyehftr.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2hbvyfhds.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gt2tzmikjnl.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2odlfqybz.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gt2kqgssabm.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2lsgadzsz.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gt2iqnodjvk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2usiitiso.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gt2dpubtmsc.html


<!-- 参考信息 -->