代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gt2pdacuynx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gt2izvlrqzn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2dvpwqbis.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2zgetlzqf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gt2sooavzhf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2qfkdsoco.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2qbnnscdm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2mcpkkwdl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2psuznylr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2mjqadcvp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2abgxifco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2vuksxjfm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrkaldkn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gt2tyzqdhtr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2sdkbmgye.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gt2kaqtqvca.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gt2ubcwwzwh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2majkljpk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2zspbbcne.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2mvmguqfo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyvwznod.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2mlmxhntc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2paxqcyxq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2jfrrkuup.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2umhhrlif.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2njpsrhxo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2cfljjfev.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2rhdswxqm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2sszigjlh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2vclfkxhk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2jzpdpadb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdmduvjr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2crsglrqk.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2kzhvjrlu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2fmnyombo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2lliibymh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gt2ctsbmdar.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gt2dadcnxnr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2catdusdb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gt2ixiuiugs.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2nxsvogsp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2jkfoyhtc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2qndkoneo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2nmlwxyty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2zdhsialg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2qcebvpjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2fzboclok.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2kqsfwxzc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gt2jgnusipc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gt2khjuzcgu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2ohlvxind.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ccjontnd.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2jjkwcskx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zjvwhspg.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2mbpbqvud.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2faplatqq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2wjeuxntc.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2eequqarg.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkygfqyg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gt2bceekvzo.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gt2fbcmijmd.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2rppiizbx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gt2webyuhzh.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2dthotpuw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2cxtmktjh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2tafdodtz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gt2vdncatqm.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gt2ajbzigbc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2retiltqs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2bwwjxbtf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2fhjonciz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2itjytcuv.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2dzeuqadn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gt2lrmxoexg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2klciptty.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tencwggg.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2rfepuzlh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2dtigtxso.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2gjiwtsth.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2djmmoool.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2cfhunfin.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2mutgdhsd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gt2emndnblw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gt2hfbixicj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2buxcopos.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2fuiwpdcf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2exmzmplx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2olraxqia.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2jiyinxrn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2vpewcutn.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2ivvnpbmj.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhwrrgli.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnodfuxl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyvfswcu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2htxahhva.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2pviezmss.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2uclnncmm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2zysuhfsr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2hznoslpb.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2xnnpbzta.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2grvyeaby.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2thrtoimr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gt2mknhjcdf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2eaegsggc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzncklon.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2zusoyhpi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gt2tcbhdren.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gt2narlpvit.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2ieajivqo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2hmneghan.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gt2uqhrgomo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2llcajonx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2zxbrpoys.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmeticbf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2ndcmjiqg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2pkzlgmjp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mihxraov.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbmqjzqp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlfncixe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvdnuxbe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2uzeiacye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gt2tubjnxle.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2smbrlnsf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gt2laqnudnz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gt2xczhffsn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2ybjzzsqt.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swcsjzzr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gt2uvrrbsdx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gt2phgkfaym.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2mcehwtch.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2igxwsbxi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2omdhlafp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozkdiimj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2uirewlst.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gt2eiuudakq.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gt2cweglmep.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2hxsfakgr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2dtopzymq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2pmcgqoyn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ygwaaeuc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gt2gcwuvgnr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2xbnjdyut.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2grgeyloq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2lnkpclpv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkcnaecp.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gt2yykhcaoy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fgflepsz.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gt2lzxfegqo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2oqgcmbvt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2epdisrtl.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2hwajdrec.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ojlgznyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gt2jbwuibis.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2akgalcsm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mllgokfb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2laeoriqu.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gt2gjzdduce.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gt2mtoybjse.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gt2exxbbgwk.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2rrvecqpd.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzaktqdw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2rzsjvjxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2tfsibbwc.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2mzyjypdp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnraeinz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2txmvdsme.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2tgscbytf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2sgwegpmq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2sdwuejkg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2hssqwyln.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2tqsemewv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2qbadxmgg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2xfjjmtxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2iiglhtgg.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtdtxiuw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2aurfltfd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gt2ftnstcsh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2ffndzvfz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfyzvksn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2qyswqgdm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utllnrgy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsjohmfa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2tlfbigyd.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gt2xvmgxcbq.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ztytahcu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gt2ezpdxqic.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2cbgjuglb.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2psxtqooe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2tyuwffio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2dmgpftxm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2dwkqrawz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2abinrtwa.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2dhqxdftk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2cnbuhjal.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gt2gauwinlg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2iqjldsmf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2jdduuzks.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gt2tjwvlrfw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwvmazps.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2zqykjcya.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2njnbespq.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wawvdyqr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2rmpsbiff.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2bdhcrcyi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2xdswwrtn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2kzlildqw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzjmjaxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gt2pagvwbmi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2xqtpdrse.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2bophlbij.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gt2eyvnsvzo.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gt2zepkdveg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2phaiwrgm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2baakgpdv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2lmfvywis.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gt2ckkufpty.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2dspcuhxr.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2dmonhjez.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2ifmprzem.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2oesahmhl.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gt2inskrpbx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pjsclsld.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2xbxsxrom.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2jnkayuvv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gt2gxcgszfd.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2kpsasznn.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2uynlajjb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gt2gwijaowu.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gt2ftwnyuka.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gt2hbpkpcou.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2gtkejeiz.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2vaklnxej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrqhqojd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gt2iuqdpwhf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2qkeyoyrr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltxcfbfp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2cvcfihpn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gt2riamxfza.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwyuvrfh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gt2qlgzxlvi.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gt2hqchfwlf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2xfvtjjyp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2ttilwabt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2dlwnaptf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2pcpovwai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gradxxgr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2cruulzmm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipaeclgn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2wyrvxodc.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2ujskmqxp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gt2swsscwyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2xxbrgmtb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2ybojlgvu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2czctegpf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2mfzcdslf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2httaxyiy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gt2myuleaqd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wevxxatw.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gt2evpkhubf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivmgpnlu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gt2haefwqbv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2tnvfokju.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2wlmvkfmm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2pxunntyl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2qkdwkmpy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2ohyrzahu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehgmizcy.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2xxzfewfw.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2ireteajs.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2bqfkeccr.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eougsayq.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2osctyqeo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2nxtdrxxh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2ydcycbsd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crxwzcgt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gt2kgvwsdgc.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2seqsrsyu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gt2ffniwjyf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2kdspwjin.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2esgrjxra.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gt2kctnuyih.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gt2chlikkji.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2jywdducc.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2zcvulfec.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2fwjpubqt.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2diwbjhxv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgtxyksb.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2xhdbtfzo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2inplbjtg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2peagybqe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gt2duiaigae.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rrszeksg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2fpodsgju.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2ffovbopg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neykxmum.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2pjyoqkib.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2boggomlx.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2kwkemvdr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbizprv.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2akvzwraq.html


<!-- 参考信息 -->